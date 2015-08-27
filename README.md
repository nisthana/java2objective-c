# java2objective-c
This contains various stuff a Java developer needs to know to move to objective c
# Classes and Objects
## Object Reference
-  Java <code>MyClass myObject;</code>
- In Objective-C <code>MyClass *myObject;</code> <br>we define the reference as "pointer" to the object. Pointer is denoted by the "*" symbol <br>

## Object Creation
- Java <code>MyClass myObject = new myObject();</code>
- OC <code>MyClass *myObject = [MyClass alloc];
<br>
The brackets syntax is similar to calling "methods". In OC, calling a method also means sending a "message" to the class. In the above case, we are sending a "message" for the object to allocate memory and in turn the response from the class is an instance of the object. Apart from allocating the memory, we also need to initialize the object so we need to pass an init message
<code>[myObject init];</code>
The two steps above can be combined into one
<code>[[MyClass alloc] init];</code>

