# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to write a String in a file "testout.txt" using FileOutputStream

## ALGORITHM :
1.  Define the string "Welcome to Saveetha" and convert it to a byte array b using getBytes().
2.	Use Scanner to prompt the user for start (starting index) and length (number of bytes) to write from the string.
3.	Open testout.txt using FileOutputStream, and write the specified portion of b from the start index for length bytes, then close the output stream.
4.	Open testout.txt using FileInputStream, read its contents byte-by-byte, convert each byte to a character, and print it to display the file's content.
5.	Use file.delete() to delete testout.txt.
6.	Attempt to read the deleted file, which triggers a FileNotFoundException as the file no longer exists.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Pooja A
RegisterNumber:  212222240072
*/
```

## Sourcecode.java:
```
   
                 FileOutputStream fout=new FileOutputStream("testout.txt");    
             String s="HI EVERYBODY...";    
             byte b[]=s.getBytes();//converting string into byte array    
             fout.write(b);    
             fout.close();    
                 System.out.println("Successfully Completed");
```

## OUTPUT:

![443558218-2b8d9885-79ca-4ae7-9af3-fc89ad666c26](https://github.com/user-attachments/assets/5009eb0f-ad44-4f72-916d-387e221cdd89)


## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

