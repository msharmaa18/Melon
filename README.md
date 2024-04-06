# Melon
Introducing Melon: A C-based Compiler for Smooth Programming

Melon is a compiler targeted at programmers who enjoy the familiarity and power of C, but also crave a more streamlined development experience. Built on top of C, Melon offers a higher level of abstraction while maintaining the efficiency and control C is known for.

**Key Features:**

* **C-based Core:** Melon leverages the robust foundation of C, ensuring efficient code generation and seamless integration with existing C libraries.
* **Simplified Syntax:** If you're comfortable with C, picking up Melon will be a breeze. Its syntax is designed to be more concise and easier to read, reducing boilerplate code and improving readability.
* **Compiler Power:** Melon translates your Melon code into optimized C code, ensuring your programs run efficiently and fully utilize your system's capabilities.

**Benefits:**

* **Faster Development:** Melon's cleaner syntax allows you to write code quicker and focus on the core logic of your application.
* **Improved Maintainability:** With its focus on readability, Melon code is easier to understand and maintain for you and your collaborators.
* **Leverage C Ecosystem:** Melon's C foundation grants you access to C libraries and tools, expanding your programming possibilities.

**Who is Melon For?**

Melon is ideal for programmers who:

* Have a strong understanding of C and want a more streamlined development experience.
* Appreciate the efficiency and control of C, but also desire a more readable syntax.
* Want to build performant applications without sacrificing development speed?

**Operating Melon Compiler**

An assembler compiler with special instruction sets written in C language.


# Melon Assembler Compiler
An assembler compiler with special instruction sets written in C language.

## Tokenizer
Let's run the makefile first and then the main.exe.
```
mingw32-make & main
```
&nbsp;

Let's write the path of the file to be tokenized in the path part. (if the file is in the same directory you can just type its name)
```
source
```
### SS
![image](https://user-images.githubusercontent.com/71611710/215190992-a55f4913-0435-4c2e-b62b-64d1ec5a3b55.png)
&nbsp;

## Parser
Compile and run.
```
gcc parser.c -o parser & parser
```
&nbsp;

Let's write the path of the file to be compiled in the path part. (if the file is in the same directory, just type its name)
```
source2
```
### SS
![image](https://user-images.githubusercontent.com/71611710/215195209-399bd11f-990d-43dd-b236-43a01f588435.png)

&nbsp;

## Assembler
Compile and run.
```
gcc assembler.c -o assembler & assembler
```
&nbsp;

Let's write the path of the file to be compiled in the path part. (if the file is in the same directory, just type its name)
```
source3
```
&nbsp;

source3 - Program to add numbers from 1 to 10 - The result is inside the AX register
```
HRK AX, 0
HRK BX, 1
HRK CX, 11
loop:
	TOP AX, BX
	TOP BX, 1
	HRK DX, BX
	CIK DX, CX
	SN loop
```

### SS
![image](https://user-images.githubusercontent.com/71611710/215197509-30974e41-2242-403d-abf6-6bc8962fc97d.png)
&nbsp;

