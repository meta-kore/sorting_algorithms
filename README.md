# sorting_algorithms

Eleven sorting algorithms in C, each printing the array after every step so the algorithm can be watched working.

| Algorithm | File | Sorts |
|---|---|---|
| Bubble sort | `0-bubble_sort.c` | array |
| Insertion sort | `1-insertion_sort_list.c` | doubly linked list |
| Selection sort | `2-selection_sort.c` | array |
| Quick sort | `3-quick_sort.c` | array |
| Shell sort | `100-shell_sort.c` | array |
| Cocktail shaker sort | `101-cocktail_sort_list.c` | doubly linked list |
| Counting sort | `102-counting_sort.c` | array |
| Merge sort | `103-merge_sort.c` | array |
| Heap sort | `104-heap_sort.c` | array |
| Radix sort | `105-radix_sort.c` | array |
| Bitonic sort | `106-bitonic_sort.c` | array |

The numbered `*-O` files hold the best, average and worst-case time complexity for each algorithm.

## Build

Every function is declared in `sort.h`. Write a `main` that fills an array, calls the sort you want and prints the result, then compile:

```sh
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -c 0-bubble_sort.c
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 your_main.c 0-bubble_sort.c -o sort
```

`print_array` and `print_list` are provided by the project harness and are not in this repository, so add your own or use the ones from the course scaffolding.

## Notes

Built as a project for ALX Africa Software Engineering.
