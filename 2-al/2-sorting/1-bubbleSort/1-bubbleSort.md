# Bubble Sort

__Sorting Algorithms__ are concepts that every competitive programmer must know.

Sorting algorithms can be used for collections of numbers, string, characters, or a structure of any of these types.

Bubble sort is based on the idea of __repeatedly__ comparing `pairs of adjacent elements` and then swapping their positions if they exist in the wrong order.

Assume that A[] is an unsorted array of _n_ elements. This array needs to be sorted in ascending order. The pseudo code is as follows:

```c++
void bubble_sort( int A[], int n ) {
    int temp;
    for (int k = 0; k < n-1; k++) {
        // (n-k-1) is for ignoring comparisons of elements which have already been compared in earlier iterations
        for (int i = 0; i < n-k-1; i++) {
            if (A[i] > A[i+1]) {
                // here swapping of positions is being done
                temp = A[i];
                A[i] = A[i+1];
                A[i+1] = temp;
            }
        }
    }
}
```

Lets try to understand the pseudo code with an example: A[] = {7, 4, 5, 2}

## Complexity

The complexity of `bubble sort` is $O(n^2)$ in both worst and average cases, because the entire array needs to be iterated for every element.