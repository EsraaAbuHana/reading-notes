# Compiled vs Interpreted

|---|Compiled|interpreted |
|---|--------|--------|
|how to work|converted directly into machine code that the processor can execute|Interpreters run through a program line by line and execute each command.|
|speed|faster and more efficient to execute|slower.But, with the development of just-in-time compilation, that gap is shrinking|
|need a “build” step |need to be manually compiled first. You need to “rebuild” the program every time you need to make a change||
||give the developer more control over hardware aspects, like memory management and CPU usage||
|Examples|C, C++, Erlang, Haskell, Rust, and Go|PHP, Ruby, Python, and JavaScript|
|Advantages |Programs that are compiled into native machine code tend to be faster| more flexible,offer dynamic typing and smaller program size,the code itself is platform independent|
|Disadvantages|Additional time needed to complete the entire compilation step before testing , Platform dependence of the generated binary code|typical execution speed compared to compiled languages|

## A Small Caveat
- Most programming languages can have both compiled and interpreted implementations 
– for simplicity’s sake, they’re typically referred to as such.
## Examples :
- Python,can be executed as either a compiled program or as an interpreted language in interactive mode.
- Most command line tools,CLIs, and shells can theoretically be classified as interpreted languages.

# [Middle ground? JIT Compilation](https://finematics.com/compiled-vs-interpreted-programming-languages/)
So far it looks like both of the languages compiled and interpreted have their pros and cons.

What if I tell you you could still achieve the speed of a fully compiled language without sacrificing portability and faster compilation time? Sounds impossible? This is where JIT compilation comes to play.

JIT or just-in-time compilation is a hybrid between normal compilation also called ahead-of-time compilation and interpretation. Instead of translating each statement from the input file (which is usually bytecode), JIT has the ability to store already compiled machine code so it doesn’t have to translate it each time.

JIT compilation works by analysing the code that is being executed (usually bytecode) and making decisions which parts of the code should be fully compiled to machine code based on how often that piece of code is being executed (and a few other factors).

The main benefit of this approach is high execution speed as all the critical and often executed code fragments are fully compiled into machine code. This comes at a cost of a bit slower execution during the initial period when the critical code fragments are being analysed and are not fully compiled yet.

A full explanation of the JIT compilation process is outside of the scope of this video, but I’m thinking about creating another one dedicated to the JIT compilation as this is a super interesting process that not everyone fully understands.

Some of the languages that make use of JIT compilation are Java, C#, Pypy (alternative Python implementation) and V8 (Javascript engine).
## Summary

|compiled|	interpreted|	JIT-compiled|
|--------|-------------|--------------| 
|execution speed|	fast|slow	usually fast (depending on the JIT implementation)|
|portability|	poor|	good|	good|
|compilation time	|slow	|fast (bytecode)|	fast (bytecode)|

# [Multithreading in Java](https://www.guru99.com/multithreading-java.html#:~:text=MULTITHREADING%20in%20Java%20is%20a,runs%20parallel%20to%20each%20other)
![](https://pediaa.com/wp-content/uploads/2019/02/Difference-Between-Single-Thread-and-Multi-Thread-in-Java-Comparison-Summary.jpg)

## Summary:

- In multithreading, users are not blocked as threads are independent and can perform multiple operations at time
- Various stages of life cycle of the thread are,
 - New
 - Runnable
 - Running
 - Waiting
 - Dead
- We also learned about synchronization between threads, which help the application to run smoothly.
- Multithreading makes many more application tasks easier.

# [Multithreading in Java?](https://www.guru99.com/multithreading-java.html#:~:text=MULTITHREADING%20in%20Java%20is%20a,runs%20parallel%20to%20each%20other)
## What is it?
- Is a process of executing two or more threads simultaneously to maximum utilization of CPU.
## How its work?
- Multithreaded applications execute two or more threads run concurrently.Known as Concurrency in Java.
- Each thread runs parallel to each other.
## why use it ?
- Mulitple threads don't allocate separate memory area.
- they save memory.
- context switching between threads takes less time.
## Advantages of multithread:

- The users are not blocked because threads are independent, and we can perform multiple operations at times
- As such the threads are independent, the other threads won't get affected if one thread meets an exception.
# ![](https://i.stack.imgur.com/m0upc.jpg)
# ![](https://www.scientecheasy.com/wp-content/uploads/2020/07/java-object-lock.png)

# Code Conventions for the Java Programming Language: 9. Naming Conventions
# Naming conventions

# Interpreted vs Compiled Programming Languages: What's the Difference?
# What is the difference between a compiled and an interpreted program?


