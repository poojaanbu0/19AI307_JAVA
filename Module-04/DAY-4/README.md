# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Pooja A
RegisterNumber: 212222240072 
*/
```

## Sourcecode.java:

```
class Name
{
    String Degree;
    String Branch;
    String Year;
    Name(String d,String b,String y)
    {
        this.Degree=d;
        this.Branch=b;
        this.Year=y;
    }
    void dispName()
    {
        System.out.println(Degree+" "+Branch+" "+Year);
    }
}
class Student
{
    int Stu_Id;
    Name obj;
    Student(int id,String d,String b,String y)
    {
        this.Stu_Id=id;
        this.obj=new Name(d,b,y);
    }
    void dispStudent()
    {
        System.out.println(Stu_Id);
        obj.dispName();
    }
}

public class Main
{
    public static void main(String[] args)
    {
      Student stu=new Student(101,"B.Tech","IT","Third year");
      stu.dispStudent();
        
    }
}
```





## OUTPUT:

![437760259-947fbfd1-3e8b-4e75-894c-ce0aad7e74bb](https://github.com/user-attachments/assets/6d9100a3-97e3-4b4b-ab52-e95900053556)



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
