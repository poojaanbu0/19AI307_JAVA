# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
### pack/A.java
```
package pack; 
public class A {
    public void display() {
        System.out.println("This is Class A from pack package.");
    }
}
```
### mypack/B.java
```
package mypack;
import pack.A; 
public class B {
    public static void main(String[] args) {
        A obj = new A(); // Create object of class A
        obj.display();   // Call the method of class A
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/081c79ac-9896-478f-86c1-bfad3088682f)


## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

