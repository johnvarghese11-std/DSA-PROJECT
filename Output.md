## Execution Output

```text
====================================
       SORTING ALGORITHM ANALYSIS
====================================

Original Array:
324 125 456 218 102 389 275 147 

========== MERGE SORT ==========
Pass 1: 125 324 218 456 102 389 147 275 
Pass 2: 125 218 324 456 102 147 275 389 
Pass 3: 102 125 147 218 275 324 389 456 

Final Sorted Array:
102 125 147 218 275 324 389 456 
Number of comparisons = 17

========== QUICK SORT ==========
First element is selected as pivot.

Partition 1
Pivot = 324
Array after partition: 275 125 147 218 102 324 389 456 

Partition 2
Pivot = 275
Array after partition: 102 125 147 218 275 324 389 456 

Partition 3
Pivot = 102
Array after partition: 102 125 147 218 275 324 389 456 

Partition 4
Pivot = 125
Array after partition: 102 125 147 218 275 324 389 456 

Partition 5
Pivot = 147
Array after partition: 102 125 147 218 275 324 389 456 

Partition 6
Pivot = 389
Array after partition: 102 125 147 218 275 324 389 456 

Final Sorted Array:
102 125 147 218 275 324 389 456 
Number of comparisons = 27

====================================
             PROGRAM END
====================================
```

## Final Sorted Sequence

```text
102 125 147 218 275 324 389 456
```

## Recorded Results

|Method|Passes / Partitions|Comparisons|
|-|-:|-:|
|Merge Sort|3 passes|17|
|Quick Sort|6 partitions|27|



