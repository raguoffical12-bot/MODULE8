
### Aim: To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them 
         in a list and find the score of the runner-up.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```
reg no:212223070021
name:Ragunandhan S
scores = list(map(int, input().split()))
scores.sort()
runner_up = scores[-2]
print(runner_up)


### Output:
 ![image](https://github.com/user-attachments/assets/4ae98a86-c951-4b7b-b6b7-22dde3330c09)


### Result: Thus, the given program is implemented and executed successfully .
 
