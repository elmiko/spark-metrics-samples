# GraphiteSink output for the driver

The driver application was started with the `spark-submit` command.

This output was captured by performing a `GET` request to
`http://127.0.0.1:8000/metrics/index.json`. These values are a list of metrics that
can be further queried by their name.

```
[
  "app-20171013133250-0000.driver.BlockManager.memory.maxOffHeapMem_MB",
  "app-20171013133250-0000.driver.BlockManager.memory.maxOnHeapMem_MB",
  "app-20171013133250-0000.driver.BlockManager.memory.onHeapMemUsed_MB",
  "app-20171013133250-0000.driver.BlockManager.memory.remainingOffHeapMem_MB",
  "app-20171013133250-0000.driver.CodeGenerator.compilationTime.mean",
  "app-20171013133250-0000.driver.CodeGenerator.compilationTime.p75",
  "app-20171013133250-0000.driver.CodeGenerator.compilationTime.p98",
  "app-20171013133250-0000.driver.CodeGenerator.generatedClassSize.max",
  "app-20171013133250-0000.driver.CodeGenerator.generatedClassSize.p95",
  "app-20171013133250-0000.driver.CodeGenerator.generatedClassSize.p98",
  "app-20171013133250-0000.driver.CodeGenerator.generatedClassSize.p99",
  "app-20171013133250-0000.driver.CodeGenerator.generatedMethodSize.count",
  "app-20171013133250-0000.driver.CodeGenerator.generatedMethodSize.p50",
  "app-20171013133250-0000.driver.CodeGenerator.sourceCodeSize.p95",
  "app-20171013133250-0000.driver.CodeGenerator.sourceCodeSize.p98",
  "app-20171013133250-0000.driver.CodeGenerator.sourceCodeSize.p99",
  "app-20171013133250-0000.driver.DAGScheduler.job.allJobs",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.m5_rate",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.max",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.mean_rate",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.p95",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.p98",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.p99",
  "app-20171013133250-0000.driver.DAGScheduler.messageProcessingTime.p999",
  "app-20171013133250-0000.driver.DAGScheduler.stage.runningStages",
  "app-20171013133250-0000.driver.HiveExternalCatalog.hiveClientCalls.count",
  "app-20171013133250-0000.driver.HiveExternalCatalog.partitionsFetched.count",
  "app-20171013133250-0000.driver.jvm.PS-MarkSweep.count",
  "app-20171013133250-0000.driver.jvm.PS-Scavenge.count",
  "app-20171013133250-0000.driver.jvm.PS-Scavenge.time",
  "app-20171013133250-0000.driver.jvm.heap.init",
  "app-20171013133250-0000.driver.jvm.heap.max",
  "app-20171013133250-0000.driver.jvm.heap.used",
  "app-20171013133250-0000.driver.jvm.non-heap.max",
  "app-20171013133250-0000.driver.jvm.pools.Code-Cache.init",
  "app-20171013133250-0000.driver.jvm.pools.Code-Cache.used",
  "app-20171013133250-0000.driver.jvm.pools.Compressed-Class-Space.init",
  "app-20171013133250-0000.driver.jvm.pools.Compressed-Class-Space.max",
  "app-20171013133250-0000.driver.jvm.pools.Compressed-Class-Space.usage",
  "app-20171013133250-0000.driver.jvm.pools.Compressed-Class-Space.used",
  "app-20171013133250-0000.driver.jvm.pools.Metaspace.init",
  "app-20171013133250-0000.driver.jvm.pools.PS-Eden-Space.init",
  "app-20171013133250-0000.driver.jvm.pools.PS-Eden-Space.used",
  "app-20171013133250-0000.driver.jvm.pools.PS-Old-Gen.committed",
  "app-20171013133250-0000.driver.jvm.pools.PS-Old-Gen.init",
  "app-20171013133250-0000.driver.jvm.pools.PS-Old-Gen.max",
  "app-20171013133250-0000.driver.jvm.total.committed",
  "app-20171013133250-0000.driver.jvm.total.max",
  "carbon.agents.b75563f1bf48-a.blacklistMatches",
  "carbon.agents.b75563f1bf48-a.cache.bulk_queries",
  "carbon.agents.b75563f1bf48-a.cache.overflow",
  "carbon.agents.b75563f1bf48-a.cache.queries",
  "carbon.agents.b75563f1bf48-a.cache.queues",
  "carbon.agents.b75563f1bf48-a.cache.size",
  "carbon.agents.b75563f1bf48-a.committedPoints",
  "carbon.agents.b75563f1bf48-a.cpuUsage",
  "carbon.agents.b75563f1bf48-a.creates",
  "carbon.agents.b75563f1bf48-a.errors",
  "carbon.agents.b75563f1bf48-a.memUsage",
  "carbon.agents.b75563f1bf48-a.metricsReceived",
  "carbon.agents.b75563f1bf48-a.updateOperations",
  "carbon.agents.b75563f1bf48-a.whitelistRejects"
]
```
