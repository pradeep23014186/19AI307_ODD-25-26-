# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
A shop keeper would like to welcome their customers with their name.

Write a java program to get name from the user (String) and print it.



## AIM:
To develop a Java program that receives a single string input (the customer's name) from the user and prints a personalized greeting message in the format "Hello, [name]"


## ALGORITHM :
1 .Start: Begin the main method execution.

2 .Setup Input: Import and create an instance of the Scanner class, linking it to the standard input stream (System.in).

3 .Read Name: Read the entire line of string input provided by the user and store it in a variable named customerName.

4 .Process Output: Concatenate the fixed string "Hello, " with the value stored in customerName.

5 .Print: Display the resulting greeting string to the console using System.out.println().

6 .Cleanup: Close the Scanner resource.

7 .End: Terminate the program execution.



## PROGRAM:
 ```
Program to implement variables and Operators using Java
Developed by: Gnanendran N
RegisterNumber: 212223240037
```

## Sourcecode.java:
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);

        String name = sc.nextLine();

       
        System.out.println("Hello, " + name);

        sc.close();
    }
} 
```






## OUTPUT:
<img width="1280" height="257" alt="image" src="https://github.com/user-attachments/assets/b3ab17b2-f4b1-48b2-9f44-90d0bf797ccc" />




## RESULT:
The program successfully reads a name from the user and prints the message.


