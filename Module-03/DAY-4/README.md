# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a Java program using the StringTokenizer class that tokenizes the string "welcome to java# programming" on the basis of the # symbol.

## ALGORITHM :

1.Start the program.

2.Import Scanner and StringTokenizer classes and define a class TokenizerExample.

3.In the main method:

i)Create a Scanner object sc.

ii)Initialize the string str as "welcome to java# programming".

iii)Create a StringTokenizer object token with str and # as the delimiter.

iv)Use a while loop to iterate through tokens:

v)Print each token using token.nextToken().

4.End the program.


## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner inp=new Scanner(System.in);
        String input=inp.nextLine();
        StringTokenizer tok=new StringTokenizer(input,"#");
        while(tok.hasMoreTokens())
        {
            System.out.println(tok.nextToken());
        }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/70e8cb97-4fc0-4644-800d-835aab6b1a86)


## RESULT:
Thus, the Java program using the StringTokenizer class that tokenizes a string "welcome to java# programming" on the basis of # was executed successfully.
