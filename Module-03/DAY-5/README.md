# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that prints a new value by modifying an existing StringBuilder object, demonstrating that strings can be changed (mutable string).

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a StringBuilder object sb with an initial string.
3.	Modify the content of sb using methods like append(), insert(), or replace().
4.	Print the modified content of sb to show that the string has been changed.
5.	End the program.

## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
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

![image](https://github.com/user-attachments/assets/54343179-9be1-4ab9-9e95-02904e0b9576)

## RESULT:
Thus, the Java program successfully demonstrated that the string can be modified in the existing StringBuilder object, showing the mutable nature of strings using StringBuilder.

