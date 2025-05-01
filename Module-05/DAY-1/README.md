# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To create a Java program to calculate the product of two numbers using encapsulation concepts.

## ALGORITHM :
1.  Start the program.
2.  Define a class Product:
3.  Declare two private integer variables: num1 and num2.
4.  Define setNum1(int n1) method to set num1.
5.  Define setNum2(int n2) method to set num2.
6.  Define getProduct() method to return the product of num1 and num2.

i)Define the main class with main method:

ii)Create a Scanner object to read user input.

iii_Read two numbers from the user.

iv)Create a Product object.

v)Set values using setNum1() and setNum2().

vi)Display the product using getProduct().

7.End the program.

## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:

```
import java.util.*;
class add
{
    private int a,b;
    public void sno1(int x)
    {
        a=x;
    }
    public void sno2(int y)
    {
        b=y;
    }
    void sum()
    {
        int out=a*b;
        System.out.print(out);
    }
}
public class ss{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        add obj=new add();
        obj.sno1(sc.nextInt());
        obj.sno2(sc.nextInt());
        obj.sum();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c5d1e44d-5c1d-49a5-872c-11c5ca75a7d3)


## RESULT:
Thus, the Java program to calculate the product of two numbers using encapsulation concepts was successfully executed.
