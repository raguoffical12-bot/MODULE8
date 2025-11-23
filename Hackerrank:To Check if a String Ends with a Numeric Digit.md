EX: 8.e check whether they are valid mobile numbers.

### Aim: Write a Python program to check whether the given mobile numbers are valid or not.
A valid mobile number is a 10-digit number starting with 7, 8, or 9.

---

### Algorithm:

1. **Start**
2. Read the number of test cases $t$.
3. For each test case, do the following:

   * Read the mobile number as a string.
   * Define a regular expression pattern to match:

     * Start of the string `^`
     * First digit is either 7, 8, or 9: `[789]`
     * Followed by exactly 9 digits: `\d{9}`
     * End of the string `$`
   * Use the regex to check if the mobile number matches the pattern.
   * If it matches, print "YES".
   * Otherwise, print "NO".
4. **End**

---

### Program:
reg no:212223070021
name:Ragunandhan S
import re
num=int(input())
for i in range(num):
    n=input()
    p=re.compile("[7|8|9]\d{9}")
    if re.match(p,n):
        print("YES")
    else:
        print("NO")

### Output:
![image](https://github.com/user-attachments/assets/8429d2c4-7739-488d-9013-80a05754ebb4)


### Result: Thus, the given program is implemented and executed successfully .
 


