# Sorting Algorithm Analysis

A C programming assignment implementing and analysing **Merge Sort** and **Quick Sort** using a fixed set of social-media IDs.

## Input

```text
324, 125, 456, 218, 102, 389, 275, 147
```

## Algorithms

### Merge Sort
The program uses an iterative bottom-up Merge Sort and records the array after each merge pass.

### Quick Sort
The program uses Quick Sort with the **first element selected as the pivot** and records the important partition results.

## Repository Contents

| File | Description |
|---|---|
| [Question.md](Question.md) | Assignment question |
| [Input.md](Input.md) | Input data and setup |
| [sorting.c](sorting.c) | C source code |
| [Output.md](Output.md) | Actual program execution output |
| [Analysis.md](Analysis.md) | Complexity and execution analysis |

## Final Sorted Sequence

```text
102 125 147 218 275 324 389 456
```

## Program Results

| Algorithm | Passes / Partitions | Comparisons |
|---|---:|---:|
| Merge Sort | 3 | 17 |
| Quick Sort | 6 | 27 |

## Running the Program

### GCC

```bash
gcc sorting.c -o sorting
./sorting
```

### Windows

```bash
gcc sorting.c -o sorting.exe
sorting.exe
```

## Note

The assignment wording refers to processing by digit position for Merge Sort, but the supplied implementation is a bottom-up Merge Sort that displays results after merge passes. The repository preserves the behavior of the supplied code.
