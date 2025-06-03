# Ex.No:10(B) JAVA LINKED LIST

## AIM :
 To create a Java Program to read the size of the LinkedList, read the elements, and display them using Collection Framework.

## ALGORITHM :
1. Start the Program  
2. Import java.util.* package for input and LinkedList functionality  
3. Create Scanner object sc and LinkedList<String> cars  
4. Read size of the LinkedList  
5. Loop through size to add elements into LinkedList  
6. Display the LinkedList  
7. End

## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> cars = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
    System.out.println(cars);
  }
}
```


## OUTPUT:



## RESULT:
Thus, the Java Program to create and display a LinkedList using the Collection Framework was successfully executed.
