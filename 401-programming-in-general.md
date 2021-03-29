# Compiled vs Interpreted

|---|Compiled|interpreted |
|---|--------|--------|
|how to work|converted directly into machine code that the processor can execute|Interpreters run through a program line by line and execute each command.|Interpreters run through a program line by line and execute each command.|
|speed|faster and more efficient to execute|slower.But, with the development of just-in-time compilation, that gap is shrinking|
|need a “build” step |need to be manually compiled first. You need to “rebuild” the program every time you need to make a change||
||give the developer more control over hardware aspects, like memory management and CPU usage||
|Examples|C, C++, Erlang, Haskell, Rust, and Go|PHP, Ruby, Python, and JavaScript|
|Advantages |Programs that are compiled into native machine code tend to be faster| more flexible,offer dynamic typing and smaller program size,the code itself is platform independent|
|Disadvantages|Additional time needed to complete the entire compilation step before testing Platform dependence of the generated binary code|typical execution speed compared to compiled languages|

## A Small Caveat
- Most programming languages can have both compiled and interpreted implementations 
– for simplicity’s sake, they’re typically referred to as such.
## Examples :
- Python,can be executed as either a compiled program or as an interpreted language in interactive mode.
- Most command line tools,CLIs, and shells can theoretically be classified as interpreted languages.

