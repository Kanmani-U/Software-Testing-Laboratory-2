# Ex.No: 13  Pytest program for Sum of digits

### DATE:15/04/2024                                                                        
### REGISTER NUMBER : 212221040119
### AIM: To write a python program for Fibonacci Series and generate test cases using Pytest. 

### Algorithm:
```
Step 1: Write the python program for sum of digits of a number. 
Step 2: Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
Step 3: Write some test cases for to be tested and save it as “test_sumofdig.py”. 
Step 4: Open command prompt and change the directory to where pytest and program is 
saved and type “pytest test_sumofdig.py” and run it. 
Step 5: Stop the program.
```

### Program:
```
def fibR(n): 
  if n==1 or n==2: 
    return 1 
  return fibR(n-1)+fibR(n-2)

def test_fib_1_equals_1(): 
  assert fibR(1) == 1

def test_fib_2_equals_1(): 
  assert fibR(2) == 1

def test_fib_6_equals_8(): 
assert fibR(6) == 7
```
### Output:
![las](https://github.com/user-attachments/assets/fe7b7840-b902-485d-bf94-26e11bec2082)



### Result:
Thus, the python program for Fibonacci Series is tested using pytest and executed and output is verified successfully.


