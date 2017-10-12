# ConsoleSink output for the driver

The driver application was started with the `spark-submit` command.

Output was obtained by collecting the stdout log output.

```
10/10/17 5:05:38 PM ============================================================

-- Gauges ----------------------------------------------------------------------
app-20171010170536-0000.driver.BlockManager.disk.diskSpaceUsed_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.maxMem_MB
             value = 732
app-20171010170536-0000.driver.BlockManager.memory.maxOffHeapMem_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.maxOnHeapMem_MB
             value = 732
app-20171010170536-0000.driver.BlockManager.memory.memUsed_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.offHeapMemUsed_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.onHeapMemUsed_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.remainingMem_MB
             value = 732
app-20171010170536-0000.driver.BlockManager.memory.remainingOffHeapMem_MB
             value = 0
app-20171010170536-0000.driver.BlockManager.memory.remainingOnHeapMem_MB
             value = 732
app-20171010170536-0000.driver.DAGScheduler.job.activeJobs
             value = 0
app-20171010170536-0000.driver.DAGScheduler.job.allJobs
             value = 1
app-20171010170536-0000.driver.DAGScheduler.stage.failedStages
             value = 0
app-20171010170536-0000.driver.DAGScheduler.stage.runningStages
             value = 0
app-20171010170536-0000.driver.DAGScheduler.stage.waitingStages
             value = 0

-- Counters --------------------------------------------------------------------
app-20171010170536-0000.driver.HiveExternalCatalog.fileCacheHits
             count = 0
app-20171010170536-0000.driver.HiveExternalCatalog.filesDiscovered
             count = 0
app-20171010170536-0000.driver.HiveExternalCatalog.hiveClientCalls
             count = 0
app-20171010170536-0000.driver.HiveExternalCatalog.parallelListingJobCount
             count = 0
app-20171010170536-0000.driver.HiveExternalCatalog.partitionsFetched
             count = 0

-- Histograms ------------------------------------------------------------------
app-20171010170536-0000.driver.CodeGenerator.compilationTime
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
app-20171010170536-0000.driver.CodeGenerator.generatedClassSize
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
app-20171010170536-0000.driver.CodeGenerator.generatedMethodSize
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
app-20171010170536-0000.driver.CodeGenerator.sourceCodeSize
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
app-20171010170536-0000.driver.DAGScheduler.messageProcessingTime
             count = 6
         mean rate = 2.29 calls/second
     1-minute rate = 0.00 calls/second
     5-minute rate = 0.00 calls/second
    15-minute rate = 0.00 calls/second
               min = 0.05 milliseconds
               max = 160.00 milliseconds
              mean = 29.43 milliseconds
            stddev = 58.18 milliseconds
            median = 4.40 milliseconds
              75% <= 7.45 milliseconds
              95% <= 160.00 milliseconds
              98% <= 160.00 milliseconds
              99% <= 160.00 milliseconds
            99.9% <= 160.00 milliseconds
```
