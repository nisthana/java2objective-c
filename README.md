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

String name = "John";<br>
myObject.javaMethodWithOneArg(name);<br>

In Objective C<br>
-(void)methodWithOneArg:(NString *) name {<br>
}<br>
NString* name = @"John";<br>
[myObject methodWithOneArg:name]<br>

- Example of a method that takes in two arguments
void javaMethodWithNameAndAge(String name,int age);<br>

String name = "John";<br>
int age = 30;<br>
myObject.javaMethodWithNameAndAge(name,age);<br>

In Objective C<br>
-(void)methodWithName:(NString *)name andAge:(int) age {<br>
}<br>
NString* name = @"John";<br>
int age = 30;<br>
[myObject methodWithName:name andAge:age];<br>

- method with 3 parameters
<code>
-(void)methodWithName:(NString *)name andAge:(int) age includingAddress(NSString*)address{<br>
}<br>
NSString* name = @"John";<br>
int age = 30;<br>
NSString* address = "San Jose,CA";
[myObject methodWithName:name andAge:age includingAddress:address];<br>
</code>
