# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1.Start the program.

2.Define a function that takes a string as input.

3.If the string is empty or has only one character, return it as it is.

4.Otherwise, take the last character of the string.

5.Call the same function with the rest of the string (excluding the last character).

6.Add the last character to the result of the recursive call.

7.Return the final reversed string.

8.Get input from the user.

9.Call the function with the user's input.

10.Print the reversed string.

11.End the program. 

## Program:
```
/*
Program to implement Reverse a String
Developed by: F.Keziah
Register Number:  212223040094
*/
```
```

def rev(s):
    if(len(s)<1):
        return s
    return s[-1]+rev(s[:-1])
s=input()
print(rev(s))

```
## Output:
![image](https://github.com/user-attachments/assets/6c1d5052-0179-46b2-b869-30d9854a3b30)



## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
