# Ex.No:6(E)  SINGLE INHERITANCE

## AIM:
To write a Java program using single inheritance to perform addition and subtraction of two numbers.

## ALGORITHM :

1.Start the program.
  
2.Create a parent class Number:
   
a.	Define two integer variables num1 and num2 initialized with values 10 and 5.

b. Define an integer variable result.

3.Create a subclass Addition that extends Number:
   
a.	Define a method add() to perform addition and display the result.

4.Create another subclass Subtraction that extends Number:

a.	Define a method sub() to perform subtraction and display the result.

5.In the Main class:
   
a.Create objects for Addition and Subtraction.

b.	Call the add() and sub() methods respectively

6.End the program.


## PROGRAM:
 ```
/*
Program to implement a Single Inheritance
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:

```
import java.util.*;
class Number{
    int num1=10,num2=5,result;
    public void display(String ope){
        System.out.println(ope+" of 2 values "+result);
    }
}
class Addition extends Number{
    public void add(){
        result=num1+num2;
    }
}
class Subtraction extends Number{
    public void sub(){
        result=num1-num2;
    }
}
public class Main{
    public static void main(String[] args){
        Addition obj=new Addition();
        obj.add();
        obj.display("Addition");
        Subtraction obj1=new Subtraction();
        obj1.sub();
        obj1.display("Subtraction");
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/536d3254-968a-44b6-b7a4-6c4992a0b7cd)


## RESULT:
Thus, the Java program to demonstrate single inheritance was successfully executed and the addition and subtraction operations were performed.
