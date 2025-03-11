PseudoCode For InsertionSort:
START
    InsertionSort(array, n)
        for i from 1 to n - 1 do
            key ← array[i]
            j ← i - 1            
            while j ≥ 0 and array[j] > key do
                array[j + 1] ← array[j]
                j ← j - 1
            end while            
            array[j + 1] ← key
        end for
END
