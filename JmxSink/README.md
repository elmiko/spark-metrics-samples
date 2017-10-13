# JmxSink

The JmxSink allows you to use JVM agents for connecting to the metrics
sources. The samples in this file represent some of what you can do with
that interface.

These samples were created by using the [Jolokia](https://jolokia.org) agent
to create a REST interface.

The `metrics.properties` file was modified to add the following:

```
*.sink.jmx.class=org.apache.spark.metrics.sink.JmxSink

master.source.jvm.class=org.apache.spark.metrics.source.JvmSource
worker.source.jvm.class=org.apache.spark.metrics.source.JvmSource
driver.source.jvm.class=org.apache.spark.metrics.source.JvmSource
executor.source.jvm.class=org.apache.spark.metrics.source.JvmSource
```

The `spark-defatuls.conf` file was modified to add the following:

```
spark.driver.extraJavaOptions -Dcom.sun.management.jmxremote -Dcom.sun.management.jmxremote.authenticate=false -Dcom.sun.management.jmxremote.ssl=false -Dcom.sun.management.jmxremote.port=19150 -Dcom.sun.management.jmxremote.local.only=false -Djava.rmi.server.hostname=127.0.0.1 -Dcom.sun.management.jmxremote.rmi.port=19151
```

This [tutorial-sparkpi-python-flask](https://github.com/radanalyticsio/tutorial-sparkpi-python-flask)
application was used as the driver.

The JSON samples that follow were taken by querying the Jolokia agent
associated with the Spark master process. The master was started with the
following command line options

```
spark-class -javaagent:jolokia-jvm-agent.jar=port=19150,host=127.0.0.1
```

A `GET` request to `http://<spark master host>:19150/jolokia/` produces this
output describing the metadata for Jolokia:

```
{
    "request": {
        "type": "version"
    },
        "status": 200,
        "timestamp": 1507848259,
        "value": {
            "agent": "1.3.7",
            "config": {
                "agentContext": "/jolokia",
                "agentId": "10.0.1.112-22456-5d22bbb7-jvm",
                "agentType": "jvm",
                "debug": "false",
                "debugMaxEntries": "100",
                "discoveryEnabled": "true",
                "historyMaxEntries": "10",
                "maxCollectionSize": "0",
                "maxDepth": "15",
                "maxObjects": "0"
            },
            "info": {
                "product": "jetty",
                "vendor": "Mortbay",
                "version": "6.1.26"
            },
            "protocol": "7.2"
        }
}
```

Jolokia has a deep query language that can be used from HTTP requests, this
is one example that queries the memory heap usage of the master. A
`GET` request to
`http://<spark master host>:19150/jolokia/read/java.lang:type=Memory/HeapMemoryUsage`
produces this JSON output:

```
{
    "request": {
        "attribute": "HeapMemoryUsage",
            "mbean": "java.lang:type=Memory",
            "type": "read"
    },
        "status": 200,
        "timestamp": 1507848084,
        "value": {
            "committed": 200802304,
            "init": 253755392,
            "max": 954728448,
            "used": 94756440
        }
}
```
