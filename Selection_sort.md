# Selection Sort

Selection sort psuedocode

```
# Write the psuedocode 
START
Input an array of elements
SelectionSort(array, n)
    for i from 0 to n-1
        min_index = i
        for j from i+1 to n-1
            if array[j] < array[min_index]
                min_index = j
        if min_index ≠ i
            SWAP(array[i], array[min_index])
    return array
END
```
