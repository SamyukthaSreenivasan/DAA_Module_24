# EX 6D BRUTE FORCE ALGORITHM
## DATE: 25.5.2025
## AIM:
To write a python program using brute force method of searching for the given substring in the main string.

## Algorithm
1.Take two inputs: the main string and the substring to search for.
2.Create a regex pattern using the substring.
3.Search for the first match of the pattern in the main string.
4.If a match is found.Print the starting index of the match.
5.Continue searching for the next match, starting just after the current match.
6.Repeat step 4 until no more matches are found. 

## Program:
```
/*
To implement the program using brute force method of searching for the given substring in the main string.
Developed by: Samyuktha S 
Register Number: 212222240089 
*/
```
```
import re
def match(string,sub):
    pattern = re.compile(str2)
    r = pattern.search(str1)
    while r:
        print("Found at index {}".format(r.start()))
        r = pattern.search(str1,r.start()+1)    

str1=input()
str2=input()
```
## Output:
![image](https://github.com/user-attachments/assets/13452a03-f96a-42ed-84eb-c69820158710)

## Result:
Thus the above program was executed successfully for searching the substring at respective index.
