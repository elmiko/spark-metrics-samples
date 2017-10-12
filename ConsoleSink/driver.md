# ConsoleSink output for the driver

The driver application was started with the `spark-submit` command.

Output was obtained by collecting the stdout log output.

```
10/12/17 4:59:53 PM ============================================================

-- Gauges ----------------------------------------------------------------------
app-20171012165951-0000.driver.BlockManager.disk.diskSpaceUsed_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.maxMem_MB
             value = 732
app-20171012165951-0000.driver.BlockManager.memory.maxOffHeapMem_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.maxOnHeapMem_MB
             value = 732
app-20171012165951-0000.driver.BlockManager.memory.memUsed_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.offHeapMemUsed_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.onHeapMemUsed_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.remainingMem_MB
             value = 732
app-20171012165951-0000.driver.BlockManager.memory.remainingOffHeapMem_MB
             value = 0
app-20171012165951-0000.driver.BlockManager.memory.remainingOnHeapMem_MB
             value = 732
app-20171012165951-0000.driver.DAGScheduler.job.activeJobs
             value = 0
app-20171012165951-0000.driver.DAGScheduler.job.allJobs
             value = 1
app-20171012165951-0000.driver.DAGScheduler.stage.failedStages
             value = 0
app-20171012165951-0000.driver.DAGScheduler.stage.runningStages
             value = 0
app-20171012165951-0000.driver.DAGScheduler.stage.waitingStages
             value = 0
app-20171012165951-0000.driver.jvm.PS-MarkSweep.count
             value = 2
app-20171012165951-0000.driver.jvm.PS-MarkSweep.time
             value = 89
app-20171012165951-0000.driver.jvm.PS-Scavenge.count
             value = 6
app-20171012165951-0000.driver.jvm.PS-Scavenge.time
             value = 62
app-20171012165951-0000.driver.jvm.heap.committed
             value = 341311488
app-20171012165951-0000.driver.jvm.heap.init
             value = 253755392
app-20171012165951-0000.driver.jvm.heap.max
             value = 954728448
app-20171012165951-0000.driver.jvm.heap.usage
             value = 0.17357724738081753
app-20171012165951-0000.driver.jvm.heap.used
             value = 165719136
app-20171012165951-0000.driver.jvm.non-heap.committed
             value = 64815104
app-20171012165951-0000.driver.jvm.non-heap.init
             value = 2555904
app-20171012165951-0000.driver.jvm.non-heap.max
             value = -1
app-20171012165951-0000.driver.jvm.non-heap.usage
             value = -6.3587248E7
app-20171012165951-0000.driver.jvm.non-heap.used
             value = 63587312
app-20171012165951-0000.driver.jvm.pools.Code-Cache.committed
             value = 7667712
app-20171012165951-0000.driver.jvm.pools.Code-Cache.init
             value = 2555904
app-20171012165951-0000.driver.jvm.pools.Code-Cache.max
             value = 251658240
app-20171012165951-0000.driver.jvm.pools.Code-Cache.usage
             value = 0.030120086669921876
app-20171012165951-0000.driver.jvm.pools.Code-Cache.used
             value = 7579968
app-20171012165951-0000.driver.jvm.pools.Compressed-Class-Space.committed
             value = 7208960
app-20171012165951-0000.driver.jvm.pools.Compressed-Class-Space.init
             value = 0
app-20171012165951-0000.driver.jvm.pools.Compressed-Class-Space.max
             value = 1073741824
app-20171012165951-0000.driver.jvm.pools.Compressed-Class-Space.usage
             value = 0.006461292505264282
app-20171012165951-0000.driver.jvm.pools.Compressed-Class-Space.used
             value = 6937760
app-20171012165951-0000.driver.jvm.pools.Metaspace.committed
             value = 49938432
app-20171012165951-0000.driver.jvm.pools.Metaspace.init
             value = 0
app-20171012165951-0000.driver.jvm.pools.Metaspace.max
             value = -1
app-20171012165951-0000.driver.jvm.pools.Metaspace.usage
             value = 0.982728011964813
app-20171012165951-0000.driver.jvm.pools.Metaspace.used
             value = 49075896
app-20171012165951-0000.driver.jvm.pools.PS-Eden-Space.committed
             value = 186646528
app-20171012165951-0000.driver.jvm.pools.PS-Eden-Space.init
             value = 63438848
app-20171012165951-0000.driver.jvm.pools.PS-Eden-Space.max
             value = 332922880
app-20171012165951-0000.driver.jvm.pools.PS-Eden-Space.usage
             value = 0.3778787688007505
app-20171012165951-0000.driver.jvm.pools.PS-Eden-Space.used
             value = 125804488
app-20171012165951-0000.driver.jvm.pools.PS-Old-Gen.committed
             value = 143130624
app-20171012165951-0000.driver.jvm.pools.PS-Old-Gen.init
             value = 169345024
app-20171012165951-0000.driver.jvm.pools.PS-Old-Gen.max
             value = 716177408
app-20171012165951-0000.driver.jvm.pools.PS-Old-Gen.usage
             value = 0.039653325674299966
app-20171012165951-0000.driver.jvm.pools.PS-Old-Gen.used
             value = 28398816
app-20171012165951-0000.driver.jvm.pools.PS-Survivor-Space.committed
             value = 11534336
app-20171012165951-0000.driver.jvm.pools.PS-Survivor-Space.init
             value = 10485760
app-20171012165951-0000.driver.jvm.pools.PS-Survivor-Space.max
             value = 11534336
app-20171012165951-0000.driver.jvm.pools.PS-Survivor-Space.usage
             value = 0.9983957464044745
app-20171012165951-0000.driver.jvm.pools.PS-Survivor-Space.used
             value = 11515832
app-20171012165951-0000.driver.jvm.total.committed
             value = 406126592
app-20171012165951-0000.driver.jvm.total.init
             value = 256311296
app-20171012165951-0000.driver.jvm.total.max
             value = 954728447
app-20171012165951-0000.driver.jvm.total.used
             value = 229324832

-- Counters --------------------------------------------------------------------
app-20171012165951-0000.driver.HiveExternalCatalog.fileCacheHits
             count = 0
app-20171012165951-0000.driver.HiveExternalCatalog.filesDiscovered
             count = 0
app-20171012165951-0000.driver.HiveExternalCatalog.hiveClientCalls
             count = 0
app-20171012165951-0000.driver.HiveExternalCatalog.parallelListingJobCount
             count = 0
app-20171012165951-0000.driver.HiveExternalCatalog.partitionsFetched
             count = 0

-- Histograms ------------------------------------------------------------------
app-20171012165951-0000.driver.CodeGenerator.compilationTime
             count = 0
               min = 0
               max = 0
              mean = 0.00
            stddev = 0.00
            median = 0.00
              75% <= 0.00
              95% <= 0.00
              98% <= 0.00
              99% <= 0.00
            99.9% <= 0.00
app-20171012165951-0000.driver.CodeGenerator.generatedClassSize
             count = 0
               min = 0
               max = 0
              mean = 0.00
            stddev = 0.00
            median = 0.00
              75% <= 0.00
              95% <= 0.00
              98% <= 0.00
              99% <= 0.00
            99.9% <= 0.00
app-20171012165951-0000.driver.CodeGenerator.generatedMethodSize
             count = 0
               min = 0
               max = 0
              mean = 0.00
            stddev = 0.00
            median = 0.00
              75% <= 0.00
              95% <= 0.00
              98% <= 0.00
              99% <= 0.00
            99.9% <= 0.00
app-20171012165951-0000.driver.CodeGenerator.sourceCodeSize
             count = 0
               min = 0
               max = 0
              mean = 0.00
            stddev = 0.00
            median = 0.00
              75% <= 0.00
              95% <= 0.00
              98% <= 0.00
              99% <= 0.00
            99.9% <= 0.00

-- Timers ----------------------------------------------------------------------
app-20171012165951-0000.driver.DAGScheduler.messageProcessingTime
             count = 22
         mean rate = 8.78 calls/second
     1-minute rate = 0.00 calls/second
     5-minute rate = 0.00 calls/second
    15-minute rate = 0.00 calls/second
               min = 0.03 milliseconds
               max = 148.73 milliseconds
              mean = 9.54 milliseconds
            stddev = 30.75 milliseconds
            median = 0.96 milliseconds
              75% <= 3.78 milliseconds
              95% <= 22.64 milliseconds
              98% <= 148.73 milliseconds
              99% <= 148.73 milliseconds
            99.9% <= 148.73 milliseconds
```
