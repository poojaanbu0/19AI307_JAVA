# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a Java program that uses the delete() method of the StringBuffer class to delete the string from the specified beginIndex to endIndex.

## ALGORITHM :
1.Start the program.

2.Import Scanner and define a class DeleteExample.

3.In the main method:

i)Create a Scanner object sc.

ii)Read a string from user input.

iii)Read beginIndex and endIndex from user input.

iv)Create a StringBuffer object sb initialized with the input string.

v)Call sb.delete(beginIndex, endIndex) to delete the specified part.

vi)Print the modified string.

4.End the program.

## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringBufferExample4 {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        int startIndex = sc.nextInt();
        int endIndex = sc.nextInt();
        StringBuffer sb = new StringBuffer(str1);
        sb.delete(startIndex, endIndex);
        System.out.println(sb);

        sc.close();
    }
}
```

## OUTPUT:
```
Input	      Expected	    Got
Hello World   Hlo World    Hlo World
1
3
namastae      namastae     namastae
0
0
```

## RESULT:
Thus, the Java program that uses the delete() method of the StringBuffer class to delete a portion of the string was executed successfully.
