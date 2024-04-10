# pw_assignment_1
java course first assignment

      ** Basic computer **

1. What is a Computer?
Ans: Computer is an electronic device for storing and processing data, typically in binary form, according to
instructions given to it in a variable program.

2. What is RAM?
Ans: RAM which stands for Random Access Memory, is a hardware device generally located on the
motherboard of a computer and acts as an internal memory of the CPU. It allows CPU store data, program, and
program results when you switch on the computer.

3. Where is data stored in a computer?
Ans: CPU

4. What is that input device used to type text and numbers on a document in the computer system?
Ans: Keyboard

5. What are the output devices?
Ans: Output devices are: Monitor, Printer, etc.

6. Which is the input device that allows a user to move the cursor or pointer on the screen?
Ans: Mouse

7. Which language is directly understood by the computer without a translation program?
Ans: Machine Language or machine code, is a low-level language composed of binary digits (ones and zeros).

8. What are Input devices?
Ans: Input devices are: Keyboard, Mouse, Joystick..


          ** Fundamentals of Java **

1. What Ps ProgrammPng language?
Ans: Programming is a practice that strengthens our capacity for logical thought and problem-solving. It
teaches us how to carry out a task with the aid of software or a computer program. So, to put it simply,
programming is the process of using computer language to bring a solution to a problem into practice.

2. Why do we need a programmPng language?
Ans: Programming Language- it is vocabulary and a collection of rules that command a computer, devices,
applications to work according to the written codes. The programming language enables us to write efficient
programs and develop online solutions such as- mobile applications, web applications, and games, etc.
Programming is used to automate, maintain, assemble, measure and interpret the processing of the data and
information. It helps in accelerating the input and output of the devices or applicationsJ

3. Features of 1avO
0 Object-Oriented - The features of object-oriented programming are supported by Java. Its object model is
straightforward and flexibleI
0 Platform independent - Because Java and C++ are platform independent, application programs created in
one Operating system can run on any other Operating system. C and C++, however, are platform
dependent languages, making it impossible for application programs created in one Operating system to
run in any other Operating systemI
0 Simple - Because Java incorporates many C/C++ capabilities, it is simple to understandI
0 Secure - Java offers a variety of defences against malware and viruses. It guarantees that neither damage
nor security will be compromisedI
0 Portable - We have the idea of portability in Java. Java allows the same software to run on various
platformsI
0 Robust - It assists us in identifying potential errors as soon as feasible during program developmentI
0 Multi-threaded - Java's multithreading programming capability enables you to create a program that
executes multiple tasks concurrentlyI
0 Distributed -Java maintains the TCP/IP protocol and is therefore suitable for distributed Internet
environmentsJ

4. What Ps an Object?
Ans: An object is an entity with state and behaviour, such as a chair, bike, marker, pen, table, or car. It could be
intellectual or physical (tangible and intangible). The banking system is an illustration of an intangible entityJ

5. What Ps a Class?
Ans: A class is a collection of items with similar characteristics. It serves as a model or blueprint from which
things can be made. It makes sense as a whole. It cannot be bodilyJ

6. ExplaPn about the java maPn() method?
Ans: The main () is the starting point for JVM to start execution of a Java program. Without the main () method,
JVM will not execute the program. The syntax of the main () method is: public: It is an access specifier. We
should use a public keyword before the main () method so that JVM can identify the execution point of the
program.

public: An access specifier, that is. Before calling the main() method, we need to use the public keyword to let
the JVM know where the programme is actually being executed. Before the main() method, if we use private,
protected, and default, the JVM won't be able to see it.

static: You can make a method static by using the keyword static. We should call the main() method without
creating an object. Static methods are the method which is invoked without creating the objects, so we do not
need any object to call the main() method.

void: In Java, every method has the return type. Void keyword acknowledges the compiler that the main()
method does not return any value.

main(): It is a default signature which is predefined in the JVM. It is called by JVM to execute a program line by
line and end the execution after completion of this method. We can also overload the main() method.
String args[]: The main() method also accepts some data from the user. It accepts a group of strings, which is
called a string array. It is used to hold the command line arguments in the form of string values.

Here, agrs[] is the array name, and it is of String type. It means that it can store a group of strings. Remember,
this array can also store a group of numbers but in the form of string only. Values passed to the main() method
are called arguments. These arguments are stored into an args[] array, so the name args[] is generally used for it  


                 ** Java Variables and Data types **

1. What is statically typed and Dynamically typed Programming Language?
Ans: Statically typed: if the memory of the variable is given during the compilation time itself then such types of
programming languages are called as “Statically typed”.
Eg: C,C++,Java
Dynamically typed: If the memory of the variable is given during the execution time itself then such types of
programming languages are called as “dynamically typed”.
Eg: Python,PHP,JavaScript

2. What is the variable in Java?
Ans: A variable is the title of a reserved region allocated in memory. In other words, it may be referred to as the
name of a memory location.
It is a container that holds the value while the Java Program is executed.
Each variable should be given a unique name to indicate the storage area.
A variable is assigned with a data type(we will learn about it after this topic).
Syntax for Declaring a Variable:
Type variable_name [= value];
The variable_name is the name of a variable. We can initialise the variable by specifying an equal sign and a
value (initialization i.e. assigning an initial value, is optional). However, the compiler never assigns a default
value to an uninitialized local variable in Java.

3. How To Assign a Value To Variable?
Ans: We use assign operator (=) to assign a value to a variable. For Example,
number = 10;
flag = true;
name = "CodePumpkin";
We can assign a value to a variable any number of times in Java, but when we assign a new value to a
variable, the old value will be overwritten.
For example, in the first code snippet, we have first assigned a value 10 to the number and then modified its
value by performing the number+20 operation and assigning it back to the variable number by .

4. What are Primitive Data types in Java?
Ans: byte, short, int, long, float, double, char, String, boolean.

5. What are the Identifiers in Java?
Ans: Identifiers in Java are symbolic names used for identification. They can be a class name, variable name,
method name, package name, constant name, and more. However, In Java , There are some reserved words  that can not be used as an identifier.

6. List the Operators in Java?
Ans: Operators in JavaF
D Arithmetic Operator_
D Relational Operator_
D Logical Operator_
D Assignment Operator_
D Unary Operator_
D Bitwise Operators

7. Explain about Increment and Decrement operators and give an examples
Ans: Increment and Decrement Operators in Java are used to increase or decrease the value by 1. For example,
Incremental operator ++ is useGul to increase the existing variable value by 1 (i = i + 1). Moreover, the decrement
operator – – is useGul to decrease or subtract the current value by 1 (i = i – 1). The syntax oG both increment and
decrement operators in Java Programming to preGix or postGix is
Increment Operator E ++x or x++
Decrement OperatorE --x or x-
       

         
