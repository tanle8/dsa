# Binary Search
(2/3)

__Binary search__ is the most popular search algorithm. It is efficient and also onr of the most commonly used techniques that is used to solve problems.

If all the names in the world are written down together in order and you want to search for the position of a specific name, binary search will accomplish this in a maximum of __35__ iterations.

__Binary search works only on a sorted set of elements__. To use binary search on a collection, the collection must first be sorted.

When binary search is used to perform operations on a sorted set, the number of iterations can always be reduced on the basis of the value that is being searched.

Let's us consider the following array:

![]()

By using linear search, the position of element 8 will be determined in the __9__th iteration.

## Implementation

## Time complexity

As we dispose off one part of the search case during every step of binary search, and perform the search operation on the other half, this results in a worst case time complexity of O(log_2(N)).