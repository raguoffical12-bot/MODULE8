EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
reg no:212223070021
name:Ragunandhan S 
start = int(input("Enter the starting range: "))
end = int(input("Enter the ending range: "))

lst = [i for i in range(start, end+1)]

result = [x**2 if x % 2 == 0 else x**3 for x in lst]

print(result)



```
### Output:
![image](https://github.com/user-attachments/assets/ddbd36e3-8f55-4166-8f95-1d1f53d2a86a)

### Result: Thus, the given program is implemented and executed successfully .
