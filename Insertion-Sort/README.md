# Task 1 (Insertion Sort) Solution:

Question 1: **[22,27,16,2,18,6]**
  - Find the solution steps of the array given above.
    - Solution:
      
      Step 1: [**22**|,27,16,2,18,6]
      
      Step 2: [**22**,27|,16,2,18,6]
      
      Step 3: [**16**,22,27|,2,18,6]
      
      Step 4: [**2**,16,22,27|,18,6]
      
      Step 5: [2,16,**18**,22,27|,6]
      
      Step 6: [2,**6**,16,18,22,27|]
      
      Sorted: [**2**,**6**,**16**,**18**,**22**,**27**]
      
  - Find the Big-O notation.
    - Solution:
      O(n<sup>2</sup>)
  - Find the time complexity for each case.
    - Solution:
      
      Best case: O(n) -> The array is already sorted.
      
      Worst case: O(n<sup>2</sup>)
      
      Average case: O(n<sup>2</sup>) 
  - Which case includes the number 18 in this array after the array is sorted?
    - Solution: When the array is sorted, the number 18 is in the middle of the array. Therefore, we could say it'd be in the average case.
 
Question 2: Find the first 4 solution steps of the array **[7,3,5,8,2,9,4,15,6]**.
 - Solution: 
    
    Step 1: [**7**|,3,5,8,2,9,4,15,6]
    
    Step 2: [**3**,7|,5,8,2,9,4,15,6]
    
    Step 3: [3,**5**,7|,8,2,9,4,15,6]
    
    Step 4: [3,5,7,**8**|,2,9,4,15,6]
      
      .

      .

      .
    
