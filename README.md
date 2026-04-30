# Sorting and Searching Algorithm Analysis System

Name: [Assylzhan Kishibayeva]
Group: [SE-2512]

Algorithms used:

* Bubble Sort
* Quick Sort
* Binary Search

---
Algorithm Description
Bubble Sort
Bubble Sort compares neighboring elements and swaps them if needed.
It is simple but slow for large arrays.
Quick Sort
Quick Sort splits the array into parts using a pivot and sorts them.
It is much faster than Bubble Sort for large data.
Binary Search
Binary Search finds an element by repeatedly dividing the array in half.
It only works on sorted arrays and is very fast.

## Results

I tested the algorithms on:

* Small arrays (10 elements)
* Medium arrays (100 elements)
* Large arrays (1000 elements)

I used:

* Random arrays
* Sorted arrays


---

## Analysis

**Which sorting algorithm was faster? Why?**
Quick Sort was faster, especially for large arrays, because it uses a more efficient method (divide and conquer).

**How does performance change with input size?**
As the size increases, Bubble Sort becomes much slower, while Quick Sort increases slowly.

**Sorted vs unsorted data?**
Bubble Sort works faster on sorted arrays because fewer swaps are needed.
Quick Sort is less affected.

**Do results match Big-O?**
Yes, Bubble Sort is slow (O(n²)) and Quick Sort is faster (O(n log n)).

**Which searching algorithm is more efficient?**
Binary Search is very efficient because it reduces the search space quickly.

**Why does Binary Search need a sorted array?**
Because it divides the array into halves. Without sorting, it cannot decide where to search.

---

## Reflection

In this project, I learned how different algorithms behave in real situations.
I saw that faster algorithms make a big difference when the data is large.
It also helped me understand the importance of time complexity and clean code.

