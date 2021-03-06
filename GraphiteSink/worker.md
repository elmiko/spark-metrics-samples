# GraphiteSink output for the worker

The worker was started with the `spark-class` command.

This output was captured by performing a `GET` request to
`http://127.0.0.1:8000/metrics/index.json`. These values are a list of metrics that
can be further queried by their name.

```
[
  "CodeGenerator.compilationTime.max",
  "CodeGenerator.compilationTime.mean",
  "CodeGenerator.compilationTime.min",
  "CodeGenerator.compilationTime.p50",
  "CodeGenerator.compilationTime.p75",
  "CodeGenerator.compilationTime.p95",
  "CodeGenerator.compilationTime.p98",
  "CodeGenerator.compilationTime.p99",
  "CodeGenerator.compilationTime.p999",
  "CodeGenerator.compilationTime.stddev",
  "CodeGenerator.generatedClassSize.max",
  "CodeGenerator.generatedClassSize.mean",
  "CodeGenerator.generatedClassSize.min",
  "CodeGenerator.generatedClassSize.p50",
  "CodeGenerator.generatedClassSize.p75",
  "CodeGenerator.generatedClassSize.p999",
  "CodeGenerator.generatedMethodSize.count",
  "CodeGenerator.generatedMethodSize.max",
  "CodeGenerator.generatedMethodSize.mean",
  "CodeGenerator.generatedMethodSize.p50",
  "CodeGenerator.generatedMethodSize.p75",
  "CodeGenerator.generatedMethodSize.p95",
  "CodeGenerator.generatedMethodSize.p98",
  "CodeGenerator.generatedMethodSize.p99",
  "CodeGenerator.generatedMethodSize.p999",
  "CodeGenerator.sourceCodeSize.max",
  "CodeGenerator.sourceCodeSize.mean",
  "CodeGenerator.sourceCodeSize.min",
  "CodeGenerator.sourceCodeSize.p50",
  "CodeGenerator.sourceCodeSize.p75",
  "CodeGenerator.sourceCodeSize.p98",
  "CodeGenerator.sourceCodeSize.p99",
  "CodeGenerator.sourceCodeSize.p999",
  "HiveExternalCatalog.fileCacheHits.count",
  "HiveExternalCatalog.filesDiscovered.count",
  "HiveExternalCatalog.hiveClientCalls.count",
  "HiveExternalCatalog.parallelListingJobCount.count",
  "carbon.agents.0dd478f6ae43-a.blacklistMatches",
  "carbon.agents.0dd478f6ae43-a.cache.bulk_queries",
  "carbon.agents.0dd478f6ae43-a.cache.overflow",
  "carbon.agents.0dd478f6ae43-a.cache.queries",
  "carbon.agents.0dd478f6ae43-a.cache.queues",
  "carbon.agents.0dd478f6ae43-a.cache.size",
  "carbon.agents.0dd478f6ae43-a.committedPoints",
  "carbon.agents.0dd478f6ae43-a.cpuUsage",
  "carbon.agents.0dd478f6ae43-a.creates",
  "carbon.agents.0dd478f6ae43-a.errors",
  "carbon.agents.0dd478f6ae43-a.memUsage",
  "carbon.agents.0dd478f6ae43-a.metricsReceived",
  "carbon.agents.0dd478f6ae43-a.updateOperations",
  "carbon.agents.0dd478f6ae43-a.whitelistRejects",
  "jvm.PS-MarkSweep.count",
  "jvm.PS-Scavenge.count",
  "jvm.PS-Scavenge.time",
  "jvm.heap.committed",
  "jvm.heap.init",
  "jvm.heap.max",
  "jvm.heap.usage",
  "jvm.non-heap.init",
  "jvm.non-heap.max",
  "jvm.non-heap.used",
  "jvm.pools.Code-Cache.committed",
  "jvm.pools.Code-Cache.max",
  "jvm.pools.Code-Cache.usage",
  "jvm.pools.Code-Cache.used",
  "jvm.pools.Compressed-Class-Space.committed",
  "jvm.pools.Compressed-Class-Space.init",
  "jvm.pools.Compressed-Class-Space.max",
  "jvm.pools.Compressed-Class-Space.usage",
  "jvm.pools.Compressed-Class-Space.used",
  "jvm.pools.Metaspace.init",
  "jvm.pools.Metaspace.max",
  "jvm.pools.Metaspace.usage",
  "jvm.pools.Metaspace.used",
  "jvm.pools.PS-Eden-Space.committed",
  "jvm.pools.PS-Eden-Space.init",
  "jvm.pools.PS-Eden-Space.usage",
  "jvm.pools.PS-Eden-Space.used",
  "jvm.pools.PS-Old-Gen.committed",
  "jvm.pools.PS-Old-Gen.init",
  "jvm.pools.PS-Old-Gen.usage",
  "jvm.pools.PS-Survivor-Space.committed",
  "jvm.pools.PS-Survivor-Space.init",
  "jvm.pools.PS-Survivor-Space.max",
  "jvm.pools.PS-Survivor-Space.usage",
  "jvm.pools.PS-Survivor-Space.used",
  "jvm.total.committed",
  "jvm.total.init",
  "jvm.total.max",
  "jvm.total.used",
  "worker.coresFree",
  "worker.coresUsed",
  "worker.executors",
  "worker.memFree_MB",
  "worker.memUsed_MB"
]
```
