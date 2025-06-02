# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
import java.util.*;
public class MutableStr{ 
    public static void main(String[ ] args) {
        Scanner input=new Scanner(System.in);
        String str=input.nextLine();
        StringBuilder sb=new StringBuilder(str);
        sb.append(" Easy");
        sb.append(" today");
        System.out.println(sb); 
        
    } 
}
```

## OUTPUT:

![437753970-54343179-9be1-4ab9-9e95-02904e0b9576](https://github.com/user-attachments/assets/b5aceee0-7c21-4e79-abcf-53738a084fef)


## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.
