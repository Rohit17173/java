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


3 . **What is encapsulation? Explain with real life example.** ?
  
