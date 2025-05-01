# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To create a Java program for calculating the area of a triangle with the help of getter and setter methods, implementing tightly encapsulated concepts and printing the value of the area of the triangle.

## ALGORITHM :
1.	Start the program.

2.Define a class Triangle:

i)Declare two private variables: width and height.

3.Create setter methods:

i)setWidth(int w) to set the width.

ii)setHeight(int h) to set the height.

4.Create a getArea() method:

i)Calculate the area using the formula Area = (width × height) / 2.

ii)Return the calculated area.

5.Define the Main class with the main method:

i)Create a Scanner object to read input.

ii)Read width and height values from the user.

iii)Create a Triangle object.

iv)Set width and height using setter methods.

v)Get and print the area using getArea().

6.End the program.


## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class SetAndGet {
 
 private int w;
 private int h;


public int getWidth() {
 return w;
}

public void setWidth(int w) {
 this.w = w;
}

public int getHeight() {
 return h;
}

public void setHeight(int h) {
 this.h = h;
}


public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int s1=sc.nextInt();
 int s2=sc.nextInt();
 
 obj.setWidth(s1);
 obj.setHeight(s2);
 System.out.println(obj.getWidth() * obj.getHeight());

}


}
```

## OUTPUT:

```
Input    Expected     Got
5          50          50
10

	
5          25          25
5

3           9           9
3
```
## RESULT:
Thus, the Java program to calculate the area of a triangle using getter and setter methods and implementing tightly encapsulated concepts was successfully executed.




