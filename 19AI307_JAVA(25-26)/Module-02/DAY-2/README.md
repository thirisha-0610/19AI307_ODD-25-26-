# Ex.No:2(B) METHODS

## QUESTION:

Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).
## AIM:

To write a Java program that demonstrates calling one method from another method to compute the cube of a number.
## ALGORITHM :
1.Start the program.
2.Import the necessary package 'java.util'
3.Create a method square(int x) that returns the square of x.
4.Create a method cube(int x) that calls square(x) and returns x * square(x).
5.In the main method, read an integer from the user.
6.Call the cube() method and display the result.
7.Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: THIRISHA A
RegisterNumber: 212223040228
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Main
{
    static int square(int x)
    {
        return x*x;
    }
    static int cube(int x)
    {
        return x*square(x);
    }
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        int result=cube(num);
        System.out.println(result);
    }
}

```





## OUTPUT:

<img width="453" height="163" alt="java22" src="https://github.com/user-attachments/assets/2e1f8c82-8893-4f0a-9cca-5110477218a2" />


## RESULT:
Thus, the Java program to calculate the cube of a number by calling the square method internally was successfully implemented and executed.
