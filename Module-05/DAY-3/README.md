# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To create a Java program to print the square of a given number using getter and setter methods.

## ALGORITHM :
1. Start the Program.
2. Define a class Square:

i)Declare a private integer variable num.

3.Define a setter method setNum(int n) to set the value of num.

4.Define a getter method getSquare():

i)Calculate and return the square of num.

5.Define the Main class with the main method:

i)Use Scanner to read the integer input from the user.

ii)Create a Square object.

iii)Set the value using setNum().

iv)Get and print the square using getSquare().

6.End the program.



## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
import java.util.*;
public class SetAndGet {
 
 private int w;

public int getSquare() {
 int sq=w*w;    
 return sq;
}

public void setSquare(int w) {
 this.w = w;
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int s1=sc.nextInt();
 
 
 obj.setSquare(s1);
 
 System.out.println("Square of "+s1+" is: "+obj.getSquare());

}

}

```






## OUTPUT:

![437763424-fb4ff6ce-c654-4a7c-a701-b962c13b90f7](https://github.com/user-attachments/assets/1a9ac77b-e953-4aed-8b82-bf836767508b)



## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






