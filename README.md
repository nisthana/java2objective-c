### Object References
MyClass myObject; //Java <br>
MyClass *myObject; //OC<br>

### Create instances
MyClass myObject = new MyClass(); //Java <br>
- Style 1
MyClass *myObject = [MyClass alloc];<br>
[myObject init];<br>
- Style 2
MyClass *myObject = [[MyClass alloc] init];<br>

### OC Messages == Java Methods
Format = [receiver selector arguments]<br>
Eg = [myObject prettyPrint:name]<br>

