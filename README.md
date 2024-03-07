## java interview Questions
1 . **Name some Default packages in jdk And Explain what they do in brief** ?

the JDK kit include mny default packages that provide useful functionality for java developers. some of the default packages are.

java.lang - this package contains fundamental classes and interfaces that are essential to the java language for e.g object class in this package which is the root of the java class
java.util - this java class contains collection framework which provides a set of classes and interfaces

2 . **What are the relational operators** ?
-  '==': The equal to operator.
-  '!=': The not equal to operator.
-  '>' : The greater than operator.
-  '<' : The less than operator.
-  '>=': The greater than or equal to operator.
-  '<=': The less than or equal to operator.


3 . **Why do constructors not return values?** ?

Constructors are not meant to return a value because they are not methods. They are called automatically when an object is created, and their job is to initialize the object's state.
If a constructor were to return a value, it would be unclear what that value would represent. It would not be the object itself, because the object has already been created. It could not be a reference to the object, because the object is already in scope.

3 . **Can a class be marked final in Java** ?

Yes, a class can be marked final in Java using the final keyword. Here's what it means yawff
Making a class final:
-  Prevents inheritance: When a class is declared final, it cannot be extended by other classes. This ensures that the class definition and behavior remain unchanged and cannot be modified by subclasses.
-  Enforces immutability: If all the fields (instance variables) within a final class are also declared final, the class becomes immutable. This means the object's state cannot be changed after creation, making it thread-safe and potentially improving performance.


3 . **What is encapsulation? Explain with real life example.** ?

encapsulation in object-oriented programming (OOP) is a fundamental principle that focuses on bundling data (attributes) and the code that acts on that data (methods) together into a single unit, called a class. It's like creating a capsule that protects the internal workings and exposes only a controlled interface for interaction.


3 . **What is abstraction? Explain with real life example.** ?

Abstraction in object-oriented programming (OOP) is the process of focusing on the essential features and functionalities of an object while hiding the underlying implementation details. It allows you to create a simplified interface for users to interact with, without needing to understand the complex inner workings of the object.


3 . **What is inheritence? And types of inheritence.** ?  

In object-oriented programming (OOP), inheritance is a fundamental mechanism that allows you to create new classes (subclasses) by inheriting the properties and behaviors of existing classes (parent classes or base classes). It establishes an "is-a" relationship between the classes.
Types of Inheritance in Java:
-  Single Inheritance: A subclass inherits from one parent class. This is the simplest and most common type of inheritance.
-  Multilevel Inheritance: A subclass inherits from another subclass, which itself inherits from another base class, forming a chain of inheritance.
-  Hierarchical Inheritance: Multiple subclasses inherit from a single parent class, creating a hierarchy of related classes.
-  Multiple Inheritance: (Not supported directly in Java) A subclass inherits from multiple parent classes. This can lead to complexity and ambiguity, so Java and other languages like C++ use alternative approaches like interfaces to achieve similar functionality.
-  Hybrid Inheritance: A combination of different inheritance types, such as multilevel and hierarchical inheritance, within the same class hierarchy.

3 . **What is Polymorphism? And types of Polymorphism.** ?  

Polymorphism in object-oriented programming (OOP) is the ability of objects of different classes to respond differently to the same method call, based on their specific type. It allows for flexible and dynamic behavior in your programs, making them more adaptable and reusable.

-  Compile-time Polymorphism (Method Overloading):
   - Occurs when multiple methods in the same class have the same name but different parameter lists.
   - The compiler determines which method to call based on the number, type, and order of the arguments provided at compile time.
