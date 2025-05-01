# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Laptop class that initializes the brand and price class fields with the values "Apple" and 42500.75, and then call getter methods in the main method of another class (Sample) to display the values.

## ALGORITHM :

1.	Start the program.
2.	Define a class Laptop:
i)Declare two private fields: String brand and double price.

3.Create a parameterized constructor:

i)Accept brand and price as parameters.

ii)Assign the parameters to the class fields.

4.Define two getter methods in Laptop:

i)getBrand() – returns the value of brand.

ii)getPrice() – returns the value of price.

5.Define another class Sample with the main method:

i)Create a Laptop object using the constructor, passing "Apple" and 42500.75.

ii)Call getBrand() and store the result in a variable.

iii)Call getPrice() and store the result in a variable.

iv)Print the values of brand and price.

5.End the program.

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043 
*/
```

## Sourcecode.java:

```
 class Laptop {

	String brand;
	double price;
    Laptop(String b,double p){
        this.brand=b;
        this.price=p;
    }
	
	
	public String getBrand() {
           return brand;
	}
	public double getPrice() {
	        return price;
	}
}

public class Sample {
	
	public static void main(String[] args) {

		Laptop obj=new Laptop("Apple",42500.75);
		String bname=obj.getBrand();
		double pvalue=obj.getPrice();
		System.out.println(bname);
		System.out.print(pvalue);
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c1082fd0-27d8-4213-9e0c-8fd4b63934e5)


## RESULT:
Thus, the Java program successfully demonstrates the use of a parameterized constructor to initialize class fields, and the values were retrieved and displayed using getter methods.

 


