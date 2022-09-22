# Sept20Notes
* Life and Death of an object
>Java has 2 areas of memory
>>Stack & the heap
>>>Stack contains method invokations and local variables, heap has objects and all of their instance variables


>Local variables: Declared inside method, including parameters
>>temprary
> 
> Reference variables: refers to objects
> >Stored in stack but object itself goes on heap
> 
> Instance variable: Declared inside class, outside method (also known as properties

>Methods are stacked like blocks in the stack when they are being invokated. Only the top block is the currently exectued one.  The system of removal is called last in first out, meaning the most top block needs to be kicked off the stack in order for the previous method to continue its execution


* Serious Polymorphism
>Literally means "multiple forms"

>Abstract keyword prevents objects being instantiated from that class
>>They have no value unless you extend them. Make sure to extend them!
>
>Opposite of an abstract class is a concrete class
>> EX: I made a canine abstract class because I dont want user to be able to create canine objects since it is too broad. However, dog is a concrete class
> 
> Abstract methods get passed down. They are only initiated in one of the parent classes
> 
>All abstract methods must be implemented. Otherwise you will get an error

> Every class in java extends the class Object

>Interfaces give us the polymorphic benefits of of multiple inheritance without having to put the method in one of the parent classes.
>>Key word: Implements

*How Objects Behave
>Class is a blueprint of an object

>Return keyword gets things back from a method

>Method takes parameters
 
> Making instance variables private and then making getters and setters allows us to control how our data can be changed

>Objects can have arrays, just like string and int!

*Knowing your variables
>Variables must have a type and name

> Think of a variable like a cup...its a container that holds something
>>Arrays are like a tray of cups

>Variables can be primitive or references to objects
>> No such thing as "object variable", it is object reference variable
