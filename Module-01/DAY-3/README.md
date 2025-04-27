# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:

Program to implement a class & objects using Java
Developed by: Lokesh R
RegisterNumber:  212222240055

```
import java.util.Scanner;

public class Demo
{
    public static void main(String[] args)
    {
       Scanner sc=new Scanner(System.in);
       int num=sc.nextInt();
       if(num ==0)
           System.out.println("Given number is Zero");
        else{
            System.out.print(num+" is Non-Zero");
        }
    }
}
```

## OUTPUT:

![{980EE531-3FF6-4E9C-BB2B-E87209FD09BF}](https://github.com/user-attachments/assets/4cbd5d8d-eedf-4ca9-8ab4-a0e3a10a93ab)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

