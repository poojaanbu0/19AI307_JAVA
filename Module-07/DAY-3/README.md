# Ex.No:7(C)             THREAD IN JAVA
## AIM:
  To Develop a Java program to create Thread using extends class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End


## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
   import java.util.*;
    public class Multi extends Thread
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        int count=sc.nextInt();
        System.out.println("Thread Count: " +count);  
    }  
    public static void main(String args[]){  
    Multi t1=new Multi();  
    t1.start();  
     }  
    }  
```






## OUTPUT:

![442063672-c02075c4-14a5-47cb-96ef-d8e549fb3282](https://github.com/user-attachments/assets/63cdb41a-3176-4c6f-8958-ac6e165146e1)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.
