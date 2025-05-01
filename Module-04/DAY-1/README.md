# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using a copy constructor to print the area of a rectangle with given dimensions [l=5, w=6].

## ALGORITHM :
1.Start the Program.

2.Define a class Rectangle.

3.Inside the class, define two integer variables l (length) and w (width) with values 5 and 6.

4.Create a parameterized constructor that initializes l and w.

5.Create a copy constructor that takes another Rectangle object and copies its values.

6.Create a method to calculate and print the area (Area = l × w).

7.In the main method:

i)Create an object r1 using the parameterized constructor.

ii)Create an object r2 using the copy constructor by copying r1.

iii)Call the method to print area from r2.

8.End the program.

## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
```
class Rectangle 
 { 
         int length; 
         int breadth; 
         
         Rectangle(int l, int b) 
         {  
             this.length=l;
             this.breadth=b;
         } 
        
         Rectangle(Rectangle obj) 
         { 
           this.length=obj.length;
           this.breadth=obj.breadth;
    
         } 
        
        int Area() 
        { 
           return (length*breadth);
        } 
 } 
        //class to create Rectangle object and calculate area 
public class CopyConstructor 
 { 
           public static void main(String[] args) 
           { 
             Rectangle firstRect = new Rectangle(5,6); 
            Rectangle cpyRect=new Rectangle(firstRect);
            int area=cpyRect.Area();
            System.out.println("Area  of First Rectangle : "+area);
            System.out.println("Area of First Second Rectangle : "+area); 
           } 
 } 
 ```

## OUTPUT:

![image](https://github.com/user-attachments/assets/3b11f7db-bc29-4341-8026-3e885f59e612)

## RESULT:
Thus, the Java program using a copy constructor to print the area of a rectangle was executed successfully.
