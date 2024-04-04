# Selection Sort

Selection sort is a sorting algorithm that is inefficient on large lists and generally performs worse than the similar insertion sort. 
There are performance advantages over more complicated algorithms in certain situations, particularly where auxiliary memory is limited.

![Selection Sort](./selection-600.gif)

It is **NOT** stable because earlier elements can jump after an element of the same value during a swap
It is **in-place** because the only additional memory needed is for storing the index to the minimum element

## Complexity

| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Selection sort**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |           |

## References

[Wikipedia](https://en.wikipedia.org/wiki/Selection_sort)
