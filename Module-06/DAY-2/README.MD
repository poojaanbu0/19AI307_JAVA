# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
```
import java.util.*;
class Shapes{
    public void print_Shape(){
        System.out.println("Shapes Class");
    }
}
class Circle extends Shapes{
    double radius;
    Scanner sc=new Scanner(System.in);
    public void get()
    {
        radius=sc.nextDouble();
    }
}
class Area extends Circle{
    public void calc(){
        double area=3.14*radius*radius;
        System.out.println("Area of Circle is "+area);
    }
}
public class Main{
    public static void main(String[] args){
        Area area=new Area();
        area.print_Shape();
        area.get();
        area.calc();
    }
}
```

## OUTPUT:
```
Input        Expected  	                               Got

2          Shapes Class                              Shapes Class
           Area of Circle is 12.56                   Area of Circle is 12.56

3          Shapes Class                              Shapes Class
           Area of Circle is 28.259999999999998      Area of Circle is 28.259999999999998

```
## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





