# EX 1D Linear search
## DATE:4/3/25
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1.Input the number of elements: Ask the user to enter how many numbers they want to store in a tuple. Store this value in variable n.

2.Initialize an empty tuple: Create an empty tuple named Tuple.

3.Read n integer inputs: Use a loop that runs n times to take integer input from the user. Each input value is added to the tuple using tuple concatenation (Tuple += (value,)).

4.Input the search key: Ask the user to enter the number they want to search for. Store it in a variable x.

5.Define the search function: Create a function called search that takes two arguments:

tup: the tuple of elements

key: the value to be searched

6.Search through the tuple: Inside the function, use a loop to go through each element i in the tuple.

7.If the key is found: If any element in the tuple matches the key, print "key Found" and stop the loop using break.

8.If the loop completes without finding the key: If the loop ends normally (no match found), print "key Not Found" using the else clause of the loop.
## Program:
```
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: Keziah.F
Register Number:  212223040094
*/
```

## Output:

![image](https://github.com/user-attachments/assets/77faef37-a92f-4673-9ba4-b8b5fb57090f)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
