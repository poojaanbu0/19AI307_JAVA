# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: Pooja A
RegisterNumber: 212222240072  
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

![437753090-70e8cb97-4fc0-4644-800d-835aab6b1a86](https://github.com/user-attachments/assets/eff9ba69-673f-4bb4-841a-713c15ae0d3c)



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
