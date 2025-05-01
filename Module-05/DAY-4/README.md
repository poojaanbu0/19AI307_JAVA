# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To create a Java program to perform the addition of two numbers using class and object concepts and apply the HAS-A relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class Addition:
-	a) Declare two integers num1 and num2.
-	b) Define method add(int a, int b):
-	i) Set num1 = a and num2 = b.
-	ii) Calculate sum = num1 + num2.
-	iii) Print "Addition is:" followed by sum.
3.In the main class:
-	a) Use Scanner to read two integers
-	b) Create an object of class Addition.
-	c)Call add(a, b) method using the object.
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
class add{
   int sum(int a, int b) {
        return (a + b);
    } 
}
public class Main {
    public static void main(String args[]) {
        int a, b, s;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        b = sc.nextInt();
        add dd = new add();
        s = dd.sum(a, b);
        System.out.println("Sum is:" + s);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e687da34-567a-4e59-95b1-d42570de07d3)


## RESULT:
Thus, the Java program to perform the addition of two numbers using class and object concepts and applying the HAS-A relationship was executed successfully.

