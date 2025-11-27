# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.



## AIM:
To write a Java program that accepts a string from the user and prints the reversed string.


## ALGORITHM :
1.	Start the program.

2 .Import the package java.util.Scanner.

3 .Create a Scanner object to read input from the user.

4 .Read the input string.

5 .Initialize an empty string variable rev to store the reversed string.

6 .Use a loop to traverse the string from the last character to the first:

7 .Append each character to rev.

8 .After the loop ends, display the reversed string.

9 .End the program.	

## PROGRAM:
 ```
Program to implement a Strings and Math Function using Java
Developed by: Gnanendran N
RegisterNumber:  212223240037
```

## SOURCE CODE:
```java
import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.nextLine();
        String rev = "";
        for (int i = str.length() - 1; i >= 0; i--) {
            rev = rev + str.charAt(i);
        }


        System.out.println("Reversed string: " + rev);

        sc.close();
    }
}
```
## OUTPUT:
<img width="1283" height="346" alt="image" src="https://github.com/user-attachments/assets/534f0f79-6b9c-4995-92be-67f2c08e4b8c" />


## RESULT:
Thus, the Java program to reverse a given string was executed successfully and the reversed output was obtained.

