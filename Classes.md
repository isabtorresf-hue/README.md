# Classes

## 1. Concept 

Classes are used to create objects in a program.

A class is like a template that describes the information and actions that an object can have.

For example, if we create a class called `Student`, we can define properties like name and age, and methods like studying.

Classes are an important part of object-oriented programming in C#.

---

## 2. Key C# Syntax

```csharp
class Student
{
    public string name;
    public int age;

    public void Introduce()
    {
        Console.WriteLine("My name is " + name);
    }
}

Student student1 = new Student();

student1.name = "Isabella";
student1.age = 23;

student1.Introduce();
