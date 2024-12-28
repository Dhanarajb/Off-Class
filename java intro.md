# What is Java?

Java is a high-level programming language that is easy to learn and widely used for building software applications. It was created by Sun Microsystems in 1995 and is now owned by Oracle. One of the main features of Java is its platform independence, meaning that Java code can run on any operating system, such as Windows, Mac, or Linux, without needing to be rewritten.

## Key Features of Java:
- **Works on any platform**: Java code can run on any operating system without needing to be changed.
- **Object-Oriented**: Java uses a style of programming that helps organize code and make it reusable.
- **Reliable and Safe**: Java has built-in tools to make sure the code runs smoothly and securely.
- **Multithreading**: Java can run multiple tasks at the same time, making it more efficient.
- **Big Library**: Java has a huge collection of ready-to-use tools and functions to make programming easier.

## Real-Life Example:
### Android Apps:
Android Development: Java is one of the main languages used to build Android apps. When you download a new app from the Google Play Store, it’s usually written in Java or Kotlin, which works seamlessly with Java. Java allows the app to work on all Android phones, regardless of the brand or model.

## Conclusion:
Java is a popular programming language because it's easy to use, can run on any computer or phone, and is perfect for building everything from websites to mobile apps.


---
# Why Java?

Java is a very popular programming language for several important reasons. Let's break them down:

## 1. Object-Oriented Programming (OOP)

- **What it means**: Java uses the concept of objects and classes. An object is like a real-world thing (like a car or a person), and a class is like a blueprint that defines what an object will look like and what it can do.

- **Why it's good**: By organizing code into objects and classes, Java makes it easier to manage large projects. You can reuse code, so you don't have to rewrite the same thing again. It also helps break down complex tasks into smaller, easier-to-understand parts. This leads to cleaner, more organized code that’s easier to maintain and expand.

## 2. Platform Independence

- **What it means**: Java code is turned into a special format called bytecode when it’s written. This bytecode can run on any computer or device that has a Java Virtual Machine (JVM) installed, no matter what type of operating system (Windows, Mac, Linux, etc.) it’s using.

- **Why it's good**: This is why Java is called "write once, run anywhere." You can write your program once, and it will work on any computer or device, without having to rewrite or change the code for each platform. It saves time and makes your program more flexible.

## 3. Security

- **What it means**: Java comes with built-in features to keep your code and data safe. It has things like automatic memory management (to avoid memory errors), encryption (to protect sensitive data), and secure class loading (to make sure harmful code doesn’t get executed).

- **Why it's good**: These security features make Java a great choice for building secure applications, such as online banking systems, e-commerce websites, and anything that deals with sensitive personal data. Java helps protect against things like hacking or accidental data loss.

## 4. Multithreading

- **What it means**: Java can do many tasks at the same time using multithreading. This means a program can perform multiple actions at once, like downloading files and playing music at the same time, without freezing or slowing down.

- **Why it's good**: Multithreading improves the performance of your programs, especially those that need to respond quickly, like video games, media players, or communication apps (like chat apps). It helps make your programs more efficient and faster.

## 5. Large Ecosystem and Libraries

- **What it means**: Java has a large collection of pre-written code (called libraries) that developers can use to perform common tasks. For example, Java has libraries for connecting to databases, managing user interfaces, or handling networks.

- **Why it's good**: These libraries save time by providing ready-made solutions for common problems. Instead of writing everything from scratch, developers can use these libraries to focus on the unique parts of their project, making development faster and easier.

Real-time Example: Banking Applications

Java is commonly used in online banking systems because it provides strong security features that help protect sensitive information. Here's how it works:

Security of User Data: Java helps ensure that important information like your bank account number, passwords, and transaction details are kept safe. It uses encryption, which is like putting your data in a locked box, so only authorized users can access it.

Secure Transactions: When you make a payment or transfer money online, Java helps secure the transaction by making sure that no one can tamper with the data while it’s being sent over the internet. This prevents fraud and ensures that your financial information stays private.

---
# Where is Java Used?

Java is a versatile programming language, used in many areas of technology. Here’s where Java is commonly used:

## 1. Web Applications (Backend)
- **What it means**: Java is often used to build the backend of websites and web applications. This means Java runs the server-side tasks, like processing requests, interacting with databases, and sending data to the frontend (what users see).
- **Real-world example**: Large websites, like banking systems or e-commerce sites, use Java to make sure everything works behind the scenes smoothly.

## 2. Mobile Applications (Android)
- **What it means**: Java is the main language used for building Android apps. These are the apps that run on smartphones and tablets.
- **Real-world example**: Many popular Android apps, such as Instagram and WhatsApp, are built using Java.

## 3. Embedded Systems
- **What it means**: Java is also used in small devices like printers, smart TVs, and Internet of Things (IoT) devices. These devices need to run specific tasks, and Java is often used because it's lightweight and efficient.
- **Real-world example**: Java can be found in things like smart home devices and certain wearable technology.

## Real-time Example:

### Online Shopping Websites
- **How it's used**: Websites like Amazon and eBay use Java for the backend. Java handles important tasks like managing inventory, processing payments, and ensuring user accounts are secure.

### Enterprise Applications
- **How it's used**: Large companies use Java to build systems that manage resources, track inventory, and handle business functions, like ERP (Enterprise Resource Planning) systems.

Java is everywhere, from the websites you shop on, to the apps you use, and even to the small devices in your home.
-----
# When Should You Use Java?

You should choose Java when:

## 1. You need platform independence
- **What it means**: If you want your program to run on different operating systems (like Windows, Mac, Linux) without changes, Java is a great choice because it works anywhere.

## 2. You’re building a large, complex application
- **What it means**: Java is ideal for developing big, complex systems that require scalability and reliability, such as customer management or financial systems. 

## 3. Security is important
- **What it means**: Java has strong security features to protect sensitive data, making it the right choice for building secure applications, like payment processing or online banking.

## Real-time Example:

### Enterprise Solutions
- **How it's used**: Companies such as banks and large retailers use Java to build systems that manage millions of transactions and sensitive data daily. For example, Java is used in CRM systems to store customer details and process orders.

### Online Games and Trading Systems
- **How it's used**: Java is used in high-speed trading platforms and large multiplayer online games because it can handle large amounts of data and transactions quickly and securely.

---
# How Java Works: From Source Code to Execution

Java works in a unique way that allows it to run on any device, anywhere. Let’s break down the process of how Java code is compiled, converted into bytecode, and executed by the Java Virtual Machine (JVM), using a simple "Hello World" program as an example.

---

## 1. **Writing the Java Code (Source Code)**

First, a Java programmer writes the source code, which is a simple text file. For example, here's a simple "Hello World" Java program:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
### What Happens?
- This code is written in **human-readable Java syntax**.
- It’s saved with the `.java` extension, like `HelloWorld.java`.
- This is **source code**, which needs to be translated into machine-readable instructions.

# 2. Compilation (Source Code to Bytecode)

Once the Java program is written, it must be compiled into bytecode. This is done using the Java Compiler (`javac`).

### What Happens?
- You run the `javac HelloWorld.java` command, which invokes the Java compiler.
- The compiler translates the `.java` file into bytecode and saves it as a `.class` file, like `HelloWorld.class`.
- The bytecode is a set of instructions that the JVM can understand and execute, but it's not tied to any specific operating system or hardware. It's platform-independent.

### Why Bytecode?
- **Platform Independence**: The bytecode is not specific to any operating system (Windows, Mac, Linux, etc.), so it can be run on any system that has a JVM.


# 3. Java Virtual Machine (JVM)

Now that the Java program is compiled into bytecode, it needs to be executed. The JVM comes into play.

### What Happens?
- The JVM is a special program that runs on the computer and knows how to interpret the bytecode.
- When you run the command `java HelloWorld`, the JVM loads the bytecode from `HelloWorld.class`.
- The JVM then translates the bytecode into machine code (binary code) that the computer's processor understands. This machine code is platform-specific (it depends on the OS and hardware), but the JVM handles the translation for you.


# 4. Execution (Bytecode to Machine Code)

### What Happens?
- The JVM executes the bytecode line by line, translating each instruction into machine code.
- For example, the command `System.out.println("Hello, World!");` sends an instruction to the JVM to print "Hello, World!" to the screen.
- The JVM translates this into the appropriate machine instructions (binary code) that will make the operating system display the message.

# 5. Memory Management and Garbage Collection

While the program is running, the JVM also manages memory. It allocates memory for objects and handles garbage collection, which means it automatically cleans up memory that is no longer in use.

### What Happens?
- If your program creates objects or uses resources (like memory), the JVM will automatically free up the memory once the objects are no longer needed.
- This ensures that your program doesn’t use more memory than it should, avoiding crashes or memory leaks.


# Real-time Example: Java in Web Servers

Java is widely used in web servers like Tomcat or JBoss. Let’s say you're visiting an online shopping website:

The backend server of the website runs Java code to handle requests like:
- User logins
- Fetching product data from a database
- Processing payments

These Java applications are compiled into bytecode and executed by the JVM. The JVM ensures that the server can run smoothly regardless of the operating system (Windows, Linux, etc.) on which it is hosted.

### Platform Independence with Web Servers
When a user requests to view a product, the Java backend code processes this request:
- The bytecode is interpreted by the JVM.
- It translates into machine-specific code to retrieve product details.
- The machine code sends the data back to the user’s browser.

This shows the power of Java's platform independence, where the same bytecode works on various operating systems and hardware platforms.


# From Source Code to Bytecode and Machine Code

### Java Code → Bytecode:
1. **HelloWorld.java** is written by the programmer.
2. The Java compiler (`javac`) converts the source code into bytecode and saves it in a `.class` file.

### Bytecode → JVM → Machine Code:
1. The JVM takes the bytecode from `HelloWorld.class`.
2. The JVM translates the bytecode into machine code (binary format) that the computer can understand and execute.

### JVM Execution:
1. The JVM handles the execution of the program. 
2. For example, it translates `System.out.println("Hello, World!");` into machine code that instructs the computer to display the message on the screen.

# Summary of the Process:

### Compilation:
- Java source code → Bytecode (using `javac HelloWorld.java`).

### Execution:
- Bytecode → JVM → Machine Code (using `java HelloWorld`).

### JVM:
- Handles the translation and execution of the bytecode, memory management, and garbage collection.

This entire process is what makes Java platform-independent. The "write once, run anywhere" philosophy means that once the Java program is compiled into bytecode, it can run on any system with a JVM, regardless of the operating system or hardware.

<img width="167" alt="Screenshot 2024-12-14 at 12 43 18 PM" src="https://github.com/user-attachments/assets/8fa77e2e-e047-41f0-b1c5-9f5aa62fc75b" />

---
# Step-by-Step Java Installation

