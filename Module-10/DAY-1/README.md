# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
To create a Java Program to add even numbers from 1 to 10 or 11 to 20 or 21 to 30 in an ArrayList and then display the size of the ArrayList.

## ALGORITHM:
1. Start the Program  
2. Import java.util.* package for input and ArrayList functionality  
3. Define the class Main with the main method  
   a) Create an ArrayList<Integer> named al  
   b) Create a Scanner object sc for runtime input  
4. Loop 5 times using a for loop:  
   a) Read an integer from the user  
   b) Add the integer to the ArrayList al  
5. After the loop ends, print the size of the ArrayList using al.size()  
6. End
   
## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		ArrayList<Integer> al=new ArrayList<Integer>();
        Scanner sc=new Scanner(System.in);
        for(int i=1;i<=5;i++)
        {
        al.add(sc.nextInt());
        }
     
        System.out.println(al.size());
	}
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/25f83f2b-8977-4761-b64b-12e6c48daacc)


## RESULT:
Thus, the Java Program to add even numbers in a specified range to an ArrayList and display the size of the ArrayList was executed successfully.

