# Ex.No: 7 Sorting.

### DATE: 24/09/2024                                                                          
### REGISTER NUMBER :  212221040119
### AIM: 
Write a python program for sorting and inspect for failures.

### Algorithm:
```
1.start the program.
2.Get the number of elements from user.
3.Get the elements to be sorted.
4.Traverse the array and sort the element one by one.
5.print the sorted array.
6.Stop the program.
```

### Program:
```
n=int(input("Enter the number of elements:"))
arr=[]
try:
for i in range(n):
a=float(input("Enter the element:"))
arr.append(a)
for i in range(n):
for j in range(n):
if(arr[i]<arr[j):
temp = arr[i]
arr[i] = arr[j]
arr[j] = temp
print(“The array after sorting: ”)
for i in range(n):
print(arr[i],end=’ ’)
except ValueError:
print(“Enter a valid number”)
```

### Output:
![ex77](https://github.com/user-attachments/assets/39e4c781-e922-4c3c-9f6e-07609bd9d074)

### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully
