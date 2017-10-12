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
    "jvm.PS-MarkSweep.count": {
      "value": 1
    },
    "jvm.PS-MarkSweep.time": {
      "value": 17
    },
    "jvm.PS-Scavenge.count": {
      "value": 4
    },
    "jvm.PS-Scavenge.time": {
      "value": 27
    },
    "jvm.heap.committed": {
      "value": 203423744
    },
    "jvm.heap.init": {
      "value": 253755392
    },
    "jvm.heap.max": {
      "value": 954728448
    },
    "jvm.heap.usage": {
      "value": 0.09611805345513283
    },
    "jvm.heap.used": {
      "value": 92455272
    },
    "jvm.non-heap.committed": {
      "value": 40108032
    },
    "jvm.non-heap.init": {
      "value": 2555904
    },
    "jvm.non-heap.max": {
      "value": -1
    },
    "jvm.non-heap.usage": {
      "value": -39412336.0
    },
    "jvm.non-heap.used": {
      "value": 39412400
    },
    "jvm.pools.Code-Cache.committed": {
      "value": 5767168
    },
    "jvm.pools.Code-Cache.init": {
      "value": 2555904
    },
    "jvm.pools.Code-Cache.max": {
      "value": 251658240
    },
    "jvm.pools.Code-Cache.usage": {
      "value": 0.022637939453125
    },
    "jvm.pools.Code-Cache.used": {
      "value": 5697024
    },
    "jvm.pools.Compressed-Class-Space.committed": {
      "value": 4063232
    },
    "jvm.pools.Compressed-Class-Space.init": {
      "value": 0
    },
    "jvm.pools.Compressed-Class-Space.max": {
      "value": 1073741824
    },
    "jvm.pools.Compressed-Class-Space.usage": {
      "value": 0.003678850829601288
    },
    "jvm.pools.Compressed-Class-Space.used": {
      "value": 3950136
    },
    "jvm.pools.Metaspace.committed": {
      "value": 30277632
    },
    "jvm.pools.Metaspace.init": {
      "value": 0
    },
    "jvm.pools.Metaspace.max": {
      "value": -1
    },
    "jvm.pools.Metaspace.usage": {
      "value": 0.9831971007508117
    },
    "jvm.pools.Metaspace.used": {
      "value": 29768880
    },
    "jvm.pools.PS-Eden-Space.committed": {
      "value": 103284736
    },
    "jvm.pools.PS-Eden-Space.init": {
      "value": 63438848
    },
    "jvm.pools.PS-Eden-Space.max": {
      "value": 340262912
    },
    "jvm.pools.PS-Eden-Space.usage": {
      "value": 0.18802618135472843
    },
    "jvm.pools.PS-Eden-Space.used": {
      "value": 63978336
    },
    "jvm.pools.PS-Old-Gen.committed": {
      "value": 93323264
    },
    "jvm.pools.PS-Old-Gen.init": {
      "value": 169345024
    },
    "jvm.pools.PS-Old-Gen.max": {
      "value": 716177408
    },
    "jvm.pools.PS-Old-Gen.usage": {
      "value": 0.030753854776720352
    },
    "jvm.pools.PS-Old-Gen.used": {
      "value": 22025216
    },
    "jvm.pools.PS-Survivor-Space.committed": {
      "value": 6815744
    },
    "jvm.pools.PS-Survivor-Space.init": {
      "value": 10485760
    },
    "jvm.pools.PS-Survivor-Space.max": {
      "value": 6815744
    },
    "jvm.pools.PS-Survivor-Space.usage": {
      "value": 0.9465907170222356
    },
    "jvm.pools.PS-Survivor-Space.used": {
      "value": 6451720
    },
    "jvm.total.committed": {
      "value": 243531776
    },
    "jvm.total.init": {
      "value": 256311296
    },
    "jvm.total.max": {
      "value": 954728447
    },
    "jvm.total.used": {
      "value": 131875536
    },
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
