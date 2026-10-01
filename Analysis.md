# Analysis

## Input

```text
324, 125, 456, 218, 102, 389, 275, 147
```

## Merge Sort

The supplied program uses an iterative bottom-up Merge Sort.

* Number of merge passes: **3**
* Comparisons recorded by the program: **17**
* Best-case time complexity: **O(n log n)**
* Average-case time complexity: **O(n log n)**
* Worst-case time complexity: **O(n log n)**
* Additional space: **O(n)** because a temporary array is used during merging.

### Merge Passes

```text
Pass 1: 125 324 218 456 102 389 147 275
Pass 2: 125 218 324 456 102 147 275 389
Pass 3: 102 125 147 218 275 324 389 456
```

## Quick Sort

The supplied program selects the first element as the pivot for each partition.

* Number of partitions: **6**
* Comparisons recorded by the program: **27**
* Best-case time complexity: **O(n log n)**
* Average-case time complexity: **O(n log n)**
* Worst-case time complexity: **O(n²)**
* Additional space: **O(log n)** average recursion stack and **O(n)** worst-case recursion stack.

### Partition Results

The program records each pivot and the array after that partition. The complete results are available in [`Output.md`](Output.md).

## Execution Summary

|Feature|Merge Sort|Quick Sort|
|-|-|-|
|Passes / Partitions|3 passes|6 partitions|
|Comparisons|17|27|
|Best Time|O(n log n)|O(n log n)|
|Average Time|O(n log n)|O(n log n)|
|Worst Time|O(n log n)|O(n²)|
|Additional Space|O(n)|O(log n) average, O(n) worst case|

## Important Note

The question says to record the array after each **digit position** for Merge Sort. However, the supplied C program is an **iterative bottom-up Merge Sort** and records the array after each **merge pass**. This repository documents the behavior of the supplied program rather than changing its algorithm.

