# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
A pirate ship has a code lock that only opens if:

The input code is even, and

If it is less than 100, say "Weak Code".

If it is between 100 and 999, say "Strong Code".

If the code is odd, deny access.

For example:

Input	Result
42
Weak Code


## AIM:
Write a Java program to implement a conditional statement.


## ALGORITHM :
1 .Start the program.

2 .Import the package java.util.Scanner.

3 .Create a Scanner object to read input from the user.

4 .Read an integer value code from the user.

5 .Check if code is even using code % 2 == 0.

6 .If the code is even:
a. Check if code is less than 100:

7 .Print "Weak Code".
b. Else if code is between 100 and 999 (inclusive):

8 .Print "Strong Code".
c. Else (code is greater than 999):

9 .Print "Access Denied".

10 .If the code is odd:

Print "Access Denied".

11 .End the program.





## PROGRAM:
 ```
Program to implement a conditional statement using Java
Developed by: Gnanendran N
RegisterNumber:  212223240037
```

## SOURCE CODE:
```java
import java.util.Scanner;
public class Pirate{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        int code=sc.nextInt();
        if (code%2==0){
            if (code<100){
                System.out.println("Weak Code");
            }
            else if (code>=100 && code<=999){
                System.out.println("Strong Code");
            }
            else{
                System.out.println("Access Denied");
            }
        }
        else{
            System.out.println("Access Denied");
            
        }
            
    }
}

```


## OUTPUT:
<img width="1277" height="391" alt="image" src="https://github.com/user-attachments/assets/8089ccef-0dc3-4a4b-aa66-402ea4c82c76" />


## RESULT:
Thus, the program to implement conditional statements in Java was executed successfully.


