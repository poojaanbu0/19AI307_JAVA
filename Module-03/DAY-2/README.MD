# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End







## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: Pooja A
RegisterNumber:  212222240072
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
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
