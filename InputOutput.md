# Input and Output

## 1. Concept 

Input and output are used to make a program communicate with the user.

Input means that the program receives information from the user. Output means that the program shows information on the screen.

In C#, we usually use `Console.ReadLine()` to get information and `Console.WriteLine()` to display information.

---

## 2. Key C# Syntax

```csharp
Console.WriteLine("What is your name?");

string name = Console.ReadLine();

Console.WriteLine("Hello " + name);
