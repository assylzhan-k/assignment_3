# Sorting and Searching Algorithm Analysis System

**Name:** [Assylzhan Kishibayeva]
**Group:** [SE_2512]

---

## Project Overview

This project compares different sorting and searching algorithms in Java. The goal is to see how fast they work and how performance changes with different array sizes and data types.

Algorithms used:
* Bubble Sort
* Quick Sort
* Binary Search

---

## Algorithm Description

**Bubble Sort**
Bubble Sort compares neighboring elements and swaps them if needed. It is simple but slow for large arrays.

**Quick Sort**
Quick Sort splits the array into parts using a pivot and sorts them. It is much faster than Bubble Sort for large data.

**Binary Search**
Binary Search finds an element by repeatedly dividing the array in half. It only works on sorted arrays and is very fast.

---

## Results

I tested the algorithms on:

* Small arrays (10 elements)
* Medium arrays (100 elements)
* Large arrays (1000 elements)

I used random arrays and sorted arrays

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 20 42" src="https://github.com/user-attachments/assets/7ee03c58-fe2c-4368-92ee-4dd53374ae29" />

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 22 25" src="https://github.com/user-attachments/assets/6a31dad0-f158-4ee9-ab98-31a8eb854b79" />

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 22 28" src="https://github.com/user-attachments/assets/8080461d-2e88-42d9-8eb7-0ff131e71db6" />

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 22 37" src="https://github.com/user-attachments/assets/788dccbc-2acf-4a72-a9cf-3d944be3c81b" />

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 24 48" src="https://github.com/user-attachments/assets/be710b31-b529-4a73-8c2a-c2eb4a37c434" />

<img width="1470" height="956" alt="Screenshot 2026-04-30 at 06 25 08" src="https://github.com/user-attachments/assets/8c3560db-43f7-494d-8b60-7224d735d098" />


---

## Analysis

**Which sorting algorithm was faster?**
Quick sort was faster, especially for large arrays, because it uses a more efficient method.

**How does performance change with input size?**
As the size increases, bubble sort becomes much slower, while quick sort increases slowly.

**Sorted vs unsorted data?**
Bubble sort works faster on sorted arrays because fewer swaps are needed and quick sort is less affected.

**Do results match Big-O?**
Yes, bubble sort is slow (O(n²)) and quick sort is faster (O(n log n)).

**Which searching algorithm is more efficient?**
Binary search is very efficient because it reduces the search space quickly.

---

## Reflection

In this project, I learned how different algorithms behave in real situations and I saw that faster algorithms make a big difference when the data is large. This assignment helped me understand the importance of time complexity and clean code.
