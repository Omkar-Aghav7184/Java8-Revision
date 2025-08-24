# Features of Java8:

1) Lambda Expression:
    - It is also known as "Anonymous function".
    - It is similar to methods, but they do not need a name and  they can be implemented right in the body of a method.
    - # Example: (x,y)-> x+y;

2) Stream API: Java Stream API is used  for bulk of data. Operations on Collections.

3) Date and Time API:  Under the package java.time, Java 8 offers a new date-time API.

4) Base64 Encode and Decode: 
    - For Base64 encoding, Java 8 has built-in  encode and decode functions.
    - The Base64 encoding class in java.util.Base64.

5) Method & constructor reference: (:: operator)

6) Default methods in Interface: 
    - Interfaces can have methods with default implementations.  
    - Helps to add new methods to interfaces without breaking existing implementations.

7) Statis methods in Interface: 
    - Interfaces can have static methods that can be called without an instance.  
    - Example: `InterfaceName.staticMethod()`

8) Functional Interface: 
    - A `functional interface` is an interface that has exactly one abstract method. To designate an interface as a functional interface.
    - We don't need to use the @FunctionalInterface annotation.

9) Optional Class:
   - The `Optional` class in Java 8 is a container object used to represent the presence or absence of a value. It is primarily used to avoid `null` checks and `NullPointerException`.
   - By using `Optional`, developers can specify methods to handle both the presence and absence of a value explicitly, promoting cleaner and more readable code.

10) Java IO Improvements:
     - Java 8 introduced several improvements to the IO (Input/Output) API, focusing on enhancing the performance and usability of file operations.
     - Notable enhancements include the addition of the `java.nio.file` package with utility classes like `Files` and `Paths`, which provide more efficient and flexible ways to handle file operations, such as reading, writing, and manipulating file paths.

11) Collection API Improvements: 
    - The Collection API in Java 8 saw significant improvements, including the introduction of new methods for existing collections. 
    - One of the major additions was the `Stream` API, which allows for functional-style operations on collections, such as `filtering, mapping, and reducing.` 
    - Other enhancements include methods like `forEach`, `removeIf`, `replaceAll`, and `sort`, which provide more concise and expressive ways to work with collections.