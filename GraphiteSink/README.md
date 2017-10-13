# GraphiteSink

The GraphiteSink allows you to use HTTP calls for harvesting metrics
through the
[Graphite API](https://graphite-api.readthedocs.io/en/latest/index.html). This
API provides a rich interface for querying metrics data and creating output
that includes JSON as well as graphical renderings.

These samples were creating by querying a Graphite API server running locally
with the various Spark processes.

The `metrics.properties` file was modified to add the following:

```
*.sink.graphite.class=org.apache.spark.metrics.sink.GraphiteSink
*.sink.graphite.host=127.0.0.1
*.sink.graphite.port=2003
*.sink.graphite.period=1
*.sink.graphite.unit=seconds

master.source.jvm.class=org.apache.spark.metrics.source.JvmSource
worker.source.jvm.class=org.apache.spark.metrics.source.JvmSource
driver.source.jvm.class=org.apache.spark.metrics.source.JvmSource
executor.source.jvm.class=org.apache.spark.metrics.source.JvmSource
```

This [tutorial-sparkpi-python-flask](https://github.com/radanalyticsio/tutorial-sparkpi-python-flask)
application was used as the driver.
