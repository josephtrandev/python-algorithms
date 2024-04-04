# Insertion Sort

Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item at a time. 
It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

![Insertion Sort](./insertion-600.gif)

It is **stable** because later elements will not swap with earlier elements unless the later element is smaller
It is **in-place** because no additional data structures are used to store intermediate values

## Complexity

| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Insertion sort**    | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |

## References

[Wikipedia](https://en.wikipedia.org/wiki/Insertion_sort)
