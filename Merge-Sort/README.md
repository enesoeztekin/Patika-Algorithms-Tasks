## Task 2 (Merge Sort) Solution:

- Question 1: **[16,21,11,8,12,22]**
    - Find the solution steps of the array given above.
      - Solution: 
      
        Step 1: [16,21,11] [8,12,22]
        
        Step 2: [16] [21,11] [8,12] [22]
        
        Step 3: [16] [21] [11] [8] [12] [22]
        
        Step 4: [16,21] [11] [8,12] [22]
        
        Step 5: [11,16,21] [8,12,22]
        
        Step 6: [8,11,12,16,21,22]
        
    - Find the Big-O notation.
      - Solution: O(nlogn) -> That's because the number of operations halving by dividing the array by 2 in each iteration of the loop. 
