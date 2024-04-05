# Binary Search

Binary search is an array search algorithm that compares the target value to the middle element of the array; 
if they are unequal, the half in which the target cannot lie is eliminated and the search continues on the remaining half until it is successful. 
If the search ends with the remaining half being empty, the target is not in the array.

Including an equality comparison in the while loop can catch a potential edge case of a one-element array.

![Binary Search](./Binary-search-work.gif)

## Complexity

**Time Complexity**: `O(log(n))`

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Binary_search_algorithm)
