PsuedoCode for Selection Sort:
START
SelectionSort(arr,n)
    n = length(arr)
    for i from 0 to n-1 do
        minIndex = i
        for j from i+1 to n-1 do
            if arr[j] < arr[minIndex] then
              minIndex = j
            swap arr[i] with arr[minIndex]
     return Arr
END