## Step 1: Download JDK
1. Open your browser and go to the official [Oracle Java Downloads page](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Select the appropriate JDK version for your operating system (Windows, macOS, or Linux).
3. Click on the download link and accept the license agreement.

## Step 2: Install JDK
1. Locate the downloaded JDK installer file on your system (e.g., `jdk-x.x.x-windows-x64.exe` for Windows).
2. Double-click the installer to start the installation process.
3. Follow the on-screen instructions:
   - Click **Next**.
   - Choose the installation directory (default is usually fine, but you can change it if needed).
   - Click **Install** to complete the process.

## Step 3: Configure Environment Variables (Windows Only)
1. Open the Start menu, search for **Environment Variables**, and click on **Edit the system environment variables**.
2. In the **System Properties** window, click on **Environment Variables**.
3. Under **System Variables**, find `Path`, and click **Edit**.
4. Add the path to the `bin` directory of your JDK installation (e.g., `C:\Program Files\Java\jdk-x.x.x\bin`).
5. Click **OK** to save the changes.

## Step 4: Verify Installation
1. Open the terminal (Command Prompt on Windows or Terminal on macOS/Linux).
2. Type the command:
   ```bash
   java -version
   ```
   This should display the installed Java version.
3. Type the command:
   ```bash
   javac -version
   ```
   This should display the version of the Java compiler.

------
# Understanding JVM, JDK, and JRE

### 1. **JVM (Java Virtual Machine)**
**What**: The **JVM** is a virtual machine that allows Java programs to run on any device or operating system by interpreting compiled Java bytecode. It is platform-independent and provides an environment for Java applications to execute.
  
- **Why**: It ensures that Java code is portable, meaning it can run on any platform that has a JVM implementation. This is the cornerstone of Java’s “write once, run anywhere” philosophy.
  
- **When**: The JVM is used **whenever** Java bytecode needs to be executed. After compiling the Java source code, the JVM runs it on the target machine.

- **Where**: The JVM is installed on the **end-user’s machine** or the **server** where the Java program will run. It is typically included with the JRE.

- **How**: The JVM takes the bytecode, interprets it, and translates it into machine-specific code for execution on the hardware.

#### Visualization:
Think of the JVM as a **translator**. Your Java program (written in Java language) is like a message in English. The JVM translates this message into a format that your computer can understand (machine code).

---

### 2. **JDK (Java Development Kit)**
- **What**: The **JDK** is a software development kit that includes everything you need to develop Java applications: the compiler, the JVM, libraries, and tools to build, debug, and deploy Java applications.
  
- **Why**: If you’re a developer, the JDK provides all the tools necessary to write, compile, and debug your Java programs. Without the JDK, you can't write or compile Java code.
  
- **When**: You use the **JDK** when you are **developing** Java programs (writing and compiling source code).

- **Where**: The JDK is installed on a **developer's machine** to facilitate the creation of Java applications.

- **How**: The JDK includes a compiler (`javac`) to compile Java code into bytecode, which can then be executed by the JVM. It also includes other tools like debuggers and profilers to aid in the development process.

#### 3. **JRE (Java Runtime Environment)**
- **What**: The **JRE** is a runtime environment that allows you to run Java applications. It includes the JVM and essential libraries but does not provide development tools like the JDK.

- **Why**: The JRE is needed to run Java applications. It contains the JVM that interprets bytecode and provides the necessary libraries for Java programs to function.

- **When**: You need the **JRE** when you want to **run** Java applications but not develop them (no need for compiling).

- **Where**: The JRE is typically installed on **end-user machines** or **servers** where Java applications will be executed.

- **How**: The JRE includes the JVM, which runs Java bytecode, and the set of libraries that the Java program depends on for its execution.
#### Contains:
- **JVM**: The virtual machine that runs your Java code.
- **JRE**: The runtime environment that allows you to run Java programs.
- **Development Tools**: Compilers, debuggers, and other tools for writing Java code.

#### Visualization:
Imagine you’re going to bake a cake. The **JDK** is like a complete kitchen with all the tools (baking pan, oven, etc.) and ingredients (flour, sugar, etc.) you need to bake the cake (develop Java code). The **JVM** is the oven that actually bakes the cake (runs your code), and the **JRE** is the ingredients to make the cake (provides the environment to run the code).


---

## Scenario: A Simple Java Program

Let’s say you are a developer who has written a Java program to calculate the sum of two numbers.

1. **Step 1**: You write your Java code (source code).
   ```java
   public class Sum {
       public static void main(String[] args) {
           int a = 5;
           int b = 10;
           System.out.println("Sum: " + (a + b));
       }
   }
   ```
 2. **Step 2**: Compile the Java Code Using the JDK
The compiler (part of the JDK) converts the Java code into bytecode (a .class file).  
   ```javac Sum.java
```
3. **Step 3**: Execute the Bytecode with the JVM
The JVM takes the bytecode and executes it on your machine. The JVM translates the bytecode into machine code that your system can execute.
 ```java Sum
```
```Sum: 15
```
If you just want to run this program (without modifying it), you would need the JRE, as it contains the JVM and libraries required for execution.
If you want to develop the program (write and compile it), you would need the JDK.
## **Comparison of JDK, JVM, and JRE**

- **JDK:** Includes everything you need to develop **and** run Java applications (both the **JRE** and tools like the **compiler**).
- **JRE:** Includes everything you need to **run** Java applications (just the **JVM** and libraries).
- **JVM:** The virtual machine that executes the **bytecode** and translates it into **machine code** for your system.

## **Summary with Simple Example**

Let’s say you want to create a simple **Java-based Calculator** app:

- **JDK** is your toolbox. You use it to **write** the Java code, **compile** it, and **debug** any issues.
- **JVM** is like the **engine** of your app. It takes the compiled bytecode and runs it on your computer, so you can use the app.
- **JRE** is like a **ready-made engine** that only helps you run apps that are already compiled. If you only want to **use** the Calculator app (but not create it), you'd need the **JRE**, not the full **JDK**.

## **How These Work Together:**
1. You write the **Calculator app code** (Java file).
2. You compile the code using **JDK** (which creates bytecode).
3. The **JVM** then runs the bytecode, executing the app on your computer.
4. If you're just running the app, you'd need the **JRE** installed, which includes the **JVM**.

### **In Summary:**
- **JDK = Full toolbox for Java development** (including compiler and JVM).
- **JRE = Environment for running Java programs** (includes JVM).
- **JVM = The engine that runs the Java program** (translates bytecode into machine code).


----
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
# Java HelloWorld Program Explanation

## 1. `public`
**Meaning**: `public` is an access modifier. It defines the visibility or accessibility of the class, method, or variable.

**Elaboration**: 
- When you declare a class or method as `public`, it means that it can be accessed from anywhere. In this case, it means that the `HelloWorld` class can be accessed by other classes, regardless of where those classes are in the codebase.
- In the context of the main method: `public` ensures that the `main` method can be accessed by the Java Virtual Machine (JVM) to start the program when it is executed.

---

## 2. `class`
**Meaning**: `class` is a keyword in Java that defines a class.

**Elaboration**: 
- A class in Java is a blueprint for creating objects (instances). It contains fields (variables) and methods (functions) that define the behavior of the objects. 
- In this case, the class is named `HelloWorld`.
- In the context of `HelloWorld`: This keyword signifies that we're defining a class named `HelloWorld`, and everything inside the curly braces `{}` will belong to this class.

---

## 3. `HelloWorld`
**Meaning**: `HelloWorld` is the name of the class.

**Elaboration**:
- In Java, class names follow the PascalCase convention, where the first letter of each word is capitalized. The name `HelloWorld` is what identifies the class, and it will be used when referring to this class or creating an object of this class.
- In the context of the program: `HelloWorld` is the class that contains the main method. When you run the program, the JVM will look for the `HelloWorld` class and the `main` method within it.

---

## 4. `{` and `}`
**Meaning**: These curly braces `{}` are used to define the body of the class and method.

**Elaboration**:
- In Java, blocks of code, such as classes, methods, and loops, are enclosed in curly braces. These braces indicate where a particular section of code begins and ends.
- In the context of the program: The first set of curly braces `{}` marks the beginning and end of the `HelloWorld` class, while the second set `{}` within it marks the beginning and end of the `main` method.

---

## 5. `public static void main(String[] args)`
**Meaning**: This is the entry point of a Java application. It’s the method that is executed when you run the Java program.

**Elaboration**:
- `public`: As mentioned earlier, this makes the method accessible from outside the class, specifically by the JVM when executing the program.
- `static`: This means that the method belongs to the class itself rather than to instances (objects) of the class. You don’t need to create an instance of the `HelloWorld` class to run the `main` method.
- `void`: This means that the method does not return any value. It is a return type that signifies no value will be returned after execution.
- `main`: This is the name of the method. In Java, the `main` method is special because it is the entry point of any Java application. It’s where execution begins.
- `String[] args`: This is an array of command-line arguments that can be passed when running the program. `String[]` represents an array of String objects. `args` is the name of the variable that holds these arguments. You can pass values to the program when running it from the command line.

In the context of the program: The `main` method is called automatically by the JVM when you run the `HelloWorld` program. It is the starting point where the program begins execution.

---

## 6. `System.out.println("Hello, World!");`
**Meaning**: This statement prints text to the console.

**Elaboration**:
- `System`: This is a built-in Java class in the `java.lang` package. It provides various utility functions, such as accessing standard input, output, and error streams.
- `out`: This is a static field of the `System` class that refers to the standard output stream (usually the console or terminal).
- `println`: This is a method of the `out` object. It stands for "print line," and it prints the specified text or value followed by a new line.
- `"Hello, World!"`: This is a string literal that specifies the text to be printed. The quotation marks indicate that it is a string.

In the context of the program: The statement `System.out.println("Hello, World!");` tells the program to print `"Hello, World!"` to the console when the program runs. The `println` method also moves the cursor to the next line after printing the text, so if you add more print statements, each will appear on a new line.

---

## 7. `;`
**Meaning**: This is the semicolon symbol, used to mark the end of a statement in Java.

**Elaboration**: 
- Every statement in Java, such as variable declarations, method calls, and assignments, must be terminated with a semicolon. It indicates the end of a complete statement.
- In the context of the program: The semicolon marks the end of the `println` statement.

---

## Putting It All Together
- `public class HelloWorld`: This defines the class `HelloWorld` as public and marks the start of the class body.
- `public static void main(String[] args)`: This defines the `main` method, the entry point of the Java program.
- `System.out.println("Hello, World!");`: This prints `"Hello, World!"` to the console.

----
# Understanding Data Types in Java
# What is a Variable?

A **variable** is like a box or container where you store data. Every variable has:

1. **A name** – so you can refer to it later.
2. **A data type** – which defines what kind of data it will hold (like numbers, text, etc.).
3. **A value** – the actual data inside the variable.

### Example:

```java
int age = 25;
```
- ```age``` is the variable name.
- ```int``` is the data type (which tells Java that age will store a whole number).
- ```25``` is the value stored in the variable.

# Why Do We Need Data Types?

**Data types** tell Java what kind of data you are working with and help the program know how to process that data. Without data types, Java wouldn't know how to treat the information.

### Examples:
- You **can’t store text** in a number variable.
- You **can’t perform mathematical operations** on text without converting it to a number first.

### Without data types:

```java
int age = "twenty";  // Error: You can't store text in an integer variable
```
```java
int age = 25;         // Correct: age is an integer
String name = "John"; // Correct: name is a string

```



---

### Two Main Categories of Data Types in Java

Java has two broad categories of data types:
1. **Primitive Data Types**  : These store simple values like numbers or a single character.
2. **Reference Data Types** : These store complex data like objects or arrays.

---

## 1. Primitive Data Types

Primitive data types are the most basic building blocks for storing data. Java has 8 types of primitive data types. Let’s look at each one with examples.

### a) byte
- **What is it?** A tiny number that can range from -128 to 127.
- **Size:** It takes up only 1 byte of memory.
- **Example:** 
  ```java
  byte age = 25;
- Use: It’s used when you need to store very small numbers and save memory.

### b) short

- **What is it?**  A slightly larger number, ranging from -32,768 to 32,767.
- **Size:** Takes up 2 bytes of memory.
- **Example:**
  ```java
  short temperature = -5;
- Use: Useful for small numbers, and when memory is a concern.

### c) int

- **What is it?** A common number type for whole numbers.
- **Size:** 4 bytes (32 bits).
- **Example:**
  ```java
  int distance = 100000;
- Use: Most commonly used for numbers that don’t have decimals.

### d) long
- **What is it?** A big number.
- **Size:** Takes up 8 bytes.
- **Example:**
  ```java
  long population = 7800000000L;
- Use: Used when numbers are too large to fit in an int.

### e) float
- **What is it?** A number with decimals (but not super precise).
- **Size:** Takes up 4 bytes.
- **Example:**
  ```java
  float price = 9.99f;
- Use: Used for decimal numbers when you don’t need a lot of precision.

### f) double
- **What is it?** A more precise decimal number.
- **Size:** Takes up 8 bytes.
- **Example:**
  ```java
  double salary = 1500.75;
- Use: The default data type for decimal numbers in Java.

### g) char
- **What is it?** A single character.
- **Size:** Takes up 2 bytes.
- **Example:**
  ```java
  char grade = 'A';
- Use: Used to store a single character, like a letter or number.

### h) boolean
- **What is it?** A value that can only be true or false.
- **Size:** Takes up 1 byte.
- **Example:**
  ```java
  boolean isAdult = true;
- Use: Used to represent a decision, yes/no, or true/false situation.


### 2. Reference Data Types
Reference data types are used to store complex data structures. Instead of holding actual data, they store the address (or reference) to the memory location where the data is stored.

#### a) String
- **What is it?** A sequence of characters, like words or sentences.
- **Example:**
  ```java
  String name = "John Doe";
- Use: Used for text (e.g., names, addresses, or any words).

#### b) Arrays
- **What is it?** A list of values of the same type.
- **Example:**
  ```java
  int[] numbers = {1, 2, 3, 4, 5};
- Use: Used to store multiple values in a single variable. For example, you could store multiple numbers in an array.

#### c) Objects
- **What is it?** A collection of data and functions that belong to a specific entity or class.
- **Example:**
  ```java
  Car myCar = new Car();
- Use: Used for creating and storing complex data structures. Objects are the backbone of object-oriented programming (OOP), where you create entities like Car, Person, or Book.

-----
### Why Are Data Types Important?

- **Memory Management:** Different data types take up different amounts of memory. For example, a `byte` takes only 1 byte, but an `int` takes 4 bytes. Choosing the right data type can save memory.
- **Type Safety:** Data types prevent mistakes. For example, you can’t accidentally store text (`String`) in a variable meant to hold numbers (`int`). It helps keep your program from errors and bugs.
- **Performance:** Using the correct data type helps your program run faster and use resources (like memory) efficiently. For example, using `byte` instead of `int` for small numbers can improve performance.

### Real-Life Example:
Imagine you are setting up a bank account system where you need to store the following details:

- **The name of the account holder:** Use `String`
- **The account balance:** Use `double` (because it has decimal places)
- **The account number:** Use `int` (whole number)
- **Whether the account is active or not:** Use `boolean` (true or false)

Here’s how you might write it:
```java
public class BankAccount {
    String accountHolder = "John Doe";  // String for text
    double balance = 5000.75;  // double for decimal values
    int accountNumber = 123456789;  // int for whole numbers
    boolean isActive = true;  // boolean for true/false
}
```
This simple example shows how different types of data are stored and used in the real world!

### Summary:
- **Primitive Data Types** store basic values like numbers, characters, and true/false values.
- **Reference Data Types** store more complex data like text, arrays, and objects.
- **Data types** help us save memory, prevent errors, and make our programs run efficiently.
- By understanding data types, we can write better and more efficient code!

-------------

# Operators and Expressions in Java

## What Are Operators?

In programming, **operators** are symbols or words that perform operations on variables and values. They are used to manipulate data and variables in your program. Think of them as tools that help you do calculations, compare values, or even change the values of variables.

---

## Types of Operators in Java

Java has several types of operators that you will frequently use. Here’s an easy-to-understand breakdown:

### 1. Arithmetic Operators

These are the most basic operators that deal with mathematical operations like addition, subtraction, multiplication, etc.

- **Addition (`+`)**: Adds two values together.

```java
int sum = 10 + 5;  // sum = 15
```
- **Subtraction (`-`)**: Subtracts one value from another.
```java
int sub = 10 - 5;  // sub = 5
```
- **Multiplication (`*`)**: Multiplies two values.
```java
int mult = 10 * 5;  // mult = 50
```
- **Division (`/`)**: Divides one value by another.
```java
int div = 10 / 5;  // div = 2
```
- **Modulus (`%`)**: Gives the remainder of a division.
```java
int rem = 10 % 3;  // rem = 1
```


### 2. Relational (Comparison) Operators

These operators compare two values and return a boolean result (`true` or `false`).

- **Equal to (`==`)**: Checks if two values are the same.

```java
boolean result = 5 == 5;  // result will be true
```
- **Not equal to (`!=`)**: Checks if two values are different.
```java
boolean result = 5 != 3;
```
- **Greater than (`>`)**: Checks if one value is greater than the other.
```java
boolean result = 5 > 3;  // result will be true
```
- **Less than (`<`)**: Checks if one value is less than the other.
```java
boolean result = 5 < 10;  // result will be true
```
- **Greater than or equal to (`>=`)**: Checks if one value is greater than or equal to the other.
```java
boolean result = 5 >= 5;  // result will be true
```
- **Less than or equal to (`<=`)**: Checks if one value is less than or equal to the other.
```java
boolean result = 3 <= 4;  // result will be true
```
### 3. Logical Operators

Logical operators are used to combine multiple conditions and return a `true` or `false` result.

- **AND (`&&`)**: Returns `true` if both conditions are true.

```java
boolean result = (5 > 3) && (10 > 5);  // result will be true because both conditions are true
```
- **OR (`||`)**: Returns true if at least one condition is true.
```java
boolean result = (5 < 3) || (10 > 5);  // result will be true
```
- **NOT (`!`)**: Reverses the boolean value. If it’s true, it becomes false, and if it’s false, it becomes true.
```java
boolean result = !(5 < 3);  // result will be true because 5 is not less than 3
```

### 4. Assignment Operators

Assignment operators are used to assign values to variables.

- **Equal (`=`)**: Assigns a value to a variable.

```java
int x = 5;  // Assigns the value 5 to the variable x
```
- **Add and assign (`+=`)**: Adds a value to a variable and assigns the result back to the variable.
```java
x += 3;  // Equivalent to x = x + 3; Now x will be 8
```
- **Subtract and assign (`-=`)**: Subtracts a value from a variable and assigns the result back.
```java
x -= 2;  // Equivalent to x = x - 2; Now x will be 6
```
- **Multiply and assign (`*=`)**: Multiplies a variable by a value and assigns the result back.
```java
x *= 2;  // Equivalent to x = x * 2; Now x will be 12
```
- **Divide and assign (`/=`)**: Divides a variable by a value and assigns the result back.
```java
x /= 3;  // Equivalent to x = x / 3; Now x will be 4
```

### 5. Unary Operators

Unary operators operate on a single variable.

- **Increment (`++`)**: Increases the value of a variable by 1.

```java
int x = 5;
x++;  // x is now 6
```
- **Decrement (`--`)**: Decreases the value of a variable by 1.
```java
int count = 5;
count--;  // count will be 4
```
### 6. Ternary Operator

The ternary operator is a shortcut for `if-else` statements. It allows you to write a simple condition check in one line, with three parts: 

- A **condition**
- A **result if the condition is true**
- A **result if the condition is false**

The syntax is:

```java
int age = 20;
String result = (age >= 18) ? "Adult" : "Minor";  // result will be "Adult"

```
### What Are Expressions?

An expression is a combination of variables, constants, operators, and functions that are evaluated to produce a value. Expressions are used in Java to perform operations within statements, such as performing calculations or making comparisons.

In simple terms, an expression is something that the program evaluates to give you a result.

#### Examples of Expressions:

1. **Simple Arithmetic Expression:**

```java
int sum = 5 + 3;  // The expression 5 + 3 is evaluated, and the result (8) is assigned to the variable sum
```

2. **Relational Expression:**
```java
boolean isGreater = (5 > 3);  // isGreater will be true
```

3. **Logical Expression:**
```java
boolean result = (5 > 3) && (10 < 20);  // result will be true
```
4. **Ternary Expression:**
```java
String message = (10 > 5) ? "Greater" : "Smaller";  // message will be "Greater"
```

### How Do Operators and Expressions Work Together?

Operators and expressions work hand-in-hand to perform operations and return results. Operators modify the data, while expressions group the operators and values together to form a complete operation.

In Java, an **expression** can consist of values, variables, operators, and function calls. The **operators** act on the values and variables within the expression to calculate the final result.

#### Example:

```java
int x = (5 + 3) * 2;
```
- Here, (5 + 3) is an expression that evaluates to 8, and 8 * 2 is another expression that evaluates to 16. The final result is assigned to the variable x.

### Why Are Operators and Expressions Important?

1. **Mathematical Calculations**: Operators help you perform mathematical operations, such as addition, subtraction, multiplication, and division. They allow you to manipulate numerical data in your programs.

2. **Making Decisions**: Logical and relational operators are used to compare values and make decisions in your program. For example, you can check if a condition is true or false, which helps control the flow of your program (e.g., using `if` statements).

3. **Efficient Code**: Understanding how operators and expressions work allows you to write more efficient, readable, and concise code. With the right operators and well-formed expressions, you can avoid redundancy and make your code easier to understand and maintain.

---

### Real-Life Example of Operators and Expressions:

Let’s say you're creating a simple program to check if someone qualifies for a discount at a store based on their age and the total amount of their purchase.

```java
int age = 25;
double purchaseAmount = 150.0;

boolean qualifiesForDiscount = (age >= 18) && (purchaseAmount > 100);
System.out.println("Qualifies for discount: " + qualifiesForDiscount);
```

- The relational operator >= checks if the age is 18 or older.
- The relational operator > checks if the purchase amount is greater than 100.
- The logical operator && ensures that both conditions must be true for the discount to apply

--------

# Control Statements (if, switch, loops) in Java

## 1. `if` Statement
The `if` statement is used to execute a block of code only if a specified condition is `true`. If the condition is `false`, the code inside the `if` block is skipped.

### Syntax:
```java
if (condition) {
  // code to execute if condition is true
}
```

### Scenario:
A student needs to check whether they have passed or failed based on their marks.

### Examples:

1. **Check if a student passes**
   ```java
   int marks = 80;
   if (marks >= 50) {
     System.out.println("Student has passed.");
   }
   ```

2. **Check if a number is positive**
   ```java
   int number = 5;
   if (number > 0) {
     System.out.println("The number is positive.");
   }
   ```

3. **Check if a number is even**
   ```java
   int num = 4;
   if (num % 2 == 0) {
     System.out.println("The number is even.");
   }
   ```

4. **Check age for voting eligibility**
   ```java
   int age = 18;
   if (age >= 18) {
     System.out.println("Eligible to vote.");
   }
   ```

5. **Check if a temperature is below freezing**
   ```java
   int temperature = -5;
   if (temperature < 0) {
     System.out.println("The weather is freezing.");
   }
   ```

## 2. `else` Statement
The `else` statement runs a block of code if the condition in the `if` statement is `false`.

### Syntax:
```java
if (condition) {
  // code if condition is true
} else {
  // code if condition is false
}
```

### Scenario:
A student is checking if they can enter a contest based on their age.

### Examples:

1. **Check if a student passes or fails**
   ```java
   int marks = 40;
   if (marks >= 50) {
     System.out.println("Student has passed.");
   } else {
     System.out.println("Student has failed.");
   }
   ```

2. **Check if a number is positive or negative**
   ```java
   int number = -3;
   if (number > 0) {
     System.out.println("The number is positive.");
   } else {
     System.out.println("The number is negative.");
   }
   ```

3. **Check if it's daytime or nighttime**
   ```java
   int time = 10;  // 10 AM
   if (time < 12) {
     System.out.println("Good Morning!");
   } else {
     System.out.println("Good Evening!");
   }
   ```

4. **Check if a person is eligible for a discount**
   ```java
   int age = 15;
   if (age >= 18) {
     System.out.println("Eligible for a discount.");
   } else {
     System.out.println("Not eligible for a discount.");
   }
   ```

5. **Check if it's freezing or not**
   ```java
   int temperature = 10;
   if (temperature < 0) {
     System.out.println("It's freezing.");
   } else {
     System.out.println("It's not freezing.");
   }
   ```

## 3. `else if` Statement
The `else if` statement allows you to check multiple conditions. It’s used when you need to test more than one condition in a sequence.

### Syntax:
```java
if (condition1) {
  // code if condition1 is true
} else if (condition2) {
  // code if condition2 is true
} else {
  // code if none of the conditions are true
}
```

### Scenario:
A person is checking if a number is positive, negative, or zero.

### Examples:

1. **Check if a number is positive, negative, or zero**
   ```java
   int number = 0;
   if (number > 0) {
     System.out.println("The number is positive.");
   } else if (number < 0) {
     System.out.println("The number is negative.");
   } else {
     System.out.println("The number is zero.");
   }
   ```

2. **Check if a student is grade A, B, or C**
   ```java
   int marks = 75;
   if (marks >= 85) {
     System.out.println("Grade A");
   } else if (marks >= 65) {
     System.out.println("Grade B");
   } else {
     System.out.println("Grade C");
   }
   ```

3. **Check if it's morning, afternoon, or night**
   ```java
   int hour = 14; // 2 PM
   if (hour < 12) {
     System.out.println("Good morning!");
   } else if (hour < 18) {
     System.out.println("Good afternoon!");
   } else {
     System.out.println("Good evening!");
   }
   ```

4. **Check if it's a weekend or weekday**
   ```java
   String day = "Monday";
   if (day.equals("Saturday") || day.equals("Sunday")) {
     System.out.println("It's a weekend.");
   } else {
     System.out.println("It's a weekday.");
   }
   ```

5. **Check age group**
   ```java
   int age = 25;
   if (age < 13) {
     System.out.println("Child");
   } else if (age < 20) {
     System.out.println("Teenager");
   } else {
     System.out.println("Adult");
   }
   ```

## 4. `switch` Statement
The `switch` statement is used to evaluate a single expression and match it against multiple cases. It is often more readable than multiple `if`/`else if` statements when there are many conditions.

### Syntax:
```java
switch (expression) {
  case value1:
    // code to run if expression matches value1
    break;
  case value2:
    // code to run if expression matches value2
    break;
  default:
    // code to run if no cases match
}
```

### Scenario:
A person is checking the day of the week to print a message.

### Examples:

1. **Check day of the week**
   ```java
   String day = "Monday";
   switch (day) {
     case "Monday":
       System.out.println("Start of the week!");
       break;
     case "Friday":
       System.out.println("Weekend is near!");
       break;
     default:
       System.out.println("Midweek!");
   }
   ```

2. **Check vehicle type**
   ```java
   String vehicle = "car";
   switch (vehicle) {
     case "car":
       System.out.println("Four wheels");
       break;
     case "bike":
       System.out.println("Two wheels");
       break;
     default:
       System.out.println("Unknown vehicle");
   }
   ```

3. **Check grade**
   ```java
   String grade = "A";
   switch (grade) {
     case "A":
       System.out.println("Excellent!");
       break;
     case "B":
       System.out.println("Good!");
       break;
     case "C":
       System.out.println("Fair");
       break;
     default:
       System.out.println("Failed");
   }
   ```

4. **Check fruit color**
   ```java
   String fruit = "apple";
   switch (fruit) {
     case "apple":
       System.out.println("Red or green");
       break;
     case "banana":
       System.out.println("Yellow");
       break;
     default:
       System.out.println("Unknown fruit");
   }
   ```

5. **Check month**
   ```java
   String month = "April";
   switch (month) {
     case "December":
     case "January":
     case "February":
       System.out.println("Winter");
       break;
     case "March":
     case "April":
     case "May":
       System.out.println("Spring");
       break;
     default:
       System.out.println("Summer or Fall");
   }
   ```

## 5. Loops
Loops allow you to run a block of code multiple times.
# Creating the content of the file
loop_explanation_content = """

# Loops in Java: Detailed Explanation for Students

## What is a Loop?
A **loop** is a way to make the computer repeat a set of instructions. For example, if you want to print "Hello!" 5 times, instead of writing it 5 times in the code, you can use a loop to do it for you.
It saves time and makes your code shorter and smarter.

## Types of Loops in Java
1. **`for` loop**: Use this when you know how many times the loop should run.
2. **`while` loop**: Use this when you don’t know how many times it will run, but you know the condition it should stop at.
3. **`do-while` loop**: Like `while`, but this one will always run at least once before checking the condition.

---

## How a Loop Works

Think of a loop like a washing machine:
1. You start the machine (initialization).
2. The machine checks if the clothes are still dirty (condition).
3. If dirty, it washes (executes the code).
4. After washing, it checks again (updates).
5. It keeps repeating until the clothes are clean (condition is false).

---

## 1. `for` Loop
The `for` loop is used when you know in advance how many times you want to repeat something.

### Syntax:
```java
for (initialization; condition; update) {
    // Code to execute
}
```

### How it Works (Simple Explanation):
1. **Initialization**: Start with a variable, like `int i = 0`. It tells the loop where to begin.
2. **Condition**: This decides how long the loop will run. For example, `i < 5` means, "Keep running while `i` is less than 5."
3. **Update**: After each round, update the variable. For example, `i++` adds 1 to `i`.

---

### Example:
Let’s print numbers from 1 to 5 using a `for` loop:

```java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

### What Happens in This Code:
- **Step 1**: Start with `i = 1`.
- **Step 2**: Check the condition: Is `i <= 5`? (Yes, so run the code.)
- **Step 3**: Print `i` (1).
- **Step 4**: Add 1 to `i` (now `i = 2`) and repeat steps 2–4 until `i > 5`.

### Output:
```
1
2
3
4
5
```

---
# `while` and `do-while` Loops in Java

In Java, both `while` and `do-while` loops are used for repeating a block of code multiple times, but they have key differences in how they check the condition and when the loop executes.

---

### 1. `while` Loop

The **`while` loop** repeatedly executes a block of code as long as a given condition is true. It checks the condition **before** running the loop's body, so if the condition is false initially, the code inside the loop will **never execute**.

#### Syntax:

```java
while (condition) {
    // Code to execute
}
```
- condition: An expression that evaluates to true or false. If true, the loop executes; if false, the loop stops.
- The loop continues executing as long as the condition remains true.

```
int i = 1;
while (i <= 5) {
    System.out.println(i);
    i++;  // Increment the counter
}
```
- What Happens in This Code:
- Step 1: Start with i = 1.
- Step 2: Check the condition i <= 5. Since it's true, enter the loop.
- Step 3: Print i (1).
- Step 4: Increment i (now i = 2).
- Step 5: Check the condition again. If it's true, repeat steps 3–5. If it's false, exit the loop.

- Key Point:
Condition checked before execution: If the condition is false initially, the loop does not run at all.
----
## 3. `do-while` Loop

The `do-while` loop is similar to the `while` loop, but with one important difference: it checks the condition **after** executing the loop's body. This means the block of code inside the loop will always run at least once, even if the condition is false initially.

### Syntax:

```java
do {
    // Code to execute
} while (condition);
```
- condition: Like in the while loop, this determines whether the loop will continue running. However, it's checked after the loop body executes, so the loop will run at least once regardless of the condition.

```
int i = 1;
do {
    System.out.println(i);
    i++;  // Increment the counter
} while (i <= 5);

````
**What Happens in This Code:**
- Step 1: Start with i = 1.
- Step 2: The block of code inside the loop is executed once, printing i (1).
- Step 3: Increment i (now i = 2).
- Step 4: Check the condition i <= 5. Since it's true, repeat the loop.
- Step 5: After the condition is checked, if it's still true, the loop continues.

- Key Point:
Condition checked after execution: The loop runs at least once, even if the condition is false initially.
----

## Differences Between Loops

| Feature        | `for` Loop               | `while` Loop          | `do-while` Loop         |
|----------------|--------------------------|------------------------|-------------------------|
| Use Case       | When you know how many times it should run. | When you don’t know how many times it will run. | When you want it to run at least once. |
| Condition Check | Before running the block. | Before running the block. | After running the block. |
| Runs at Least Once? | No                       | No                     | Yes                     |

---

## Key Points to Remember
1. **Infinite Loops**: If the condition never becomes false, the loop will run forever. For example:
   ```java
   while (true) {
       System.out.println("This never stops!");
   }
   ```
   Use **`break`** to stop an infinite loop when needed.

2. **Skipping Iterations (`continue`)**: Use `continue` to skip the rest of the code in the current iteration and move to the next one.
   ```java
   for (int i = 1; i <= 5; i++) {
       if (i == 3) continue;
       System.out.println(i);
   }
   // Output: 1 2 4 5
   ```

3. **Exiting Loops (`break`)**: Use `break` to stop the loop immediately.
   ```java
   for (int i = 1; i <= 5; i++) {
       if (i == 3) break;
       System.out.println(i);
   }
   // Output: 1 2
   ```

---

## Real-Life Analogy
Imagine you’re climbing stairs:
- **`for` loop**: You know there are 10 stairs, so you take 10 steps and stop.
- **`while` loop**: You don’t know how many stairs there are, so you keep going until you see no more stairs.
- **`do-while` loop**: You take one step first, then check if there are more stairs.

---

### **1. `for` Loop**
The `for` loop is used when you know in advance how many times you want to repeat something.

#### **Syntax**:
```java
for (initialization; condition; update) {
    // Code to execute
}


### Types of Loops:
- **`for` Loop**
- **`while` Loop**
- **`do...while` Loop**

### **`for` Loop**
The `for` loop repeats a block of code for a specific number of times.

### Syntax:
```java
for (int i = 0; i < 5; i++) {
  // code to execute
}
```

### Scenario:
A teacher is printing numbers from 1 to 5.

### Examples:

1. **Print numbers from 1 to 5**
   ```java
   for (int i = 1; i <= 5; i++) {
     System.out.println(i);
   }
   ```

2. **Print even numbers from 0 to 10**
   ```java
   for (int i = 0; i <= 10; i += 2) {
     System.out.println(i);
   }
   ```

3. **Print multiplication table of 5**
   ```java
   for (int i = 1; i <= 10; i++) {
     System.out.println(5 * i);
   }
   ```

4. **Sum of numbers from 1 to 5**
   ```java
   int sum = 0;
   for (int i = 1; i <= 5; i++) {
     sum += i;
   }
   System.out.println(sum);
   ```

5. **Print characters in a string**
   ```java
   String name = "John";
   for (int i = 0; i < name.length(); i++) {
     System.out.println(name.charAt(i));
   }
   ```

### **`while` Loop**
The `while` loop repeats a block of code as long as the specified condition is true.

### Syntax:
```java
while (condition) {
  // code to execute as long as condition is true
}
```

### Scenario:
A person needs to print numbers from 1 to 5 using a `while` loop.

### Examples:

1. **Print numbers from 1 to 5**
   ```java
   int i = 1;
   while (i <= 5) {
     System.out.println(i);
     i++;
   }
   ```

2. **Print even numbers from 0 to 10**
   ```java
   int i = 0;
   while (i <= 10) {
     System.out.println(i);
     i += 2;
   }
   ```

3. **Print multiplication table of 7**
   ```java
   int i = 1;
   while (i <= 10) {
     System.out.println(7 * i);
     i++;
   }
   ```

4. **Sum of numbers from 1 to 5**
   ```java
   int sum = 0;
   int i = 1;
   while (i <= 5) {
     sum += i;
     i++;
   }
   System.out.println(sum);
   ```

5. **Print characters in a string using `while` loop**
   ```java
   String name = "Alice";
   int i = 0;
   while (i < name.length()) {
     System.out.println(name.charAt(i));
     i++;
   }
   ```

### **`do...while` Loop**
The `do...while` loop executes a block of code at least once, and then repeats the execution as long as the condition is true.

### Syntax:
```java
do {
  // code to execute
} while (condition);
```

### Scenario:
A student is trying to print numbers from 1 to 5 using a `do...while` loop.

### Examples:

1. **Print numbers from 1 to 5**
   ```java
   int i = 1;
   do {
     System.out.println(i);
     i++;
   } while (i <= 5);
   ```

2. **Print even numbers from 0 to 10**
   ```java
   int i = 0;
   do {
     System.out.println(i);
     i += 2;
   } while (i <= 10);
   ```

3. **Print multiplication table of 3**
   ```java
   int i = 1;
   do {
     System.out.println(3 * i);
     i++;
   } while (i <= 10);
   ```

4. **Sum of numbers from 1 to 5**
   ```java
   int sum = 0;
   int i = 1;
   do {
     sum += i;
     i++;
   } while (i <= 5);
   System.out.println(sum);
   ```

5. **Print characters in a string using `do...while` loop**
   ```java
   String name = "Bob";
   int i = 0;
   do {
     System.out.println(name.charAt(i));
     i++;
   } while (i < name.length());
   ```

## Conclusion
Control statements (if, switch, loops) are fundamental in Java to control the flow of execution based on conditions or repeated actions. Understanding when and how to use them is crucial for writing efficient and readable code.

### Practice Exercise
1. Create a program that checks if a number is positive, negative, or zero.
2. Write a program using `switch` to print the name of a month based on its number (1-12).
3. Implement a program using loops that prints all prime numbers between 1 and 100.

----

# Methods (Functions) in Java

A **method** in Java is a block of code that performs a specific task. It is one of the most fundamental concepts in programming and helps organize your code into reusable pieces.

---

## Why Use Methods?
- **Reusability**: Write once, use many times.
- **Modularity**: Break the program into smaller, manageable parts.
- **Readability**: Makes the code easier to read and understand.
- **Maintainability**: Easier to debug and modify the code.

---

## Method Structure
A method in Java consists of:
1. **Access Modifier**: Defines the visibility of the method (e.g., `public`, `private`).
2. **Return Type**: Specifies the type of value the method returns (e.g., `int`, `void`).
3. **Method Name**: Describes what the method does (e.g., `calculateSum`).
4. **Parameters**: Inputs the method can take, written inside parentheses.
5. **Method Body**: The code that defines what the method does, enclosed in `{}`.

### Syntax:
```java
accessModifier returnType methodName(parameters) {
    // Method body (code to execute)
    return value; // Optional, depending on return type
}
```

---

## Simple Example
Let’s start with a simple example:

### Code:
```java
class HelloWorld {
    // Method to print a message
    public void printMessage() {
        System.out.println("Hello, World!");
    }

    public static void main(String[] args) {
        HelloWorld hw = new HelloWorld(); // Create an object
        hw.printMessage(); // Call the method
    }
}
```

### Output:
```
Hello, World!
```

---

## Types of Methods

### 1. **Void Methods**
Void methods perform an action but do not return any value.

#### Example:
```java
class Greeting {
    public void sayHello() {
        System.out.println("Hello!");
    }

    public static void main(String[] args) {
        Greeting g = new Greeting();
        g.sayHello();
    }
}
```

#### Output:
```
Hello!
```

### 2. **Methods with Return Values**
These methods perform a task and return a value to the caller.

#### Example:
```java
class Calculator {
    public int add(int a, int b) {
        return a + b; // Return the sum
    }

    public static void main(String[] args) {
        Calculator calc = new Calculator();
        int result = calc.add(5, 10); // Store the returned value
        System.out.println("Sum: " + result);
    }
}
```

#### Output:
```
Sum: 15
```

### 3. **Parameterized Methods**
These methods accept inputs (parameters) and use them to perform their tasks.

#### Example:
```java
class Greetings {
    public void greet(String name) {
        System.out.println("Hello, " + name + "!");
    }

    public static void main(String[] args) {
        Greetings g = new Greetings();
        g.greet("Alice");
        g.greet("Bob");
    }
}
```

#### Output:
```
Hello, Alice!
Hello, Bob!
```

---

## Key Concepts

### 1. **Method Overloading**
Having multiple methods with the same name but different parameters.

#### Example:
```java
class MathOperations {
    public int multiply(int a, int b) {
        return a * b;
    }

    public double multiply(double a, double b) {
        return a * b;
    }

    public static void main(String[] args) {
        MathOperations math = new MathOperations();
        System.out.println(math.multiply(5, 10));       // Calls the int version
        System.out.println(math.multiply(5.5, 10.5));   // Calls the double version
    }
}
```

#### Output:
```
50
57.75
```

### 2. **Static Methods**
Static methods belong to the class rather than an instance of the class. They can be called without creating an object.

#### Example:
```java
class Utility {
    public static int square(int number) {
        return number * number;
    }

    public static void main(String[] args) {
        int result = Utility.square(4); // No need to create an object
        System.out.println("Square: " + result);
    }
}
```

#### Output:
```
Square: 16
```

### 3. **Method Scope**
Variables declared inside a method are local to that method and cannot be accessed outside of it.

#### Example:
```java
class ScopeExample {
    public void showScope() {
        int localVariable = 10; // Local variable
        System.out.println("Local variable: " + localVariable);
    }

    public static void main(String[] args) {
        ScopeExample scope = new ScopeExample();
        scope.showScope();
        // System.out.println(localVariable); // Error: Cannot access localVariable here
    }
}
```

---

## Best Practices for Methods
1. **Use meaningful names**: Names should describe what the method does (e.g., `calculateSum`).
2. **Keep methods short**: A method should perform one task.
3. **Document methods**: Use comments or JavaDoc to explain what the method does.
4. **Avoid too many parameters**: If a method requires too many inputs, consider breaking it into smaller methods.

---

## Summary Table

| **Feature**            | **Description**                                                  |
|-------------------------|------------------------------------------------------------------|
| Void Methods            | Perform tasks without returning a value.                        |
| Methods with Return     | Perform tasks and return a value.                               |
| Parameterized Methods   | Accept inputs to perform specific tasks.                        |
| Method Overloading      | Multiple methods with the same name but different parameters.   |
| Static Methods          | Belong to the class, can be called without creating an object.  |
| Method Scope            | Variables inside a method are not accessible outside it.        |

This content provides a beginner-friendly explanation of methods in Java. Let me know if you need additional details or exercises!


-----




# Object-Oriented Programming (OOP)

OOP is a way to organize code by grouping related **data** (properties) and **behaviors** (methods) into objects.

---

## 🎯 Why OOP?
- Keeps code **organized** and **easy to manage**.
- Allows **reusing** code instead of writing the same thing over and over.
- Makes it easier to **update** or **extend** functionality.

---

## 🐾 Real-World Example: A Zoo
Imagine a zoo where each animal is an **object**.

### Example: A Lion
- **Properties** (data):
  - `name: Simba`
  - `species: Lion`
  - `color: Golden`
- **Methods** (actions):
  - `roar()`
  - `hunt()`

### Example: A Bird
- **Properties**:
  - `name: Tweety`
  - `species: Bird`
  - `color: Yellow`
- **Methods**:
  - `fly()`
  - `sing()`

---

## 🏗 Key Concepts in OOP

### 1. **Class**
A **blueprint** for creating objects. Think of it as a recipe.

```javascript
class Animal {
  constructor(name, species) {
    this.name = name;       // Property
    this.species = species; // Property
  }

  speak() {                 // Method
    console.log(`${this.name} makes a sound.`);
  }
}
```

---

### 2. **Object**
An **instance** of a class. Think of it as a specific animal created from the recipe.

```javascript
const lion = new Animal('Simba', 'Lion'); // Object
lion.speak(); // Output: "Simba makes a sound."
```

---

### 3. **Inheritance**
A way to **reuse code** by creating a new class from an existing one.

```javascript
class Bird extends Animal {
  fly() {
    console.log(`${this.name} is flying!`);
  }
}

const tweety = new Bird('Tweety', 'Bird');
tweety.fly(); // Output: "Tweety is flying!"
```

---

### 4. **Encapsulation**
Keeping the details **hidden** and only exposing what’s necessary.

```javascript
class BankAccount {
  #balance; // Private property
  constructor(balance) {
    this.#balance = balance;
  }

  getBalance() {
    return this.#balance;
  }
}

const account = new BankAccount(1000);
console.log(account.getBalance()); // Output: 1000
```

---

## 🌟 Benefits of OOP
- **Readable**: Code is easier to understand.
- **Reusable**: Avoids duplication with inheritance.
- **Maintainable**: Makes updates easier by grouping related stuff.

---

## 🎉 Summary
OOP is like organizing your desk. Instead of having everything scattered, you group related things together into neat objects. This helps make your code clean, reusable, and efficient.

---

## 1. **Encapsulation**

### Definition:
Encapsulation is the process of bundling data (variables) and methods (functions) that operate on the data into a single unit, usually a class. It hides the internal implementation details and exposes only what is necessary.

### Real-World Example:
A **bank account** allows users to deposit or withdraw money but restricts direct access to the account balance.

### Benefits:
- Protects the internal state of an object.
- Provides controlled access to data.
- Enhances security and maintainability.

### Code Example:
```java
class BankAccount {
    private double balance; // Encapsulated variable

    // Constructor to initialize balance
    public BankAccount(double initialBalance) {
        if (initialBalance >= 0) {
            this.balance = initialBalance;
        } else {
            System.out.println("Initial balance cannot be negative!");
            this.balance = 0;
        }
    }

    // Public method to deposit money
    public void deposit(double amount) {
        if (amount > 0) {
            balance += amount;
            System.out.println("Deposited: " + amount);
        } else {
            System.out.println("Deposit amount must be positive!");
        }
    }

    // Public method to withdraw money
    public void withdraw(double amount) {
        if (amount > 0 && amount <= balance) {
            balance -= amount;
            System.out.println("Withdrew: " + amount);
        } else {
            System.out.println("Insufficient funds or invalid amount!");
        }
    }

    // Public getter method to view balance
    public double getBalance() {
        return balance;
    }
}

public class Main {
    public static void main(String[] args) {
        BankAccount account = new BankAccount(1000);
        account.deposit(500);
        account.withdraw(300);
        System.out.println("Balance: " + account.getBalance());
    }
}
```

### Output:
```
Deposited: 500
Withdrew: 300
Balance: 1200
```

---

## 2. **Inheritance**

### Definition:
Inheritance allows one class (child) to acquire the properties and methods of another class (parent). This promotes **code reuse** and hierarchy.

### Real-World Example:
A **Car** class has general properties like speed, color, and methods like drive. A **SportsCar** inherits from the Car class and adds unique features like turbo mode.

### Benefits:
- Reduces code duplication.
- Simplifies extension and maintenance.
- Promotes hierarchical design.

### Code Example:
```java
// Parent class
class Car {
    private String brand;
    private int speed;

    public Car(String brand, int speed) {
        this.brand = brand;
        this.speed = speed;
    }

    public void drive() {
        System.out.println(brand + " is driving at " + speed + " km/h.");
    }
}

// Child class
class SportsCar extends Car {
    private boolean turboEnabled;

    public SportsCar(String brand, int speed) {
        super(brand, speed); // Call parent class constructor
        this.turboEnabled = false;
    }

    public void enableTurbo() {
        this.turboEnabled = true;
        System.out.println("Turbo mode activated!");
    }
}

public class Main {
    public static void main(String[] args) {
        SportsCar myCar = new SportsCar("Ferrari", 200);
        myCar.drive();       // Inherited method
        myCar.enableTurbo(); // Specific to SportsCar
    }
}
```

### Output:
```
Ferrari is driving at 200 km/h.
Turbo mode activated!
```

---

## 3. **Polymorphism**

### Definition:
Polymorphism means "many forms." It allows a single method, object, or interface to behave differently based on the context.

### Real-World Example:
A **remote control** can control different devices (TV, AC, etc.), but the behavior of the buttons changes depending on the device.

### Types:
1. **Compile-Time Polymorphism (Method Overloading)**: Multiple methods with the same name but different parameters.
2. **Run-Time Polymorphism (Method Overriding)**: A method in a child class overrides a method in the parent class.

### Code Examples:
#### Compile-Time Polymorphism:
```java
class Calculator {
    public int add(int a, int b) {
        return a + b;
    }

    public double add(double a, double b) {
        return a + b;
    }
}

public class Main {
    public static void main(String[] args) {
        Calculator calc = new Calculator();
        System.out.println("Integer Sum: " + calc.add(5, 10));
        System.out.println("Double Sum: " + calc.add(5.5, 10.5));
    }
}
```

#### Run-Time Polymorphism:
```java
class Animal {
    public void sound() {
        System.out.println("Animal makes a sound.");
    }
}

class Dog extends Animal {
    @Override
    public void sound() {
        System.out.println("Dog barks.");
    }
}

class Cat extends Animal {
    @Override
    public void sound() {
        System.out.println("Cat meows.");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myAnimal;

        myAnimal = new Dog(); // Polymorphism
        myAnimal.sound();

        myAnimal = new Cat(); // Polymorphism
        myAnimal.sound();
    }
}
```

### Output:
```
Dog barks.
Cat meows.
```

---

## 4. **Abstraction**

### Definition:
Abstraction hides the implementation details of a system and only shows the essential features to the user. It can be achieved using **abstract classes** or **interfaces**.

### Real-World Example:
When you drive a car, you don’t worry about how the engine works. You only use the steering, accelerator, and brake.

### Benefits:
- Simplifies the system for the user.
- Promotes focus on what an object **does** rather than how it **works**.

### Code Example:
#### Using Abstract Classes:
```java
abstract class Shape {
    abstract void draw(); // Abstract method

    public void info() {
        System.out.println("This is a shape.");
    }
}

class Circle extends Shape {
    @Override
    public void draw() {
        System.out.println("Drawing a Circle...");
    }
}

class Rectangle extends Shape {
    @Override
    public void draw() {
        System.out.println("Drawing a Rectangle...");
    }
}

public class Main {
    public static void main(String[] args) {
        Shape shape;

        shape = new Circle();
        shape.draw();

        shape = new Rectangle();
        shape.draw();
    }
}
```

### Output:
```
Drawing a Circle...
Drawing a Rectangle...
```

---

## Summary:

| **Principle**   | **Key Feature**                   | **Real-World Example**                | **Code Example**                       |
|------------------|-----------------------------------|---------------------------------------|----------------------------------------|
| Encapsulation    | Data hiding                      | Bank Account                          | Getter and Setter methods              |
| Inheritance      | Code reuse                       | Car → SportsCar                       | `extends` keyword                      |
| Polymorphism     | Many forms (Overloading/Overriding) | Remote control for devices            | Overloading/Overriding methods         |
| Abstraction      | Hide details, show functionality | Driving a car (steering, brake)       | Abstract classes and methods           |

These examples should give you a comprehensive understanding of OOP principles in Java!



---------
# Java Collections Framework Roadmap  

## 1. What are Collections and Why Do We Need Them?  
Collections are tools in Java to store and manage groups of objects, like a list of names or a set of unique numbers.  

**Why Collections are Better than Arrays:**  
- They can grow or shrink in size automatically.  
- They provide ready-made methods for common tasks like sorting, searching, etc.  

---

## 2. Important Interfaces (Blueprints) in Collections  
Java Collections are built around these key interfaces (think of them as blueprints for storing data):  

### **List**  
- For ordered data where duplicates are allowed (e.g., a list of names).  
- **Example Classes:** `ArrayList`, `LinkedList`  

### **Set**  
- For storing unique items (e.g., unique IDs).  
- **Example Classes:** `HashSet`, `TreeSet`  

### **Queue**  
- For storing items in the order they need to be processed (e.g., a line of customers).  
- **Example Classes:** `PriorityQueue`, `ArrayDeque`  

### **Map**  
- For storing key-value pairs (e.g., a phone book where each name has a number).  
- **Example Classes:** `HashMap`, `TreeMap`  

---

## 3. Basic Data Structures and Their Use  
# Key Collection Types in Java

## 1. **List**
A **List** is an ordered collection that allows duplicate elements. It is ideal for scenarios where the order of items is important, like a to-do list.

### Examples:
- **ArrayList**:
  - **Best for Fast Searching and Random Access**  
  If you need to quickly find or access an item by its position in the list (like getting the 3rd item), an **ArrayList** is very efficient. This is because it uses an array internally, where each item has an index.

- **Backed by a Dynamic Array**  
  An **ArrayList** is built on top of a dynamic array. Unlike regular arrays, it can grow or shrink in size automatically. If you add more items than it can currently hold, it will create a larger array to accommodate all the items.

- **Slower for Inserting/Removing Items in the Middle**  
  When you add or remove an item in the middle of the list, all the items after that position need to be shifted to make space or fill the gap. This shifting process takes extra time, making these operations slower compared to structures like a LinkedList.
  - Example:
    ```java
    List<String> arrayList = new ArrayList<>();
    arrayList.add("Task 1");
    arrayList.add("Task 2");
    System.out.println(arrayList); // Output: [Task 1, Task 2]
    ```
- **LinkedList**:
 - **Efficient for Inserting/Removing Items in the Middle of the List**  
  A **LinkedList** is great when you frequently add or remove items from the middle of the list. Unlike an **ArrayList**, it doesn't need to shift items around because it's made up of nodes that are linked together.

- **Backed by a Doubly-Linked List**  
  A **LinkedList** uses a data structure called a doubly-linked list. Each item (node) in the list contains data and two links: one pointing to the previous node and one pointing to the next. This structure makes it easy to add or remove nodes.

- **Slower for Searching Because It Requires Traversal**  
  To find an item in a **LinkedList**, you have to start from the beginning (or end) and move through each node one by one until you find what you're looking for. This process takes more time compared to an **ArrayList**, which can directly access items by their position.
  - Example:
    ```java
    List<String> linkedList = new LinkedList<>();
    linkedList.add("Node 1");
    linkedList.add("Node 2");
    System.out.println(linkedList); // Output: [Node 1, Node 2]
    ```

---

## 2. **Set**
- **Ensures All Elements Are Unique**  
  A **Set** is a collection where duplicate elements are not allowed. It automatically ensures that every item in the collection is unique, making it perfect for cases where repetition is not allowed, such as storing student IDs or unique inventory items.

- **When to Use**  
  Use a **Set** when you want to keep only unique elements and don’t care about the order in which they are stored.

- **Examples of Set Implementations**  
  - **HashSet**:  
    - Best for fast operations like adding, removing, or checking if an item exists.  
    - Does not maintain any order of elements.
  - **TreeSet**:  
    - Keeps elements in sorted order.  
    - Slightly slower than **HashSet** due to the sorting overhead.
  - **LinkedHashSet**:  
    - Maintains the insertion order of elements.  
    - Useful when you need unique elements and want to preserve their order of addition.

### Examples:
- **HashSet**:
  - Offers fast operations (add, remove, search) with no guaranteed order.
  - Backed by a hash table.
  - Example:
    ```java
    Set<String> hashSet = new HashSet<>();
    hashSet.add("ID1");
    hashSet.add("ID2");
    hashSet.add("ID1"); // Duplicate, will not be added.
    System.out.println(hashSet); // Output: [ID1, ID2]
    ```
- **TreeSet**:
  - Keeps elements sorted in natural order or by a custom comparator.
  - Slower than HashSet but useful when sorted data is required.
  - Example:
    ```java
    Set<String> treeSet = new TreeSet<>();
    treeSet.add("Banana");
    treeSet.add("Apple");
    System.out.println(treeSet); // Output: [Apple, Banana]
    ```

---

## 3. **Queue**
- **Represents a Waiting Line (FIFO - First In, First Out)**  
  A **Queue** is a collection where elements are processed in the order they were added, just like a line of people waiting for service. The first person to enter the line is the first to be served (FIFO).

- **When to Use**  
  Use a **Queue** when you need to process items in the order they were added, such as handling tasks in a task manager, processing customer requests, or managing data streams.

- **Examples of Queue Implementations**  
  - **PriorityQueue**:  
    - Items are processed based on priority rather than the order they were added.  
    - The highest priority item is processed first, making it useful for scheduling tasks or handling events in a system.
  - **LinkedList** (Used as a Queue):  
    - A **LinkedList** can be used as a **Queue** where elements are added at the end and removed from the front.  
    - It's efficient for adding and removing items from both ends of the list.
  - **ArrayDeque**:  
    - A **Deque** (Double-Ended Queue) can function as a regular **Queue** and allows adding and removing elements from both ends of the collection, making it a flexible option.

### Examples:
- **PriorityQueue**:
  - Automatically prioritizes items based on natural order or a comparator.
  - Example:
    ```java
    Queue<Integer> priorityQueue = new PriorityQueue<>();
    priorityQueue.add(5);
    priorityQueue.add(1);
    priorityQueue.add(3);
    System.out.println(priorityQueue); // Output: [1, 5, 3] (priority-based)
    System.out.println(priorityQueue.poll()); // Output: 1 (removes highest priority)
    ```

---

## 4. **Map**
- **Stores Key-Value Pairs**  
  A **Map** is a collection that stores data in the form of key-value pairs. Each key is associated with a specific value, meaning that you can retrieve the value by referencing the key. It's like a dictionary where each word (key) maps to its definition (value).

- **When to Use**  
  Use a **Map** when you need to store data where each piece of information has a unique identifier (key), and you want to quickly look up, update, or remove data using the key. Common use cases include creating a phone book (name to phone number mapping) or an address book (email to contact info).

- **Examples of Map Implementations**  
  - **HashMap**:  
    - Best for fast lookups, insertions, and deletions.  
    - Does not maintain the order of elements.
  - **TreeMap**:  
    - Keeps the keys in sorted order.  
    - Slower than **HashMap** due to sorting overhead, but useful when you need ordered keys.
  - **LinkedHashMap**:  
    - Maintains the order of elements based on the order they were added.  
    - Useful when you want to store key-value pairs and maintain insertion order.






### Examples:
- **HashMap**:
  - Fast for lookups and insertions.
  - Does not guarantee order of elements.
  - Example:
    ```java
    Map<String, String> hashMap = new HashMap<>();
    hashMap.put("Alice", "12345");
    hashMap.put("Bob", "67890");
    System.out.println(hashMap); // Output: {Alice=12345, Bob=67890}
    ```
- **TreeMap**:
  - Keeps keys sorted in natural order or by a custom comparator.
  - Slower than HashMap but useful when sorted data is required.
  - Example:
    ```java
    Map<String, String> treeMap = new TreeMap<>();
    treeMap.put("Charlie", "54321");
    treeMap.put("Alice", "12345");
    System.out.println(treeMap); // Output: {Alice=12345, Charlie=54321}
    ```


---

## 4. Learn Basic Operations  
Practice common operations for each collection type:  

- **List:** Add, remove, and search for items.  
- **Set:** Add unique items.  
- **Queue:** Add items and process them in order.  
- **Map:** Store and retrieve key-value pairs.  

---

## 5. Make Your Collections Smart with Sorting  
- Use **`Comparable`** for natural ordering (e.g., A-Z).  
- Use **`Comparator`** for custom sorting (e.g., sort students by age).  

---

## 6. Be Safe with Thread-Safe Collections  
If multiple users are accessing your collections (like in an online app), use thread-safe collections:  

- Use `ConcurrentHashMap` instead of `HashMap`.  
- Use `CopyOnWriteArrayList` for thread-safe lists.  

---

## 7. Generics – A Fancy Word for Type Safety  
Collections use generics to ensure all items are of the same type.  

### **Example:**  
```java
List<String> words = new ArrayList<>();
words.add("Hello");
// words.add(123); // This will cause a compile-time error
```
# Mastering Java Collections

## 8. Handle Advanced Scenarios

### Set Operations
Combine or compare sets to handle scenarios like finding common or unique items in two sets.

### Map Tricks
Work with complex data by storing maps of lists or other intricate structures.

### Thread-Safe Apps
When working with threads (programs doing multiple things at once), use special thread-safe collections.

---

## 9. Learn New Features in Modern Java (Java 8+)

### Streams API
Process collections in a simple and modern way using the Streams API.

#### Example: Filter out numbers greater than 10
```java
List<Integer> numbers = Arrays.asList(5, 15, 20, 25);
List<Integer> filtered = numbers.stream()
                                .filter(num -> num > 10)
                                .collect(Collectors.toList());
System.out.println(filtered); // Output: [15, 20, 25]
```
## Lambda Functions
Write concise and clean code to iterate through collections effortlessly.

### Example:
```java
list.forEach(item -> System.out.println(item));
```

Use **Collectors** to gather and transform data from streams into collections like **lists**, **sets**, or **maps**.

### Example:
Convert a stream of names into a **Set**:
```java
Set<String> nameSet = names.stream()
                           .filter(name -> name.length() > 3)
                           .collect(Collectors.toSet());
```
----------
# Java Collections Framework: Lists, Sets, and Maps

## Why Use Collections in Java?
Imagine you are organizing a library with hundreds of books. You want to:
- Keep track of all the books.
- Avoid duplicate entries for the same book.
- Quickly find a book by its title or ISBN.

Handling such tasks using arrays can be tedious and inefficient. The Java Collections Framework provides **Lists**, **Sets**, and **Maps**, which make handling such data much easier, efficient, and flexible.

---

## **1. Lists**
A **List** is an ordered collection of elements. It allows duplicate entries and maintains the order in which elements are inserted.

### **Scenario**
You want to store the names of students in the order they registered for a course.

### **Key Features**
- **Duplicates Allowed:** You can add the same name twice.
- **Indexed Access:** Each student has an index (position).

### **Example**
```java
import java.util.ArrayList;
import java.util.List;

public class ListExample {
    public static void main(String[] args) {
        List<String> students = new ArrayList<>();

        // Adding students
        students.add("Alice");
        students.add("Bob");
        students.add("Alice");

        // Printing students
        System.out.println("Registered Students: " + students);

        // Accessing by index
        System.out.println("First student: " + students.get(0));
    }
}
```

### **Dry Run**
| Operation               | List Content        |
|-------------------------|---------------------|
| `students.add("Alice")` | ["Alice"]           |
| `students.add("Bob")`   | ["Alice", "Bob"]    |
| `students.add("Alice")` | ["Alice", "Bob", "Alice"] |
| `students.get(0)`       | Outputs: "Alice"    |

---

## **2. Sets**
A **Set** is a collection that does not allow duplicate elements. It is useful when you want to ensure unique entries.

### **Scenario**
You are managing an online voting system where each voter can vote only once.

### **Key Features**
- **No Duplicates:** Ensures that each voter can vote only once.
- **Unordered:** Does not maintain the insertion order.

### **Example**
```java
import java.util.HashSet;
import java.util.Set;

public class SetExample {
    public static void main(String[] args) {
        Set<String> voters = new HashSet<>();

        // Adding voters
        voters.add("Alice");
        voters.add("Bob");
        voters.add("Alice");

        // Printing voters
        System.out.println("Unique Voters: " + voters);
    }
}
```

### **Dry Run**
| Operation               | Set Content         |
|-------------------------|---------------------|
| `voters.add("Alice")`   | ["Alice"]           |
| `voters.add("Bob")`     | ["Alice", "Bob"]    |
| `voters.add("Alice")`   | ["Alice", "Bob"]    |

---

## **3. Maps**
A **Map** is a collection that stores data in key-value pairs. Each key is unique, and a key maps to a single value.

### **Scenario**
You want to store and retrieve the phone numbers of people using their names as identifiers.

### **Key Features**
- **Key-Value Pair:** Each key maps to one value.
- **No Duplicate Keys:** Each key must be unique.

### **Example**
```java
import java.util.HashMap;
import java.util.Map;

public class MapExample {
    public static void main(String[] args) {
        Map<String, String> phoneBook = new HashMap<>();

        // Adding entries
        phoneBook.put("Alice", "123-456-7890");
        phoneBook.put("Bob", "987-654-3210");
        phoneBook.put("Alice", "111-222-3333");

        // Printing phone book
        System.out.println("Phone Book: " + phoneBook);

        // Accessing by key
        System.out.println("Alice's Phone: " + phoneBook.get("Alice"));
    }
}
```

### **Dry Run**
| Operation                      | Map Content                             |
|--------------------------------|-----------------------------------------|
| `phoneBook.put("Alice", "123-456-7890")` | {"Alice"="123-456-7890"}          |
| `phoneBook.put("Bob", "987-654-3210")`   | {"Alice"="123-456-7890", "Bob"="987-654-3210"} |
| `phoneBook.put("Alice", "111-222-3333")` | {"Alice"="111-222-3333", "Bob"="987-654-3210"} |
| `phoneBook.get("Alice")`                | Outputs: "111-222-3333"           |

---

## Summary Table
| Feature               | List                   | Set                    | Map                          |
|-----------------------|------------------------|------------------------|------------------------------|
| Duplicates Allowed    | Yes                    | No                     | Keys: No, Values: Yes        |
| Maintains Order       | Yes                    | No                     | No                          |
| Access by Index/Key   | By Index               | Not Applicable         | By Key                      |

---

With these collections, Java makes it easier to manage data efficiently for various scenarios. Experiment with these examples to solidify your understanding!
-----
# Sorting and Searching in Java

## Introduction
Sorting and searching are fundamental operations in computer science that allow you to organize data and retrieve specific information efficiently. These operations are crucial for improving the performance of algorithms and ensuring that data is processed in a way that minimizes time and space complexity.

- **Sorting**: Arranges elements in a particular order (e.g., ascending or descending).
- **Searching**: Locates a specific element within a dataset.

## What
Sorting and searching are two of the most widely used algorithms in software development. Sorting organizes a collection of elements, and searching is the process of finding specific elements within that collection. 

- **Sorting**: Can be done in ascending or descending order, and there are various sorting algorithms available, such as Bubble Sort, Merge Sort, Quick Sort, etc.
- **Searching**: Involves finding an element in a dataset. Popular searching algorithms include Linear Search and Binary Search.

## Why
Sorting and searching are essential for:
- **Efficiency**: Algorithms are often more efficient when the data is sorted. Searching in sorted data can be faster and less computationally expensive (e.g., Binary Search).
- **Optimization**: Many algorithms require sorted data as input to work efficiently (e.g., for implementing range queries or finding the median).
- **Problem Solving**: Many real-world problems require sorting or searching to solve them efficiently, such as searching for a specific record in a database or arranging elements in a specific order for a display or report.

## Where
Sorting and searching are commonly used in:
- **Databases**: For organizing records and performing efficient searches.
- **Web development**: Sorting user data or search results.
- **Data analysis**: Sorting data for analysis or finding specific entries in large datasets.
- **Algorithms and problem-solving**: In contests, interviews, and competitive programming challenges.

## When
You need to use sorting and searching when:
- **Sorting**: When you need to organize a dataset in a specific order (e.g., sorting a list of employees by their salaries).
- **Searching**: When you need to find an element in a dataset quickly (e.g., finding a specific product in an e-commerce platform).

## How

### Sorting in Java
In Java, sorting can be achieved using:
1. **Java Arrays.sort()**: The `Arrays.sort()` method provides a simple and fast way to sort arrays in Java.
   ```java
   int[] arr = {5, 2, 9, 1, 5, 6};
   Arrays.sort(arr); // sorts the array in ascending order
   ```
2. **Collections.sort()**: If you have a list of objects, the Collections.sort() method can be used to sort them.
```
List<Integer> list = Arrays.asList(5, 2, 9, 1, 5, 6);
Collections.sort(list); // sorts the list in ascending order
```
In this document, we will explore multiple sorting and searching algorithms in Java, including their scenarios, code, and dry runs.

---

## Sorting Algorithms

### 1. Bubble Sort
Bubble Sort is a simple algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process continues until the list is sorted.

#### Scenario
Imagine you have a list of students' scores and want to arrange them in ascending order to identify the lowest and highest scores.

#### Java Code
```java
public class BubbleSort {
    public static void bubbleSort(int[] array) {
        int n = array.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (array[j] > array[j + 1]) {
                    // Swap array[j] and array[j + 1]
                    int temp = array[j];
                    array[j] = array[j + 1];
                    array[j + 1] = temp;
                }
            }
        }
    }

    public static void main(String[] args) {
        int[] scores = {45, 32, 88, 12, 67};

        System.out.println("Original Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }

        bubbleSort(scores);

        System.out.println("\n\nSorted Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }
    }
}
```

#### Dry Run
Let’s sort the array `[45, 32, 88, 12, 67]` using Bubble Sort:

1. **Pass 1:**
   - Compare 45 and 32 → Swap → `[32, 45, 88, 12, 67]`
   - Compare 45 and 88 → No Swap
   - Compare 88 and 12 → Swap → `[32, 45, 12, 88, 67]`
   - Compare 88 and 67 → Swap → `[32, 45, 12, 67, 88]`

2. **Pass 2:**
   - Compare 32 and 45 → No Swap
   - Compare 45 and 12 → Swap → `[32, 12, 45, 67, 88]`
   - Compare 45 and 67 → No Swap

3. **Pass 3:**
   - Compare 32 and 12 → Swap → `[12, 32, 45, 67, 88]`
   - Compare 32 and 45 → No Swap

4. **Pass 4:**
   - Compare 12 and 32 → No Swap

Final sorted array: `[12, 32, 45, 67, 88]`

---

### 2. Selection Sort
Selection Sort divides the array into two parts: the sorted part and the unsorted part. It repeatedly selects the smallest (or largest) element from the unsorted part and moves it to the sorted part.

#### Java Code
```java
public class SelectionSort {
    public static void selectionSort(int[] array) {
        int n = array.length;
        for (int i = 0; i < n - 1; i++) {
            int minIndex = i;
            for (int j = i + 1; j < n; j++) {
                if (array[j] < array[minIndex]) {
                    minIndex = j;
                }
            }
            // Swap array[i] and array[minIndex]
            int temp = array[minIndex];
            array[minIndex] = array[i];
            array[i] = temp;
        }
    }

    public static void main(String[] args) {
        int[] scores = {45, 32, 88, 12, 67};

        System.out.println("Original Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }

        selectionSort(scores);

        System.out.println("\n\nSorted Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }
    }
}
```

#### Dry Run
Let’s sort the array `[45, 32, 88, 12, 67]` using Selection Sort:

1. **Pass 1:**
   - Find the smallest element (12) and swap it with the first element → `[12, 32, 88, 45, 67]`

2. **Pass 2:**
   - Find the smallest element (32) in the remaining array and swap → `[12, 32, 88, 45, 67]`

3. **Pass 3:**
   - Find the smallest element (45) in the remaining array and swap → `[12, 32, 45, 88, 67]`

4. **Pass 4:**
   - Find the smallest element (67) in the remaining array and swap → `[12, 32, 45, 67, 88]`

Final sorted array: `[12, 32, 45, 67, 88]`

---

### 3. Insertion Sort
Insertion Sort builds the sorted array one element at a time by repeatedly picking an element and inserting it into its correct position.

#### Java Code
```java
public class InsertionSort {
    public static void insertionSort(int[] array) {
        int n = array.length;
        for (int i = 1; i < n; i++) {
            int key = array[i];
            int j = i - 1;

            while (j >= 0 && array[j] > key) {
                array[j + 1] = array[j];
                j--;
            }
            array[j + 1] = key;
        }
    }

    public static void main(String[] args) {
        int[] scores = {45, 32, 88, 12, 67};

        System.out.println("Original Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }

        insertionSort(scores);

        System.out.println("\n\nSorted Scores:");
        for (int score : scores) {
            System.out.print(score + " ");
        }
    }
}
```

#### Dry Run
Let’s sort the array `[45, 32, 88, 12, 67]` using Insertion Sort:

1. **Pass 1:**
   - Insert 32 into its correct position → `[32, 45, 88, 12, 67]`

2. **Pass 2:**
   - Insert 88 into its correct position → `[32, 45, 88, 12, 67]`

3. **Pass 3:**
   - Insert 12 into its correct position → `[12, 32, 45, 88, 67]`

4. **Pass 4:**
   - Insert 67 into its correct position → `[12, 32, 45, 67, 88]`

Final sorted array: `[12, 32, 45, 67, 88]`

---
# Sorting Algorithms: Merge Sort, Quick Sort, and Built-in Sorting

## 1. Merge Sort

Merge Sort is a divide-and-conquer algorithm that divides the array into halves, recursively sorts them, and then merges the sorted halves.

### **Algorithm Steps**
1. Divide the array into two halves.
2. Recursively sort each half.
3. Merge the two sorted halves back into a single sorted array.

### **Time Complexity**
- Best Case: O(n log n)
- Worst Case: O(n log n)
- Average Case: O(n log n)

### **Code Example**
```java
public class MergeSort {
    public static void mergeSort(int[] arr, int left, int right) {
        if (left < right) {
            int mid = left + (right - left) / 2;

            // Recursively divide the array
            mergeSort(arr, left, mid);
            mergeSort(arr, mid + 1, right);

            // Merge the sorted halves
            merge(arr, left, mid, right);
        }
    }

    public static void merge(int[] arr, int left, int mid, int right) {
        int n1 = mid - left + 1;
        int n2 = right - mid;

        int[] L = new int[n1];
        int[] R = new int[n2];

        System.arraycopy(arr, left, L, 0, n1);
        System.arraycopy(arr, mid + 1, R, 0, n2);

        int i = 0, j = 0, k = left;
        while (i < n1 && j < n2) {
            if (L[i] <= R[j]) {
                arr[k] = L[i];
                i++;
            } else {
                arr[k] = R[j];
                j++;
            }
            k++;
        }

        while (i < n1) {
            arr[k] = L[i];
            i++;
            k++;
        }

        while (j < n2) {
            arr[k] = R[j];
            j++;
            k++;
        }
    }

    public static void main(String[] args) {
        int[] arr = {12, 11, 13, 5, 6, 7};
        mergeSort(arr, 0, arr.length - 1);
        System.out.println("Sorted array: ");
        for (int num : arr) {
            System.out.print(num + " ");
        }
    }
}
```

### **Dry Run**
Input: `[12, 11, 13, 5, 6, 7]`

1. Split into `[12, 11, 13]` and `[5, 6, 7]`.
2. Further split into `[12]`, `[11, 13]`, `[5]`, and `[6, 7]`.
3. Sort and merge: `[11, 12, 13]` and `[5, 6, 7]`.
4. Final merge: `[5, 6, 7, 11, 12, 13]`.

---

## 2. Quick Sort

Quick Sort is a divide-and-conquer algorithm that selects a "pivot" element and partitions the array around the pivot, ensuring elements smaller than the pivot are on the left and larger elements are on the right.

### **Algorithm Steps**
1. Select a pivot element.
2. Partition the array such that elements smaller than the pivot go to the left, and elements greater than the pivot go to the right.
3. Recursively apply the process to the left and right subarrays.

### **Time Complexity**
- Best Case: O(n log n)
- Worst Case: O(n²) (when the pivot is the smallest or largest element)
- Average Case: O(n log n)

### **Code Example**
```java
public class QuickSort {
    public static void quickSort(int[] arr, int low, int high) {
        if (low < high) {
            int pi = partition(arr, low, high);

            quickSort(arr, low, pi - 1);
            quickSort(arr, pi + 1, high);
        }
    }

    public static int partition(int[] arr, int low, int high) {
        int pivot = arr[high];
        int i = (low - 1);

        for (int j = low; j < high; j++) {
            if (arr[j] <= pivot) {
                i++;

                // Swap arr[i] and arr[j]
                int temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }

        // Swap arr[i+1] and pivot
        int temp = arr[i + 1];
        arr[i + 1] = arr[high];
        arr[high] = temp;

        return i + 1;
    }

    public static void main(String[] args) {
        int[] arr = {10, 7, 8, 9, 1, 5};
        quickSort(arr, 0, arr.length - 1);
        System.out.println("Sorted array: ");
        for (int num : arr) {
            System.out.print(num + " ");
        }
    }
}
```

### **Dry Run**
Input: `[10, 7, 8, 9, 1, 5]`

1. Select pivot = 5. Partition: `[1] | 5 | [10, 7, 8, 9]`.
2. Recur on `[1]` (already sorted).
3. Pivot = 9 in `[10, 7, 8, 9]`. Partition: `[7, 8] | 9 | [10]`.
4. Final sorted array: `[1, 5, 7, 8, 9, 10]`.

---

## 3. Built-in Sorting

Java provides built-in methods for sorting arrays and collections using `Arrays.sort()` and `Collections.sort()`.

### **Advantages**
- Highly optimized and efficient.
- Supports primitive types (`int`, `double`, etc.) and objects (`String`, custom objects).

### **Code Example**
```java
import java.util.Arrays;
import java.util.Collections;
import java.util.List;

public class BuiltInSort {
    public static void main(String[] args) {
        // Sorting an array
        int[] arr = {64, 34, 25, 12, 22, 11, 90};
        Arrays.sort(arr);

        System.out.println("Sorted array: ");
        for (int num : arr) {
            System.out.print(num + " ");
        }

        // Sorting a collection
        List<Integer> list = Arrays.asList(64, 34, 25, 12, 22, 11, 90);
        Collections.sort(list);

        System.out.println("\nSorted list: ");
        for (int num : list) {
            System.out.print(num + " ");
        }
    }
}
```

### **Dry Run**
Input: `[64, 34, 25, 12, 22, 11, 90]`

1. Call `Arrays.sort()`.
2. Array after sorting: `[11, 12, 22, 25, 34, 64, 90]`.
3. Call `Collections.sort()` on list: `[11, 12, 22, 25, 34, 64, 90]`.

---

----

## Searching Algorithms

### 1. Linear Search
Linear Search sequentially checks each element of the array until the target element is found.

#### Java Code
```java
public class LinearSearch {
    public static int linearSearch(int[] array, int target) {
        for (int i = 0; i < array.length; i++) {
            if (array[i] == target) {
                return i;
            }
        }
        return -1;
    }

    public static void main(String[] args) {
        int[] scores = {12, 32, 45, 67, 88};
        int target = 45;

        int index = linearSearch(scores, target);

        if (index != -1) {
            System.out.println("Score " + target + " found at index: " + index);
        } else {
            System.out.println("Score " + target + " not found.");
        }
    }
}
```

#### Dry Run
Let’s search for `45` in `[12, 32, 45, 67, 88]`:

1. Compare 12 with 45 → Not Found
2. Compare 32 with 45 → Not Found
3. Compare 45 with 45 → Found at Index 2

---

### 2. Binary Search
Binary Search is an efficient algorithm to find an element in a sorted array. It repeatedly divides the search interval in half.

#### Java Code
```java
public class BinarySearch {
    public static int binarySearch(int[] array, int target) {
        int low = 0, high = array.length - 1;

        while (low <= high) {
            int mid = low + (high - low) / 2;

            if (array[mid] == target) {
                return mid; // Target found
            }

            if (array[mid] < target) {
                low = mid + 1; // Search the right half
            } else {
                high = mid - 1; // Search the left half
            }
        }

        return -1; // Target not found
    }

    public static void main(String[] args) {
        int[] scores = {12, 32, 45, 67, 88};
        int target = 45;

        int index = binarySearch(scores, target);

        if (index != -1) {
            System.out.println("Score " + target + " found at index: " + index);
        } else {
            System.out.println("Score " + target + " not found.");
        }
    }
}
```

#### Dry Run
Let’s search for `45` in `[12, 32, 45, 67, 88]`:

1. **Step 1:**
   - Low = 0, High = 4, Mid = (0 + 4) / 2 = 2
   - Array[Mid] = 45 → Target Found at Index 2

---

## Conclusion
- **Sorting Algorithms:** Bubble Sort, Selection Sort, and Insertion Sort are basic techniques to organize data.
- **Searching Algorithms:** Linear Search and Binary Search are useful to locate data efficiently.

By mastering these techniques, you can solve many practical problems in computer science and programming.
----
