# Ex.No: 5 check the given number is array through binary search and inspect for failures.
### DATE: 27-09-2024
### REGISTER NUMBER : 212221040119
### AIM: 
Write a python program for binary search and inspect for failures.

### Algorithm:

1. Input: A sorted list arr and a target element to search for.
2. Initialize:
3. Set left to the start index (0).
4. Set right to the end index (len(arr) - 1).
5. Loop while left is less than or equal to right:
6. Calculate the midpoint mid as (left + right) // 2.
7. If arr[mid] equals target, return the index mid.
8. If arr[mid] is less than target, set left to mid + 1.
9. If arr[mid] is greater than target, set right to mid - 1.
10. Return "not found" if the target is not in the list.

### Program:
```
def binary_search(arr, x):
    low = 0
    high = len(arr) - 1
    mid = 0
    
    while low <= high:
        mid = (high + low) // 2
        
        if arr[mid] < x:
            low = mid + 1
        elif arr[mid] > x:
            high = mid - 1
        else:
            return mid
    
    return -1

arr = [2, 3, 4, 10, 40]
x = input("Enter the element to be searched: ")

try:
    x = int(x)
    result = binary_search(arr, x)
    if result != -1:
        print("Element is present at index", str(result))
    else:
        print("Element is not present in array")
except:
    print("Enter a valid input!")
```
### Output:
![image](https://github.com/user-attachments/assets/e784bd03-2d42-435e-8832-cb53721c498e)

### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

