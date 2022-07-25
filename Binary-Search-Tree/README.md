## Task 3 (Binary Search Tree) Solution: 

- Question 1: Create the binary tree of the array **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**
  - Solution: We should take the number 7 as the root of the binary search tree. Then, as we go through the elements of the array, we should put the numbers less than the root to the left side of the root, and we should put the numbers more than the root to the right side of the root.
  
  Step 1: **[5]**
    ```
           7
          /
         5
    ```
  Step 2: **[1]**
    ```
           7
          /
         5
        /
       1
    ```
  Step 3: **[8]**
    ```
           7
          / \
         5   8
        /
       1
    ```
  Step 4: **[3]**
    ```
           7
          / \
         5   8
        /
       1
        \
         3
    ```
   Step 5: **[6]**
  ```
             7
            / \
           5   8
          / \
         1   6
          \
           3
  ```
   Step 6: **[0]**
  ```
             7
            / \
           5   8
          / \
         1   6
        / \
       0   3
  ```
   Step 7: **[9]**
  ```
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
  ```
  Step 8: **[4]**
  ```
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
            \
             4
  ```
  Step 9: **[2]**
  ```
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
          / \
         2   4
  ```
    
