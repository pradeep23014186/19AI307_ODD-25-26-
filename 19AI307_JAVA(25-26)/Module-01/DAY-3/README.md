# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.



## AIM:
To write a Java program that demonstrates the use of looping statements such as for, while, or do-while to perform repetitive tasks.


## ALGORITHM :
1 .Start the program.

2 .Import the package java.util.Scanner.

3 .Create a Scanner object to read input from the user.

4 .Read an integer value n from the user.

5 .Initialize a variable fact to 1.

6 .Use a for loop from i = 1 to i = n:

7 .Multiply fact by i in each iteration.

8 .After the loop ends, display the value of fact as the factorial of n.

9 .End the program.

## PROGRAM:
 ```
Program to implement a Looping Statement using Java
Developed by: Gnanendran N
RegisterNumber:  212223240037
```

## SOURCE CODE:
```java
import java.util.Scanner;

public class Factorial {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Input from user
        int n = sc.nextInt();

        long fact = 1; 

        for (int i = 1; i <= n; i++) {
            fact *= i;
        }

        // Output
        System.out.println("Factorial of " + n + " is: " + fact);
    }
}
```


## OUTPUT:
<img width="1286" height="348" alt="image" src="https://github.com/user-attachments/assets/711b62fd-42ff-41a1-b8d6-ff6cffb3fc8f" />


## RESULT:
Thus, the program using looping statements in Java was successfully executed and the desired output was obtained.



