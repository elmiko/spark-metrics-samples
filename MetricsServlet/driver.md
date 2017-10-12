# MetricsServlet output for the driver

The driver application was started with the `spark-submit` command.

All output was captured by performing a `GET` request to
`<driver ip>:<ui port>/metrics/json/`.

```
{
  "counters": {
    "app-20171012154950-0001.driver.HiveExternalCatalog.fileCacheHits": {
      "count": 0
    },
    "app-20171012154950-0001.driver.HiveExternalCatalog.filesDiscovered": {
      "count": 0
    },
    "app-20171012154950-0001.driver.HiveExternalCatalog.hiveClientCalls": {
      "count": 0
    },
    "app-20171012154950-0001.driver.HiveExternalCatalog.parallelListingJobCount": {
      "count": 0
    },
    "app-20171012154950-0001.driver.HiveExternalCatalog.partitionsFetched": {
      "count": 0
    }
  },
  "gauges": {
    "app-20171012154950-0001.driver.BlockManager.disk.diskSpaceUsed_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.maxMem_MB": {
      "value": 366
    },
    "app-20171012154950-0001.driver.BlockManager.memory.maxOffHeapMem_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.maxOnHeapMem_MB": {
      "value": 366
    },
    "app-20171012154950-0001.driver.BlockManager.memory.memUsed_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.offHeapMemUsed_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.onHeapMemUsed_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.remainingMem_MB": {
      "value": 366
    },
    "app-20171012154950-0001.driver.BlockManager.memory.remainingOffHeapMem_MB": {
      "value": 0
    },
    "app-20171012154950-0001.driver.BlockManager.memory.remainingOnHeapMem_MB": {
      "value": 366
    },
    "app-20171012154950-0001.driver.DAGScheduler.job.activeJobs": {
      "value": 1
    },
    "app-20171012154950-0001.driver.DAGScheduler.job.allJobs": {
      "value": 1
    },
    "app-20171012154950-0001.driver.DAGScheduler.stage.failedStages": {
      "value": 0
    },
    "app-20171012154950-0001.driver.DAGScheduler.stage.runningStages": {
      "value": 1
    },
    "app-20171012154950-0001.driver.DAGScheduler.stage.waitingStages": {
      "value": 0
    },
    "app-20171012154950-0001.driver.jvm.PS-MarkSweep.count": {
      "value": 3
    },
    "app-20171012154950-0001.driver.jvm.PS-MarkSweep.time": {
      "value": 159
    },
    "app-20171012154950-0001.driver.jvm.PS-Scavenge.count": {
      "value": 7
    },
    "app-20171012154950-0001.driver.jvm.PS-Scavenge.time": {
      "value": 81
    },
    "app-20171012154950-0001.driver.jvm.heap.committed": {
      "value": 555745280
    },
    "app-20171012154950-0001.driver.jvm.heap.init": {
      "value": 253755392
    },
    "app-20171012154950-0001.driver.jvm.heap.max": {
      "value": 954728448
    },
    "app-20171012154950-0001.driver.jvm.heap.usage": {
      "value": 0.1564082774665577
    },
    "app-20171012154950-0001.driver.jvm.heap.used": {
      "value": 149327432
    },
    "app-20171012154950-0001.driver.jvm.non-heap.committed": {
      "value": 66387968
    },
    "app-20171012154950-0001.driver.jvm.non-heap.init": {
      "value": 2555904
    },
    "app-20171012154950-0001.driver.jvm.non-heap.max": {
      "value": -1
    },
    "app-20171012154950-0001.driver.jvm.non-heap.usage": {
      "value": -65229656.0
    },
    "app-20171012154950-0001.driver.jvm.non-heap.used": {
      "value": 65229720
    },
    "app-20171012154950-0001.driver.jvm.pools.Code-Cache.committed": {
      "value": 7929856
    },
    "app-20171012154950-0001.driver.jvm.pools.Code-Cache.init": {
      "value": 2555904
    },
    "app-20171012154950-0001.driver.jvm.pools.Code-Cache.max": {
      "value": 251658240
    },
    "app-20171012154950-0001.driver.jvm.pools.Code-Cache.usage": {
      "value": 0.03122406005859375
    },
    "app-20171012154950-0001.driver.jvm.pools.Code-Cache.used": {
      "value": 7857792
    },
    "app-20171012154950-0001.driver.jvm.pools.Compressed-Class-Space.committed": {
      "value": 7340032
    },
    "app-20171012154950-0001.driver.jvm.pools.Compressed-Class-Space.init": {
      "value": 0
    },
    "app-20171012154950-0001.driver.jvm.pools.Compressed-Class-Space.max": {
      "value": 1073741824
    },
    "app-20171012154950-0001.driver.jvm.pools.Compressed-Class-Space.usage": {
      "value": 0.006618499755859375
    },
    "app-20171012154950-0001.driver.jvm.pools.Compressed-Class-Space.used": {
      "value": 7106560
    },
    "app-20171012154950-0001.driver.jvm.pools.Metaspace.committed": {
      "value": 51118080
    },
    "app-20171012154950-0001.driver.jvm.pools.Metaspace.init": {
      "value": 0
    },
    "app-20171012154950-0001.driver.jvm.pools.Metaspace.max": {
      "value": -1
    },
    "app-20171012154950-0001.driver.jvm.pools.Metaspace.usage": {
      "value": 0.983411114032452
    },
    "app-20171012154950-0001.driver.jvm.pools.Metaspace.used": {
      "value": 50270088
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Eden-Space.committed": {
      "value": 241696768
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Eden-Space.init": {
      "value": 63438848
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Eden-Space.max": {
      "value": 330825728
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Eden-Space.usage": {
      "value": 0.09961196246502328
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Eden-Space.used": {
      "value": 32954200
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Old-Gen.committed": {
      "value": 300417024
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Old-Gen.init": {
      "value": 169345024
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Old-Gen.max": {
      "value": 716177408
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Old-Gen.usage": {
      "value": 0.16249218517655334
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Old-Gen.used": {
      "value": 116373232
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Survivor-Space.committed": {
      "value": 13631488
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Survivor-Space.init": {
      "value": 10485760
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Survivor-Space.max": {
      "value": 13631488
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Survivor-Space.usage": {
      "value": 0.0
    },
    "app-20171012154950-0001.driver.jvm.pools.PS-Survivor-Space.used": {
      "value": 0
    },
    "app-20171012154950-0001.driver.jvm.total.committed": {
      "value": 622133248
    },
    "app-20171012154950-0001.driver.jvm.total.init": {
      "value": 256311296
    },
    "app-20171012154950-0001.driver.jvm.total.max": {
      "value": 954728447
    },
    "app-20171012154950-0001.driver.jvm.total.used": {
      "value": 214570280
    }
  },
  "histograms": {
    "app-20171012154950-0001.driver.CodeGenerator.compilationTime": {
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
    "app-20171012154950-0001.driver.CodeGenerator.generatedClassSize": {
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
    "app-20171012154950-0001.driver.CodeGenerator.generatedMethodSize": {
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
    "app-20171012154950-0001.driver.CodeGenerator.sourceCodeSize": {
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
    "app-20171012154950-0001.driver.DAGScheduler.messageProcessingTime": {
      "count": 1,
      "duration_units": "milliseconds",
      "m15_rate": 0.0,
      "m1_rate": 0.0,
      "m5_rate": 0.0,
      "max": 15.657744,
      "mean": 15.657744,
      "mean_rate": 0.8424351650250331,
      "min": 15.657744,
      "p50": 15.657744,
      "p75": 15.657744,
      "p95": 15.657744,
      "p98": 15.657744,
      "p99": 15.657744,
      "p999": 15.657744,
      "rate_units": "calls/second",
      "stddev": 0.0
    }
  },
  "version": "3.0.0"
}
```
