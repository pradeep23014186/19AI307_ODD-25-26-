# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to reverse an array


## AIM:
To write a Java program to reverse the elements of an array and display the reversed array.


## ALGORITHM :
1 .Start the program.

2 .Import the package java.util.Scanner.

3 .Create a Scanner object to read input from the user.

4 .Read the size of the array n.

5 .Create an integer array of size n.

6 .Read all n elements from the user and store them in the array.

7 .Use a loop to print the elements of the array in reverse order:

8 .Start from the last index and move towards the first index.

9 .Display the reversed array.

10 .End the program.





## PROGRAM:
 ```
Program to implement a Array concept using Java
Developed by: Gnanendran N
RegisterNumber: 212223240037
```

## SOURCE CODE:
```java
import java.util.Scanner;

public class ReverseArray {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        
        int n = sc.nextInt();
        int[] arr = new int[n];

        
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        
        for (int i = n - 1; i >= 0; i--) {
            System.out.print(arr[i] + " ");
        }

        sc.close();
    }
}
```


## OUTPUT:
<img width="1280" height="633" alt="image" src="https://github.com/user-attachments/assets/7da14810-7037-4ed3-bad9-7d567b3cedaa" />


## RESULT:
Thus, the Java program to reverse the elements of an array was executed successfully and the expected output was obtained.
