## Questions and Exercises {.unlisted .unnumbered}

1. Solve the `perf-ninja::data_packing` lab assignment, in which you need to make the data structure more compact.
2. Solve the `perf-ninja::huge_pages_1` lab assignment using methods we discussed in [@sec:secDTLB]. Observe any changes in performance, huge page allocation in `/proc/meminfo`, and CPU performance counters that measure DTLB loads and misses.
3. Solve the `perf-ninja::swmem_prefetch_1` lab assignment by implementing explicit memory prefetching for future loop iterations.
4. Describe what it takes for a piece of code to be cache-friendly?
5. Run the application that you're working with on a daily basis. Measure its memory usage, memory footprint and analyze heap allocations using memory profilers that we discussed in [@sec:MemoryProfiling]. Use a general profiler like Intel VTune or Linux perf to identify hot memory accesses. Is the application cache-friendly? Is there a way to improve it?