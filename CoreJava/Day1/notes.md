Day 1 - Java Notes :
-----------------
Java is a popular programming language, created in 1995. It is owned by Oracle, and more than 3 billion devices run Java.
It is used for:
- Mobile applications (specially Android apps)
- Desktop applications
- Web applications
- Web servers and application servers
- Games
- Database connection

Why we use Java?
Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
- It is one of the most popular programming languages in the world
- It has a large demand in the current job market
- It is easy to learn and simple to use
- It is open-source and free
- It is secure, fast and powerful
- It has huge community support (tens of millions of developers)
- Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs
- As Java is close to C++ and C#, it makes it easy for programmers to switch to Java or vice versa.


Java Syntax:
-----------
- In Java, every application begins with a class name, and that class must match the filename.
- Every line of code that runs in Java must be inside a class. The class name should always start with an uppercase first letter. 
- Note: Java is case-sensitive. MyClass and myclass would be treated as two completely different names.
- The name of the Java file must match the class name. So if your class is called Main, the file must be saved as Main.java. This is because Java uses the class name to find and run your code. If the names don't match, Java will give an error and the program will not run. 
- When saving the file, save it using the class name and add .java to the end of the filename. 

Code:
----
public class HelloWorld {
   public static void main(String[] args) {
       System.out.println("Hello World");
   }
}

- The main() method is required in every Java program. It is where the program starts running.
- Any code placed inside the main() method will be executed.
- Inside the main() method, we can use the println() method to print a line of text to the screen.
- System is a built-in Java class.
  out is a member of System, short for "output".
  println() is a method, short for "print line".
- Note: The curly braces {} mark the beginning and the end of a block of code.
- Finally, remember that each Java statement must end with a semicolon (;).

Java Statements:
---------------
- A computer program is a list of "instructions" to be "executed" by a computer. 
- In a programming language, these programming instructions are called statements. 
- The following statement "instructs" the compiler to print the text "Hello World" to the screen:
  System.out.println("Hello World!");

Java Output:
-----------
- We can use the println() method to output values or print text in Java.
  System.out.println("This is NIKHIL");
- You can add as many println() methods as you want. Note that it will add a new line for each method.
- Text must be wrapped inside double quotations marks "". If you forget the double quotes, an error occurs.
- print() vs println() : The only difference is that print() does not insert a new line at the end of the output.

Code:
----
System.out.print("Hello World! ");
System.out.print("I will print on the same line.");

Output:
------
Hello World! I will print on the same line.










