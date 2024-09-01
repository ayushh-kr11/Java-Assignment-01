# Java-Assignment-01

## Q1. When was java develope and who is the inventor of java? Why we use java for programming?

** 
Java was developed in 1995 by a team led by James Gosling at Sun Microsystems. The development of Java started in 1991 under the project name "Oak," but it was later renamed "Java" when it was officially released. Java is used for programming because it is platform independent, object-oriented, and has a vast library of APIs and tools.  **

## Q2. What are the features of java.
** 
Java has features like Platform-Independent, Object-Oriented, dynamic memory allocation that make it a widely-used programming language. 
**

## Q3. what is JDK, JRE, JVM?
**
JDK (Java Development Kit): The JDK is a software development kit that includes tools and libraries necessary for developing Java applications. It contains the Java compiler, JRE, and other development tools like debuggers and profilers.

JRE (Java Runtime Environment): The JRE provides the necessary libraries, JVM, and other components to run Java applications.

JVM (Java Virtual Machine): The JVM is the engine that runs Java bytecode. It interprets or compiles the bytecode into machine code that can be executed on the host machine. The JVM ensures that Java programs can run on any platform, making Java platform-independent.
**

## Q4. what is the structure of java program. write a program to print hello world.
**
The structure of a Java program consists of Package Declaration (optional), Import Statements (optional), a class with a main method.
**
```Java
public class assignment{

	public static void main(String[] args) {

		System.out.println("Hello World!");

	}

}
```

## Q5. Define Variables in java. Explain different scope of variable.
**
In Java, a variable is a container that holds data that can be used and manipulated within a program. Each variable has a data type, which defines the type of data it can store.

### Different Scopes of Variables in Java
### Local Variables
Variables declared inside a method, constructor, or block. They are accessible only within the method, constructor, or block where they are declared. They are created when the method or block is entered and destroyed when it exits.

### Instance Variables
Variables declared inside a class but outside any method, constructor, or block.
They are accessible throughout the class, and each object of the class has its own copy of the instance variables.

### Class Variables 
Variables declared inside a class with the static keyword. They are shared among all instances of the class. They are accessible throughout the class and can be accessed without creating an object of the class.

**

## Q6. Define data types in java.
**
 In Java, data types are the categories of values that a variable can hold. There are primitive data types (int, double, boolean, etc.) and reference data types (String, Array)
**

## Q7. What is type casting in java?
** 
Type casting in Java is the process of converting a value of one data type to another data type. There are two types of type casting: implicit and explicit.
**

## Q8. Write a program to add two number by taking input from user.
Here is a program to add two numbers by taking input from the user:
```java

public class assignment {

	public static void main(String[] args) {
		
		int a = 11;
		int b = 11;
		int c = a + b;
		System.out.println(c);

	}

}

```
## Q9. Define operator and its type?
**
In Java, an operator is a symbol that performs operations on variables and values. Operators are essential in programming for manipulating data and variables to achieve specific results.
#### Arithmetic Operators = (+, -, *, /, %)
#### Relational Operators = (==, !=, >, <, <=, >=)
#### Logical Operators = (&&, ||, !)
#### Bitwise Operator = (&, |, ^, ~)
**
## Q10. Write a program individually to perform operators operation.

``` Java

public class assignment {
    public static void main(String[] args) {
        int a = 10, b = 5;
        boolean x = true;

        //Arithmetic Operator
        System.out.println("Addition: " + (a + b));    
        System.out.println("Subtraction: " + (a - b));  

        //Relational Operators  
        System.out.println("a == b: " + (a == b));      
        System.out.println("a != b: " + (a != b));

        //Logical Operators 
        System.out.println("!x: " + (!x));  

        //Bitwise Operator
        System.out.println("a & b: " + (a & b)); 
        System.out.println("a | b: " + (a | b));      
        System.out.println("a ^ b: " + (a ^ b)); 
    }
}

```