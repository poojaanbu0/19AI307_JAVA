# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Pooja A
RegisterNumber: 212222240072  
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

![439171021-afce41fe-6a77-4675-8d36-d22255d42953](https://github.com/user-attachments/assets/b1f3a4f4-7f05-48bb-95e9-d3bab0dbc07e)



## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




