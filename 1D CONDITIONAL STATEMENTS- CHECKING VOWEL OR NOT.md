## Experiment No: 1d – Conditional Statements- Write a python program to find the smallest among three Integer  Numbers

## AIM  
The aim of this program is to determine the smallest integer among three given numbers.
## ALGORITHM  
1.Define a function find_smallest that takes three parameters (num1, num2, num3).
2.Initialize a variable smallest with the value of num1 (assuming num1 is the smallest initially).
3.Check if num2 is smaller than smallest. If so, update smallest to num2.
4.Check if num3 is smaller than smallest. If so, update smallest to num3.
5.Return the variable smallest.
6.Use the function with example values to demonstrate its functionality.

## PROGRAM

a=int(input()) <br>
b=int(input()) <br>
c=int(input()) <br>
if a<b:  <br>
    big=a   <br>
else:   <br>
    big=b   <br>
if c<big:   <br>
    big=c  <br>
print("The Smallest  of the three a=",a,"b=",b,"c=",c,"is",big)  

## OUTPUT

![image](https://github.com/user-attachments/assets/2bfc4fee-e91e-4def-92b5-9f745dfc9a43)


## RESULT
Thus the given program implemented and executed successfully.
