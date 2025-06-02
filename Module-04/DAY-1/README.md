# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End


## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: Pooja A
RegisterNumber: 212222240072 
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

![437757427-3b11f7db-bc29-4341-8026-3e885f59e612](https://github.com/user-attachments/assets/487c6660-363d-4334-975c-5cb631269d05)



## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
