# reading-notes-401


## Reading 3

### System.I.0


System I/O refers to the transfer of data either to or from a storage medium. -From Microsoft docs.
You can write to a file synchronously with write or writeLine or asynchronously with WriteAsync and WriteLineAsync. 

On the flip side you may read synchronously or asynchronously as well. Some example code to read synchronously looks like this (from microsoft docs)

```
using System;
using System.IO;

class Program
{
    public static void Main()
    {
        try
        {
            // Open the text file using a stream reader.
            using (var sr = new StreamReader("TestFile.txt"))
            {
                // Read the stream as a string, and write the string to the console.
                Console.WriteLine(sr.ReadToEnd());
            }
        }
        catch (IOException e)
        {
            Console.WriteLine("The file could not be read:");
            Console.WriteLine(e.Message);
        }
    }
}
```

[Table Of Contents](README.md)