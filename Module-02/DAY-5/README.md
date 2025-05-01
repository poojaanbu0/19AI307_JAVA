# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Write a Java program to find the smallest and second smallest elements of a given array.

## ALGORITHM :
1.	Input array size (size).
2.	If size < 2, print error and exit.
3.	Input size elements into the array.
4.	Initialize smallest and secondSmallest to Integer.MAX_VALUE.
5.	Loop through the array:
           i) Update smallest and secondSmallest as needed.
6.	If secondSmallest == Integer.MAX_VALUE, print error.
7.	Else, print smallest and secondSmallest.
8.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: SHAKTHI KUMAR S
RegisterNumber:  212222110043
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class SmallestElements {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int size = scanner.nextInt();
        
        if (size < 2) {
            System.out.println("Array should have at least two elements.");
            return;
        }

        int[] array = new int[size];

        for (int i = 0; i < size; i++) {
            array[i] = scanner.nextInt();
        }

        int smallest = Integer.MAX_VALUE;
        int secondSmallest = Integer.MAX_VALUE;

        for (int i = 0; i < size; i++) {
            if (array[i] < smallest) {
                secondSmallest = smallest;
                smallest = array[i];
            } else if (array[i] < secondSmallest && array[i] != smallest) {
                secondSmallest = array[i];
            }
        }

        if (secondSmallest == Integer.MAX_VALUE) {
            System.out.println("There is no second smallest element.");
        } else {
            System.out.println("Smallest element: " + smallest);
            System.out.println("Second smallest element: " + secondSmallest);
        }
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/afce41fe-6a77-4675-8d36-d22255d42953)



## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




