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

### Messages (methods) declaration and call
- Example of a method that takes in Single argument
void javaMethodWithOneArg(String name);

String name = "John";
javaMethodWithOneArg(name)

In Objective C
-(void)methodWithOneArg:(NString *) name {
}
NString* name = @"John";
[myObject methodWithOneArg:name]

- Example of a method that takes in two arguments
void javaMethodWithTwoArgs(String name,int Street);

String name = "John";
javaMethodWithOneArg(name)

In Objective C
-(void)methodWithOneArg:(NString *) name {
}
NString* name = @"John";
[myObject methodWithOneArg:name]

