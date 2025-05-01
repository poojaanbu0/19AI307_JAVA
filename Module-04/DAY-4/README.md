# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program for the given situation:Student object contains a member Stu_Id. It contains an object named Course, which contains its own information such as Degree, Branch, and Year of Studying.
 
## ALGORITHM :
1.Start the Program.

2.Define a class Course:

i)Declare three String variables: Degree, Branch, and Year.

ii)Define method dispCourse(String deg, String br, String yr):

iii)Print Degree, Branch, and Year using passed parameters.

3.Define a class Student:

i)Declare an integer variable Stu_Id.

ii)Create an instance of Course called obj.

iii)Define method disp(int id):

iv)Print the Student ID.

v)Create a new Course object and call dispCourse("B.Tech", "CSE", "3rd Year").

4.Define the main class with the main method:

i)Create a Student object stu.

ii)Call stu.disp(12345) to display student details.

End the program.

## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: SHAKTHI KUMAR S
RegisterNumber: 212222110043
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

![image](https://github.com/user-attachments/assets/947fbfd1-3e8b-4e75-894c-ce0aad7e74bb)


## RESULT:
Thus, the Java program for the situation where a Student object contains a Course object was successfully executed using final and static keywords.
