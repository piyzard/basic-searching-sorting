 Insertion Sort

 Insertion sort psuedocode

```
# Write the psuedocode 
START
Input an array of elements
insertion_sort(array,n):
  for i in range(1,n):
    key = array[i]
    j=i-1
    while j>=0 and array[j]>key
      array[j+1]=array[j]
      j=j-1
    array[j+1]=key
retyrn array
END
```
