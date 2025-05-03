# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE: 03-05-2025                                                                            
### REGISTER NUMBER : 212224230015
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
 def is_palindrome(s):
    s = s.lower().replace(" ", "")
    return s == s[::-1]

string = input("Enter a string: ")
if is_palindrome(string):
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

```












### Output:
![image](https://github.com/user-attachments/assets/82cb4f31-e9c5-4f9e-a274-f3abf4ee45e5)





### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
