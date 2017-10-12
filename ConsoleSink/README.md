# ConsoleSink

All of the metrics samples in this directory were created with the ConsoleSink.

The `metrics.properties` file was modified to add the following:

```
*.sink.console.class=org.apache.spark.metrics.sink.ConsoleSink
*.sink.console.period=10
*.sink.console.unit=seconds
```

This [tutorial-sparkpi-python-flask](https://github.com/radanalyticsio/tutorial-sparkpi-python-flask)
application was used as the driver.

