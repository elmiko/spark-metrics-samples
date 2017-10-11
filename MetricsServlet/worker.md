# MetricsServlet output for the worker

The driver application was started with the `spark-class` command.

All output was captured by performing a `GET` request to
`<worker ip>:<ui port>/metrics/json/`.

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
    "worker.coresFree": {
      "value": 8
    },
    "worker.coresUsed": {
      "value": 0
    },
    "worker.executors": {
      "value": 0
    },
    "worker.memFree_MB": {
      "value": 14449
    },
    "worker.memUsed_MB": {
      "value": 0
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
