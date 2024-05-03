# OOP-features
This is a repository explaining the features of object oriented programming

1.	Encapsulation
The meaning of Encapsulation, is to make sure that "sensitive" data is hidden from users. To achieve this, one must:
•	declare class variables/attributes as private
•	provide public get and set methods to access and update the value of a private variable

Get and Set
Private variables can only be accessed within the same class (an outside class has no access to it). 
However, it is possible to access them if we provide public get and set methods.
The get method returns the variable value. 
The set method sets the value.

Why Encapsulation?
•	Better control of class attributes and methods
•	Class attributes can be made read-only (if you only use the get method), or write-only (if you only use the set method)
•	Flexible: the programmer can change one part of the code without affecting other parts
•	Increased security of data

2.	Inheritance
In Java, it is possible to inherit attributes and methods from one class to another. We group the "inheritance concept" into two categories:

•	subclass (child) - the class that inherits from another class
•	superclass (parent) - the class being inherited from

To inherit from a class, use the extends keyword.

3.	Polymorphism
Polymorphism means "many forms", and it occurs when we have many classes that are related to each other by inheritance.
Inheritance lets us inherit attributes and methods from another class. Polymorphism uses those methods to perform different tasks. This allows us to perform a single action in different ways.

4.	Abstraction
Data abstraction is the process of hiding certain details and showing only essential information to the user.
Abstraction can be achieved with either abstract classes or interfaces 

The abstract keyword is a non-access modifier, used for classes and methods:

Abstract class: is a restricted class that cannot be used to create objects (to access it, it must be inherited from another class).

Abstract method: can only be used in an abstract class, and it does not have a body. The body is provided by the subclass (inherited from).
An abstract class can have both abstract and regular methods:

// written by SADIKI SULTAN MNDEME	210210221326
