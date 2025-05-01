# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- c) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
```
class Name{
    String name="Johnson";
    void display(){
        class Inner{
            void print(){
                System.out.println("Name given in Outer Class is "+name);
            }
        }
        Inner o=new Inner();
        o.print();
    }
}
public class Main{
    public static void main(String[] argv){
        Name obj=new Name();
        obj.display();
    }
}

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/dd2ced34-8ba8-4b21-9ac5-8599cdb91b71)



## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

