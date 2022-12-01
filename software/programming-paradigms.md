# Programming Paradigms

## **About**

* A paradigm simply means a way of thinking.
* Programming paradigms include procedural, object orientated, assembly, functional and declarative.
* Most programming languages and paradigms are said to be “Turing complete.”
* This means that a language is able to solve all the problems a computer is able to solve.
* Some problems are better suited to being solved in a certain paradigm.
* This makes languages written in certain paradigms better suited to solving certain problems.

## **Procedural**

* One of the most common procedural paradigms in use.
* Sometimes referred to as imperative languages. This means to give an order.
* Tells a computer what to do step by step.
* Includes:
  * Sequence
  * Selection
  * Iteration
  * Recursion
  * Data types
  * Data structures
  * Abstract data structures such as stack and queues
* It uses modular techniques to split large problems into manageable chunks.

## **Assembly Language**

* Assembly languages are known as low level languages.
* Low level instruction - opcode + operand.
* Each type of processor has its own unique instruction set of low level assembly codes available to it.
* This means that an assembly level language written for one processor will not work on another.
* As assembly language is translated directly into machine code, these instructions sets allow us to represent the actual binary 1s and 0s by using short codes known as mnemonics.
* This is so we don't actually have to remember or code the actual binary values themselves.

## **Functional**

* Languages such as Hascal.
* Programs consist of functions that accept data and return data.
* Used in big data, the concept of manipulating huge amounts of data.

## **Declarative**

* Supported by languages such as SQL, where you write statements that describe the problem to be solved, and the language implementation decides the best way of solving it.
* SQL is a standard language used to read/write from/to databases.
* SQL is a declarative language (this means that you tell it what you want it to do, you don't have to tell it how to do it).
* In SQL, you write statements declaring what we want from the database.

## **Object Orientated Programming (OOP)**

### **Object Orientated Languages**

* Object oriented programming relies on objects in the real world being represented or classified and then every object identified being placed in its own class.
* A class is like a template - we use it to set out and define what attributes and methods an object of a certain type should have.
* This class is not an actual object itself, it's just a cutting tool to make sure that every object we make from that class looks the same.
* This is one of the major benefits of OOP.
* When we want to create an actual copy or an “instance” of a class we can use a single line of code to create it using the word “new.”
* This in OOP is called instantiation: “The process of creating an object from a class template.”
* Every language which implements OOP has its own syntax and way of doing it.

### **Object Orientated Programming**

In OOP, you can use inheritance to quickly and easily reuse code and then extend the attributes and methods without affecting the original code.

* For example, if you needed to make an employee class, an employee is still a person, but requires more information such as an NI number.
* You do not rewrite all the code, we simply create a class that inherits all the details of the person class and then adds the extra attributes and methods needed. This results in a class and a subclass.
* Overriding happens when a method in a subclass shares the same name as a method further up the object tree.
* The overridden method takes precedence and replaces the method inherited form the superclass.
* Using the super prefixes overrides overriding.

### **Encapsulation**

The protection of the attributes and methods of an object so that they can’t be accessed or altered by other objects.

This concept allows you to completely protect the data associated with each object.

It can’t be accidentally altered by another part of the program without using the code you provide thus this keeps you, the programmer, in control.

* Other objects (instantiations of a class) are prevented from directly accessing the data of attributes inside an object other than by going through or using the method that are provided.
* In OOP, we use the keyword private to show that the following attribute is only accessible from within the class.
* Any attempt to access or change a private attribute outside of the class will result in error.
* The method must be used instead.
* This now means that we must make sure to provide a method in the class in order to allow other parts of the program to alter one of the private attributes.
* This method therefore has to be public.
* Because it is public, it can be called by other parts of the program and thus it will be able to change the internal, private attribute.
* However, you now have complete control as you're the one writing the code in that method which means the attributes can only be changed in the way you specify.

### **Polymorphism**

* Polymorphism makes sure that when a symbol or function have different meanings the right meaning is chosen based on the context.
