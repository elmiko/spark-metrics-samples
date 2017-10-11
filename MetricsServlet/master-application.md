# MetricsServlet output for the master application endpoint

The master was started with the `spark-class` command.

All output was captured by performing a `GET` request to
`<master ip>:<ui port>/metrics/applications/json/`.

```
{
  "counters": {
    "HiveExternalCatalog.fileCacheHits": {
      "count": 0
    },
    "HiveExternalCatalog.filesDiscovered": {
      "count": 0
    },
    "HiveExternalCatalog.hiveClientCalls": {
      "count": 0
    },
    "HiveExternalCatalog.parallelListingJobCount": {
      "count": 0
    },
    "HiveExternalCatalog.partitionsFetched": {
      "count": 0
    }
  },
  "gauges": {
    "application.PythonPi.1507650357866.cores": {
      "value": 8
    },
    "application.PythonPi.1507650357866.runtime_ms": {
      "value": 2405
    },
    "application.PythonPi.1507650357866.status": {
      "value": "FINISHED"
    },
    "application.PythonPi.1507650877411.cores": {
      "value": 8
    },
    "application.PythonPi.1507650877411.runtime_ms": {
      "value": 2320
    },
    "application.PythonPi.1507650877411.status": {
      "value": "FINISHED"
    },
    "application.PythonPi.1507650900220.cores": {
      "value": 8
    },
    "application.PythonPi.1507650900220.runtime_ms": {
      "value": 2522
    },
    "application.PythonPi.1507650900220.status": {
      "value": "FINISHED"
    },
    "application.PythonPi.1507650961955.cores": {
      "value": 8
    },
    "application.PythonPi.1507650961955.runtime_ms": {
      "value": 2026
    },
    "application.PythonPi.1507650961955.status": {
      "value": "FINISHED"
    }
  },
  "histograms": {
    "CodeGenerator.compilationTime": {
      "count": 0,
      "max": 0,
      "mean": 0.0,
      "min": 0,
      "p50": 0.0,
      "p75": 0.0,
      "p95": 0.0,
      "p98": 0.0,
      "p99": 0.0,
      "p999": 0.0,
      "stddev": 0.0
    },
    "CodeGenerator.generatedClassSize": {
      "count": 0,
      "max": 0,
      "mean": 0.0,
      "min": 0,
      "p50": 0.0,
      "p75": 0.0,
      "p95": 0.0,
      "p98": 0.0,
      "p99": 0.0,
      "p999": 0.0,
      "stddev": 0.0
    },
    "CodeGenerator.generatedMethodSize": {
      "count": 0,
      "max": 0,
      "mean": 0.0,
      "min": 0,
      "p50": 0.0,
      "p75": 0.0,
      "p95": 0.0,
      "p98": 0.0,
      "p99": 0.0,
      "p999": 0.0,
      "stddev": 0.0
    },
    "CodeGenerator.sourceCodeSize": {
      "count": 0,
      "max": 0,
      "mean": 0.0,
      "min": 0,
      "p50": 0.0,
      "p75": 0.0,
      "p95": 0.0,
      "p98": 0.0,
      "p99": 0.0,
      "p999": 0.0,
      "stddev": 0.0
    }
  },
  "meters": {},
  "timers": {},
  "version": "3.0.0"
}
```
