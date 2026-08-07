# Switch Statements

## 1. Concept 

A switch statement is another way to make decisions in a program.

It is useful when we have many possible options and we want to compare one value with different cases.

Instead of writing many `if` and `else if` statements, a switch can make the code easier to read.

---

## 2. Key C# Syntax

```csharp
int day = 3;

switch (day)
{
    case 1:
        Console.WriteLine("Monday");
        break;

    case 2:
        Console.WriteLine("Tuesday");
        break;

    case 3:
        Console.WriteLine("Wednesday");
        break;

    default:
        Console.WriteLine("Invalid day");
        break;
}
