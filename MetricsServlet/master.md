# MetricsServlet output for the master

The master was started with the `spark-class` command.

All output was captured by performing a `GET` request to
`<master ip>:<ui port>/metrics/master/json/`.

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
      "value": 21
    },
    "jvm.PS-Scavenge.count": {
      "value": 3
    },
    "jvm.PS-Scavenge.time": {
      "value": 18
    },
    "jvm.heap.committed": {
      "value": 235405312
    },
    "jvm.heap.init": {
      "value": 253755392
    },
    "jvm.heap.max": {
      "value": 954728448
    },
    "jvm.heap.usage": {
      "value": 0.1299843617941507
    },
    "jvm.heap.used": {
      "value": 124099768
    },
    "jvm.non-heap.committed": {
      "value": 39387136
    },
    "jvm.non-heap.init": {
      "value": 2555904
    },
    "jvm.non-heap.max": {
      "value": -1
    },
    "jvm.non-heap.usage": {
      "value": -37803608.0
    },
    "jvm.non-heap.used": {
      "value": 37803672
    },
    "jvm.pools.Code-Cache.committed": {
      "value": 5570560
    },
    "jvm.pools.Code-Cache.init": {
      "value": 2555904
    },
    "jvm.pools.Code-Cache.max": {
      "value": 251658240
    },
    "jvm.pools.Code-Cache.usage": {
      "value": 0.01876068115234375
    },
    "jvm.pools.Code-Cache.used": {
      "value": 4721280
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
      "value": 0.0035966336727142334
    },
    "jvm.pools.Compressed-Class-Space.used": {
      "value": 3861856
    },
    "jvm.pools.Metaspace.committed": {
      "value": 29753344
    },
    "jvm.pools.Metaspace.init": {
      "value": 0
    },
    "jvm.pools.Metaspace.max": {
      "value": -1
    },
    "jvm.pools.Metaspace.usage": {
      "value": 0.9822960404047357
    },
    "jvm.pools.Metaspace.used": {
      "value": 29226592
    },
    "jvm.pools.PS-Eden-Space.committed": {
      "value": 126877696
    },
    "jvm.pools.PS-Eden-Space.init": {
      "value": 63438848
    },
    "jvm.pools.PS-Eden-Space.max": {
      "value": 336592896
    },
    "jvm.pools.PS-Eden-Space.usage": {
      "value": 0.35358868655386
    },
    "jvm.pools.PS-Eden-Space.used": {
      "value": 119015440
    },
    "jvm.pools.PS-Old-Gen.committed": {
      "value": 98041856
    },
    "jvm.pools.PS-Old-Gen.init": {
      "value": 169345024
    },
    "jvm.pools.PS-Old-Gen.max": {
      "value": 716177408
    },
    "jvm.pools.PS-Old-Gen.usage": {
      "value": 0.007099257730285734
    },
    "jvm.pools.PS-Old-Gen.used": {
      "value": 5084328
    },
    "jvm.pools.PS-Survivor-Space.committed": {
      "value": 10485760
    },
    "jvm.pools.PS-Survivor-Space.init": {
      "value": 10485760
    },
    "jvm.pools.PS-Survivor-Space.max": {
      "value": 10485760
    },
    "jvm.pools.PS-Survivor-Space.usage": {
      "value": 0.0
    },
    "jvm.pools.PS-Survivor-Space.used": {
      "value": 0
    },
    "jvm.total.committed": {
      "value": 274792448
    },
    "jvm.total.init": {
      "value": 256311296
    },
    "jvm.total.max": {
      "value": 954728447
    },
    "jvm.total.used": {
      "value": 161918840
    },
    "master.aliveWorkers": {
      "value": 1
    },
    "master.apps": {
      "value": 0
    },
    "master.waitingApps": {
      "value": 0
    },
    "master.workers": {
      "value": 1
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
