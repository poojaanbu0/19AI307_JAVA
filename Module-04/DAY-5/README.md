# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

	1.	Start the program.
2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
3.	Create a parameterized constructor in Employee:
4.	Accept two parameters: name and designation.
5.	Assign the parameters to the class fields.
6.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
7.	Create another class Sample with the main method.
8.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
9.	Print the values of empName and empDesg.
10.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Pooja A 
RegisterNumber: 212222240072 
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


![437761210-c1082fd0-27d8-4213-9e0c-8fd4b63934e5](https://github.com/user-attachments/assets/96c84063-cf35-4344-9868-1fa2d5dbfbf6)


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


