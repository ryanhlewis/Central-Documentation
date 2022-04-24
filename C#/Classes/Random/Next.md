# Random.Next

### Declaration

public virtual int **Next**(int **minInclusive**, int **maxExclusive**);

### Description

Returns a random ```int``` within ```[minInclusive..maxExclusive]``` (upper bound is exclusive).

If ```minInclusive``` is not provided, then it returns  ```[0..maxExclusive]```

If both variables are not provided, then it returns ```[0..maxInt32Value]```


There are ```float```, ```double```, and ```long``` versions of this function that operate slightly differently, especially regarding the range maximum.
See their docs in [Random.NextFloat](), [Random.NextDouble](), [Random.NextLong]().

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
