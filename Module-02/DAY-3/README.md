# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 5 values and display the all 5 values from array using single dimensional array.

## ALGORITHM :
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 5`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 5`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
8.	End


## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:

```
import java.util.*;
public class ArrayExample{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int[] arr = new int[3];
        System.out.println("One dimensional array elements are");
        for(int i=0;i<arr.length;i++)
        {
            arr[i]=sc.nextInt();
        }
        for(int i=0;i<arr.length;i++)
        {
            System.out.println(+arr[i]);
        }

    }
}
```





## OUTPUT:

![437406003-36820e51-bdef-4a59-bad7-28707a815113](https://github.com/user-attachments/assets/6459b83a-41f0-42e7-a2ab-604193de9a5f)



## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


