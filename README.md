# STEP Week 04: Array Algorithms

My solutions to the Week 4 practice problems and coding assignment of the **STEP Java Programming** track.

## Topics covered

- Hash-based pair search
- Single-pass greedy scans
- Two pointers
- Array rotation
- Prefix and suffix products
- Kadane's algorithm
- Binary search on a rotated array

## Practice

| Program | What it does | Input |
|---------|--------------|-------|
| [`BestTimeToBuySellStock`](Practice/BestTimeToBuySellStock.java) | Finds the maximum profit from a single buy and sell | Built-in example |
| [`ContainsDuplicate`](Practice/ContainsDuplicate.java) | Checks whether any value appears more than once | Built-in example |
| [`MergeTwoSortedArrays`](Practice/MergeTwoSortedArrays.java) | Merges two sorted arrays into one sorted array | Built-in example |
| [`RotateArray`](Practice/RotateArray.java) | Rotates an array to the right by k steps | Built-in example |
| [`TwoSum`](Practice/TwoSum.java) | Finds the indices of the two numbers that add up to a target | Built-in example |

## Assignment

| Program | What it does | Input |
|---------|--------------|-------|
| [`FindMinimumRotatedSortedArray`](Assignment/FindMinimumRotatedSortedArray.java) | Finds the minimum of a rotated sorted array with binary search | Built-in example |
| [`MaximumSubarray`](Assignment/MaximumSubarray.java) | Finds the largest sum of a contiguous subarray (Kadane's algorithm) | Built-in example |
| [`ProductOfArrayExceptSelf`](Assignment/ProductOfArrayExceptSelf.java) | Computes the product of all other elements for each position, without division | Built-in example |
| [`SubarraySumEqualsK`](Assignment/SubarraySumEqualsK.java) | Counts the subarrays whose sum equals k | Built-in example |
| [`ThreeSum`](Assignment/ThreeSum.java) | Finds all unique triplets that add up to zero | Built-in example |

## Project structure

```
.
├── Practice/
│   ├── BestTimeToBuySellStock.java
│   ├── ContainsDuplicate.java
│   ├── MergeTwoSortedArrays.java
│   ├── RotateArray.java
│   ├── TwoSum.java
│   └── README.md
├── Assignment/
│   ├── FindMinimumRotatedSortedArray.java
│   ├── MaximumSubarray.java
│   ├── ProductOfArrayExceptSelf.java
│   ├── SubarraySumEqualsK.java
│   ├── ThreeSum.java
│   └── README.md
└── README.md
```

## How to run

You need JDK 8 or later.

```bash
cd Practice      # or: cd Assignment
javac FileName.java
java FileName
```

Replace `FileName` with the program name. Programs marked **Interactive** read input from the terminal; the rest run a built-in example straight away. Each file is self-contained, so you can also open it in VS Code or IntelliJ and press **Run**.

## Author

**Aditya Shukla** · [@adityashukla44](https://github.com/adityashukla44)
