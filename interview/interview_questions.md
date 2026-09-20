# About myself #
`Introduce about yourself ?`

`Answer: `Good morning, afternoon sir/ms A, my name is Khoan from Binh Dinh province. I graduated with a Bachelor's degree in Software Engineering from  FPT University. And I'm very excited to apply for the Java Junior position today

--- 

`What are your long-term goals?`

`Answer: `Having a good skills.

---

# General about Java #
`What is the difference between final, finally, and finalize()?`

`Answer: `
- final is a keyword used to restrict changes. A final variable cannot be reassigned, a final method cannot be overridden, and a final class cannot be inherited.
- finally is a block used in exception handling that always executes, whether an exception occurs or not, usually for cleanup tasks.
- finalize() was a method called by the Garbage Collector before destroying an object, but it has been deprecated since Java 9 and is no longer recommended.

---

# JVM, JRE, JDK #
`What are JDK, JVM and JRE?`

`Answer: `
- **JVM (Java Virtual Machine):** virtual machine convert java byte code into native machine code so the operating system can execute it. JVM makes Java “Write once, run anywhere”
=> JVM executes Java program.
- **JRE (Java Runtime Environment):** provide everything needed to run a Java application. It contains JVM and core class libraries, supporting files.
=> JRE runs Java program. (run here is prepare environment for running, not running)
- **JDK (Java Development Kit):** is a software development kit to build Java applications. It includes JRE for running code, development tools like Java compiler (javac), debugger,..
=> JDK develops Java program. (develop here is create new, debug, test, run,...)

---

# 4 principles of OOP #
`What are the 4 principles of OOP?`

`Answer: `There are 4 principles of OOP
- **encapsulation** is the bundling of data and the methods that operate on that data into a single unit, while restricting direct access to some of the object's internal state by access modifiers like private, protected or using getter/setter.
- **abstraction** means hiding implementation details and showing only the essential features of an object
- **inheritance** allows one class to reuse properties and behavior of another class
- **polymorphism** means one interface, many implementations. => overriding and overloading

---

`Can Java support multiple inheritance?`

`Answer: `No, Java does not support multiple inheritance for classes => diamond problem ( a class inherits from two different parents that share a common ancestor)

---

`What is method overloading vs method overriding?`

`Answer: `
- **Method overloading** allows multiple methods with the same name but different parameters within a single class, resolved at compile-time 
- **Method overriding** allows a child class to provide specific implementation for a method already defined in íts parent class, resolved at runtime.

---
