# MetricsServlet output for the driver

The driver application was started with the `spark-submit` command.

All output was captured by performing a `GET` request to
`<driver ip>:<ui port>/metrics/json/`.

```
{
  "counters": {
    "app-20171010115601-0003.driver.HiveExternalCatalog.fileCacheHits": {
      "count": 0
    },
    "app-20171010115601-0003.driver.HiveExternalCatalog.filesDiscovered": {
      "count": 0
    },
    "app-20171010115601-0003.driver.HiveExternalCatalog.hiveClientCalls": {
      "count": 0
    },
    "app-20171010115601-0003.driver.HiveExternalCatalog.parallelListingJobCount": {
      "count": 0
    },
    "app-20171010115601-0003.driver.HiveExternalCatalog.partitionsFetched": {
      "count": 0
    }
  },
  "gauges": {
    "app-20171010115601-0003.driver.BlockManager.disk.diskSpaceUsed_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.maxMem_MB": {
      "value": 366
    },
    "app-20171010115601-0003.driver.BlockManager.memory.maxOffHeapMem_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.maxOnHeapMem_MB": {
      "value": 366
    },
    "app-20171010115601-0003.driver.BlockManager.memory.memUsed_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.offHeapMemUsed_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.onHeapMemUsed_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.remainingMem_MB": {
      "value": 366
    },
    "app-20171010115601-0003.driver.BlockManager.memory.remainingOffHeapMem_MB": {
      "value": 0
    },
    "app-20171010115601-0003.driver.BlockManager.memory.remainingOnHeapMem_MB": {
      "value": 366
    },
    "app-20171010115601-0003.driver.DAGScheduler.job.activeJobs": {
      "value": 1
    },
    "app-20171010115601-0003.driver.DAGScheduler.job.allJobs": {
      "value": 1
    },
    "app-20171010115601-0003.driver.DAGScheduler.stage.failedStages": {
      "value": 0
    },
    "app-20171010115601-0003.driver.DAGScheduler.stage.runningStages": {
      "value": 1
    },
    "app-20171010115601-0003.driver.DAGScheduler.stage.waitingStages": {
      "value": 0
    }
  },
  "histograms": {
    "app-20171010115601-0003.driver.CodeGenerator.compilationTime": {
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
    "app-20171010115601-0003.driver.CodeGenerator.generatedClassSize": {
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
    "app-20171010115601-0003.driver.CodeGenerator.generatedMethodSize": {
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
    "app-20171010115601-0003.driver.CodeGenerator.sourceCodeSize": {
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
  "timers": {
    "app-20171010115601-0003.driver.DAGScheduler.messageProcessingTime": {
      "count": 1,
      "duration_units": "milliseconds",
      "m15_rate": 0.0,
      "m1_rate": 0.0,
      "m5_rate": 0.0,
      "max": 9.826995,
      "mean": 9.826995,
      "mean_rate": 0.8831491510470907,
      "min": 9.826995,
      "p50": 9.826995,
      "p75": 9.826995,
      "p95": 9.826995,
      "p98": 9.826995,
      "p99": 9.826995,
      "p999": 9.826995,
      "rate_units": "calls/second",
      "stddev": 0.0
    }
  },
  "version": "3.0.0"
}
```
