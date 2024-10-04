# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 06-09-2024                                                                           
### REGISTER NUMBER : 212221040111

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

### iii)Switch

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

### iv) if..else

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

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```
### Output:

### do..while

![ex1-a](https://github.com/user-attachments/assets/7bee82e9-2148-4cf4-9d22-b07a32dca5cb)

### while..do

![ex1-b](https://github.com/user-attachments/assets/6b854d98-6d73-4262-a8eb-fbea4990f473)

### switch

![ex1-c](https://github.com/user-attachments/assets/a75e44f3-d6dc-4bc4-b282-5e1365caf758)


### if..else

![ex1-d](https://github.com/user-attachments/assets/0f4edf62-91b0-428c-b405-c3976c84903e)

### for

![ex1-e](https://github.com/user-attachments/assets/45720ff2-f8d3-4e2e-b63d-12ac3133b959)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


