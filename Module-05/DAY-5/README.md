# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a Java program to separate the individual characters from a string using a tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Create a tightly encapsulated class StringData:
a.	Declare a private String variable text.
b.	Provide public getter and setter methods for text.
3.Create another class StringOperation:
a.	Create a method separateCharacters() that accepts a StringData object.
b.	Loop through the string and print each character separately.
4.	In the main() method of a class Main:
a.	Create an object of StringData and use the setter method to set the string.
b.	Create an object of StringOperation and call separateCharacters() by passing the StringData object.
5.	End the program.
	
## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
*/
```

## Sourcecode.java:

```
import java.util.*;
class Str{
    private String name;
    public void set(String name){
        this.name=name;
    }
    public void get(){
        for(int i=0;i<name.length();i++){
            System.out.print(name.charAt(i)+" ");
        }
    }
}
public class Main{
    public static void main(String[] args){
        Scanner inp=new Scanner(System.in);
        String name=inp.nextLine();
        Str obj=new Str();
        obj.set(name);
        obj.get();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/b3266ebd-738e-4d58-9a4e-ed87a65fd130)


## RESULT:
Thus, the Java program to separate the individual characters from a string using a tightly encapsulated class was executed successfully.

