# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance based on the given scenario where Media is the parent class, and Magazine and Channel are the child classes.


## ALGORITHM :
1.  Start the Program
2.	Define class Media:
-	a) Constructor displays "Parent Class is Media"
3.	Define class Magazine that extends Media:
-	a) Constructor calls the parent constructor using super().
-	b) Displays "Magazine is one of the Child of Media Class".
4.	Define class Channel that extends Media:
-	a) Constructor calls the parent constructor using super().
-	b) Displays "Channel is one of the Child of Media Class"
5.	In the Main class:
-	a) Create an object of Magazine class.
-	b) Create an object of Channel class.



## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: Pooja A
RegisterNumber: 212222240072 
*/
```

## Sourcecode.java:

```
class Media
{
public Media()
{
System.out.println("Parent Class is Media");
}
}
class Channel extends Media
{
public Channel()
{
super();
System.out.println("Channel is the one of the Child of Media Class");
}
}
class Magazine extends Media
{
public Magazine(){
super();
System.out.println("Magazine is the one of the Child of Media Class");
}
}
public class Main
{
public static void main(String[] args)
{
Magazine magazine=new Magazine();
Channel channel=new Channel();
}}
```





## OUTPUT:

![438284066-33bb06ec-0c4c-451c-b7eb-86b66fd6fa3c](https://github.com/user-attachments/assets/622346ca-6f40-496d-9cab-668d4945333f)



## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






