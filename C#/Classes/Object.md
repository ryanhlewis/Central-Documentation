# Object Class

### Declaration

public virtual **Object**();

### Description

Returns a new Object() instance, the top of the hierarchy of classes in C#. Every class inherits from Object, and Object defines generic methods such as toString() and 


future - more description 


future- implement example class

```C#

using System;

public class ExampleClass
{

    // Generates a random integer ranging from 1 (inclusive) to 10 (exclusive)
    static void Main()
    {
        Random rnd = new Random();

        int randomVal = rnd.Next(1,10);
        Console.WriteLine(randomVal);
    }
}

```