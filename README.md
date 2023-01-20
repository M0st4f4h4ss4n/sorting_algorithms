# C - Sorting Algorithms & Big O

This is a project on sorting algorithms implemented in C language, along with their corresponding time complexity (big O notation).

## Table of Contents
- [Sorting Algorithms](#sorting-algorithms)
- [Time Complexity](#time-complexity)
- [Files](#files)
- [Compilation](#compilation)

## Sorting Algorithms
- Bubble sort
- insertion sort
- selection sort
- quick sort
- shell sort
- cocktail sort
- counting sort
- merge sort
- heap sort
- radix sort
- bitonic sort
- quick sort hoare

## Time Complexity

| Algorithm     | Best Case | Average Case | Worst Case |
|----------------|------------|---------------|------------|
| bubble sort    | O(n)       | O(n^2)        | O(n^2)     |
| insertion sort | O(n)       | O(n^2)        | O(n^2)     |
| selection sort | O(n^2)     | O(n^2)        | O(n^2)     |
| quick sort     | O(n log n) | O(n log n)    | O(n^2)     |
| shell sort     | O(n log^2n)| O(n log^2n)   | O(n log^2n)|
| cocktail sort  | O(n)       | O(n^2)        | O(n^2)     |
| counting sort  | O(k+n)     | O(k+n)        | Ok+n)     |
| merge sort     | O(n log n) | O(n log n)    | O(n log n) |
| heap sort      | O(n log n) | O(n log n)    | O(n log n) |
| radix sort     | O(nk)      | O(nk)         | O(nk)      |
| bitonic sort   | O(n log^2n)| O(n log^2n)   | O(n log^2n)|
| quick sort hoare| O(n log n) | O(n log n)    | O(n^2)     |

## Files
- `sort.h` : header file which contains all the function prototypes
- `0-bubble_sort.c`, `0-O` : a function that sorts an array of integers in ascending order using the bubble sort algorithm
- `1-insertion_sort_list.c`, `1-O` : a function that sorts a doubly linked list of integers in ascending order using the insertion sort algorithm
- `2-selection_sort.c`, `2-O` : a function that sorts an array of integers in ascending order using the selection sort algorithm
- `3-quick_sort.c`, `3-O` : a function that sorts an array of integers in ascending order using the quick sort algorithm
- `100-shell_sort.c` : a function that sorts an array of integers in ascending order using the shell sort algorithm, using the Knuth sequence
- `101-cocktail_sort_list.c`, `101-O` : a function that sorts a doubly linked list of integers in ascending order using the cocktail shaker sort algorithm
- `102-counting_sort.c`, `102-O` : a function that sorts an array of integers in ascending order using the counting sort algorithm
- `103-merge_sort.c`, `103-O` : a function that sorts an array of integers in ascending order using the merge sort algorithm
- `104-heap_sort.c`, `104-O` : a function that sorts an array of integers in ascending order using the heap sort algorithm
- `105-radix_sort.c`, `105-O` : a function that sorts an array of integers in ascending order using the radix sort algorithm
- `106-bitonic_sort.c`, `106-O` : a function that sorts an array of integers in ascending order using the bitonic sort algorithm
- `107-quick_sort_hoare.c`, `107-O` : a function that sorts an array of integers in ascending order using the quick sort hoare algorithm
- `deck.h` : header file for the card deck structure
- `deck` : a directory containing the card deck files
- `print_array.c` : a function that prints an array of integers
- `print_list.c` : a function that prints a doubly linked list of integers

## Compilation
All the files should be compiled with `gcc -Wall -Wextra -Werror -pedantic -std=c89`.
