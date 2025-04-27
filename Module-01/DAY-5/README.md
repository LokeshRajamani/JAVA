# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 
Program to implement a Static Variable using Java


Developed by: Lokesh R

RegisterNumber:  212222240055
```
class Student {
    String name;
    static int age;

    public Student(String name) {
        this.name = name;
    }

    public void displayDetails() {
        System.out.println("Student name: " + name + ", Age: " + age);
    }

    public static void main(String[] args) {
        Student.age = 18;

        Student student1 = new Student("John");
        Student student2 = new Student("Ram");

        student1.displayDetails();
        student2.displayDetails();
    }
}

```
## OUTPUT:

![{76E36E1F-38B1-4054-956B-9D30A9F2F202}](https://github.com/user-attachments/assets/6ff7f745-9e9b-4f77-a78b-84a4aa692479)


## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

