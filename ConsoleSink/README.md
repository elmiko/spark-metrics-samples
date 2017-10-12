# ConsoleSink

All of the metrics samples in this directory were created with the ConsoleSink.

The `metrics.properties` file was modified to add the following:

```
*.sink.console.class=org.apache.spark.metrics.sink.ConsoleSink
*.sink.console.period=5
*.sink.console.unit=seconds

master.source.jvm.class=org.apache.spark.metrics.source.JvmSource
worker.source.jvm.class=org.apache.spark.metrics.source.JvmSource
driver.source.jvm.class=org.apache.spark.metrics.source.JvmSource
executor.source.jvm.class=org.apache.spark.metrics.source.JvmSource
```

This [tutorial-sparkpi-python-flask](https://github.com/radanalyticsio/tutorial-sparkpi-python-flask)
application was used as the driver.

