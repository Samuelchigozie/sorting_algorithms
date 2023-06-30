# C - Sorting Algorithms & Big O

This repository contains implementations of various sorting algorithms in C. The sorting algorithms included are:

## Sorting Algorithms

* Bubble Sort (`0-bubble_sort.c`)
* Insertion Sort (`1-insertion_sort_list.c`)
* Selection Sort (`2-selection_sort.c`)
* Quick Sort (`3-quick_sort.c`)
* Shell Sort - Knuth Sequence (`100-shell_sort.c`)
* Cocktail Shaker Sort (`101-cocktail_sort_list.c`)
* Counting Sort (`102-counting_sort.c`)
* Merge Sort (`103-merge_sort.c`)
* Heap Sort (`104-heap_sort.c`)
* Radix Sort (`105-radix_sort.c`)
* Bitonic Sort (`106-bitonic_sort.c`)
* Quick Sort - Hoare Partition Scheme (`107-quick_sort_hoare.c`)

Each algorithm is implemented in a separate C file.

## Test Files

The `tests` folder contains test files to verify the correctness of the sorting algorithms.

## Helper Files

* `print_array.c`: A C function that prints an array of integers.
* `print_list.c`: A C function that prints a doubly-linked list of integers (`listint_t`).

## Header Files

* `sort.h`: Contains definitions and function prototypes for the sorting algorithms.

## Data Structures

The repository also includes additional files related to a task called `1000-sort_deck.c`. It involves sorting a deck of cards.

* `deck.h`: Contains definitions and function prototypes for the card deck data structure.
* `deck_node_t`: Structure representing a node in the doubly-linked list.
* `card_t`: Structure representing a card in the deck.
* `sort_deck`: Function that sorts a doubly-linked list deck of cards.

## Complexity Analysis

Each sorting algorithm has an associated file (`*-O`) that provides the best, average, and worst-case time complexities of the algorithm.

## Tasks

The repository also includes separate files for each task related to the sorting algorithms. Each task has its own implementation file and an associated text file describing the time complexities of the algorithm.

Please refer to the respective files for more details about each algorithm and task.

Note: This README provides a brief overview of the repository. For detailed information about the implementation of each algorithm, please refer to the individual files and comments within them.