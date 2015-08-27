# java2objective-c
This contains various stuff a Java developer needs to know to move to objective c
# Classes and Objects
- Object Reference
-  Java <code>MyClass myObject;</code>
- In Objective-C <code>MyClass *myObject;</code> <br>we define the reference as "pointer" to the object. Pointer is denoted by the "*" symbol <br>

- Object Creation
- Java <code>MyClass myObject = new myObject();</code>
- OC <code>MyClass *myObject = [MyClass alloc];

The brackets syntax is similar to calling "methods". In OC, calling a method also means sending a "message" to the object. In the above case, we are sending a "message" for the object to allocate memory and in turn the response from the object is the instance it returns.
