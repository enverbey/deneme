# 🚀 Java Introduction

Welcome to the **Java Basics** repository! In this section, we will cover the fundamentals of Java, including setting up your environment and writing your first Java program.

---

## 🤔 Why Java?

Java is a **high-level, object-oriented programming language** that is widely used for building **robust and scalable applications**. One of the main reasons Java became so popular is its platform independence. Java code can run on **any machine** that supports the **Java Virtual Machine (JVM)**, meaning you write your code once and run it anywhere!

Java was introduced in 1995 by Sun Microsystems (now part of Oracle). When it was first released, its **platform independence** feature was revolutionary compared to competitors like C/C++, where developers had to write separate versions of their applications for different operating systems. 

Java offers several advantages:
- 🏆 **Widest Used Language**: Java consistently ranks among the most used programming languages globally, powering everything from web applications to mobile and desktop solutions.
- 🔧 **Automatic Memory Management**: One of the standout features of Java is its **automatic memory management (Garbage Collection)**. In contrast to languages like C/C++, where you have to manually allocate and deallocate memory, Java takes care of this for you. This makes development much easier and helps to prevent common memory-related bugs such as memory leaks. We'll cover this topic in greater detail later in the course.
- 📚 **Strong Ecosystem**: Java has a rich set of libraries, frameworks, and tools that make development easier, faster, and more reliable.

## 🛠️ Setting up Java

1. **Install JDK (Java Development Kit)**: You can download the JDK from the [official Oracle website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or use [OpenJDK](https://openjdk.java.net/). Make sure to set up the `JAVA_HOME` environment variable correctly.
2. **Choose an IDE**: We recommend using popular IDEs like [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) or [VS Code](https://code.visualstudio.com/) with the Java extensions for efficient development.

---

## 👨‍💻 Hello World Program

Below is a simple example of a **Hello World** program in Java:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Let's break it down and understand the key parts of this code:

- **`System`**: This refers to the **System** class in the `java.lang` package, which provides several useful methods and fields. In our case, we are using `System` to access the **standard output stream**.

- **`out`**: This is a static field in the `System` class. It is an instance of `PrintStream` that is used to send output to the console. When you want to print something to the screen, you use `System.out`.

- **`println`**: This is a method of the `PrintStream` class. It prints a message followed by a new line (`ln` stands for line). If we wanted to print without moving to the next line, we could use `print()` instead.

### 🤓 How does `System.out.println` work?
When you call `System.out.println()`, it works like this:
- `System`: The class that gives us access to useful resources like input, output, and error streams.
- `out`: A static member of `System` that represents the standard output (usually the console).
- `println`: The method that prints a string (or other data types) and moves to the next line.

In summary, `System.out.println` can be read as:
- "Access the `System` class."
- "Use the `out` field to access the output stream."
- "Call the `println` method to print a message."

---

## 💡 Additional Notes:
- Java is **case-sensitive**, so be sure to write `System.out.println` exactly as shown.
- You can also use `System.out.print()` to print without adding a new line after the message.

---

## 🎥 Recommended Videos on OOP

1. [Object-oriented Programming in 7 minutes | Mosh](https://www.youtube.com/watch?v=pTB0EiLXUC8)  
   
2. [Oop Gerçekte Nedir ? Nesne Yönelimli Programlama](https://www.youtube.com/watch?v=tXQD9VKVmVM)

---

## 📧 Contact Information

If you have any questions or need assistance, feel free to reach out to me:

📧 **Email:** [enverbey1534@gmail.com](mailto:enverbey1534@gmail.com)

---

## 🎯 What's Next?

In the next section, we will dive into **Java variables and data types**, exploring how to store and manipulate data in Java. Stay tuned!

