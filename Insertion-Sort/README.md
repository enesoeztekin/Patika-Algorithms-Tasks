# Task 1 (Insertion Sort) Solution:

Question 1: **[22,27,16,2,18,6]**
  - Find the solution steps of the array given above.
    - Solution:
      
      Step 1: [**22**,27,16,2,18,6]
      
      Step 2: [**2**,27,16,**22**,18,6]
      
      Step 3: [2,**6**,16,22,18,**27**]
      
      Step 4: [2,6,**16**,22,18,27]
      
      Step 5: [2,6,16,**18**,**22**,27]
      
      Sorted: [**2**,**6**,**16**,**18**,**22**,**27**]
      
  - Find the Big-O notation.
    - Solution:
      O(n<sup>2</sup>)
  - Find the time complexity for each case.
    - Solution:
      
      Best case: O(1) -> The array is already sorted.
      
      Worst case: O(n<sup>2</sup>) -> The array is sorted in reverse. I.e. [22,27,16,2,18,6]
  - Which case includes the number 18 in this array after the array is sorted?
    - Solution: When the array is sorted, the number 18 is in the middle of the array. Therefore, we could say it'd be in the average case.
 
