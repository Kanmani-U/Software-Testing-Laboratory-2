# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 06-09-2024                                                                          
### REGISTER NUMBER : 212221040119

### AIM:   
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### i)do..while
```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display()
```
### ii) while..do
```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")
```
### Switch
```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch()
```
###  if..else
```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”)
```
### v) for
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
### Output:
### do..while
 ![image](https://github.com/user-attachments/assets/c2229a2c-12ab-4814-8be4-1d63f1dcafbb)
### while..do
 ![image](https://github.com/user-attachments/assets/565fdd1f-1246-4081-9273-f6425145de1b)
### switch
 ![image](https://github.com/user-attachments/assets/5c183abb-3039-4652-b1b6-57b4fa8fffa9)
### if..else
 ![image](https://github.com/user-attachments/assets/fc5e32c5-5a39-45cc-acbb-895372422a59)
### for
 ![image](https://github.com/user-attachments/assets/7bb0f593-68ae-4641-abcb-6d5284a513c1)
 
### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


