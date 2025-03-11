# Bubble Sort

Bubble sort psuedocode:

START
FUNCTION bubbleSort(array)
   n = LENGTH(array)
   FOR i FROM 0 TO n-1 DO
       swapped = FALSE
   FOR j FROM 0 TO n-i-2 DO
       IF array[j] > array[j+1] THEN
       TEMP = array[j]
       array[j] = array[j+1]
       array[j+1] = TEMP
       swapped = TRUE
       END IF
       END FOR
       IF NOT swapped THEN
      BREAK
      END IF
    END FOR
END FUNCTION

