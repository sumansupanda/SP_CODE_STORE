# INTRODUCTION.

Software is a collection of programs and a program is a collection of instruction given to the computer. Development of software is a stepwise process, before developing a software number of processes are done.

The first step is to understand the *user requirments*. *Problem analysis* arises during the requirment phase of software development. Problem analysis is done for obtaining the user requirments and to *determine the input and output* of the program. For solving any problem, an `algorithm` is implemented. *Algorithm* is a sequence of steps that gives method of solving a problem. This algorithm creates the logic of program. On the basis of this algorithm, *program code* is written. Program *testing* is performed to make sure that it gives correct result. Proper *documentation* of the program should be done so that it is easier to modify or enhance the program whenever required.

> **Process of program development.....**

__User requirements__ :arrow_right: __Problem analysis__ :arrow_right: __Determine Input and Output__ :arrow_right: __Designing algorithm__ :arrow_right: __Program coding__ :arrow_right: __Testing and Debugging the program__ :arrow_right: __Program Documentation__.

## Design Methods

*Designing* is the first step for obtaining solution of a given problem. The purpose of designing is to represent solution for a system. It is difficult to design a large system because the complexity of system cannot be represented easily. Thus various methods have been evolved for designing.

1. Top-Down Design

Every system has several hierarchies of components. The top-level component represents the whole system. Top-Down design method starts from component to lowest level(bottom) component. In this design method, the system is divided into some major components. Then each major component is divided into lower level components. Similarly other components are divided till the lowest level component.

2. Bottom-Up Design

Bottom-Up design method is the reverse of Top-Down approach. It starts from the lowest-level component to the highest-level component. It first designs the basic components and from these basic components the highest level components are designed. 

3. Modular Approach

It is better to divide a large system into modules. In terms of programming, module is logically a well-defined part of program. Each module is a separate part of the program. It is easy to modify a program written with modular approach because changes in one module don't affect other modules of program. It is also easy to check bugs in the program in module level programming.

## Programming Languages

Before learning any language, it is important to know about the various types of languages and their features. The *programming languages* can be classified into two types-

1. Low-Level Languages

The *low level languages* can further divided into two types-

+ Machine Level Language

Computer can understand only `digital signal`, which are in binary digits `i.e 0 and 1`. So the instructions given to the computer can be only in binary codes. The *machine language* consists of instructions that are in binary 0 or 1. Computers can understand only machine level language.

Writing a program in machine level language is a difficult task because it it not easy for programmers to write instructions in binary code. A machine level language program is `error-prone` and its maintenance is vary difficult. Furthermore machine language program are not portable. Every computer has its own machine instructions. So the programs written for one computer are not valid for other computer.

+ Assembly Language

The difficulties faced in machine level language were reduced to some extent by using a modified form of machine level language called *assembly language*. In assembly language instructions are given in `English` like words, such as `MOV`, `ADD`, `SUB` etc. So it is easier to write and understand assembly programs. Since computer can understand only machine level language, assembly language program must be translated into machine language. The translator that is used for translating is called `"assembler"`.

2. High-Level Languages

*High-level languages* are designed keeping in mind the features of portability i.e these languages are machine independent. These are English like languages, so it is easy to write and understand the program of high-level language. While programming in a high level language, the programmer is not concerned with the low level details, and so the whole attenton can be paid to the logic of the problem being solved. For translating a higher level language program into machine language, `compiler` or `interpreter` is used. Every language has its own compiler or interpreter. Some languages in this category are- `FORTRAN`, `COBOL`, `BASIC`, `Pascal` etc.

## Translators 

We know that computers can understand only machine level language, which is in binary 1 or 0. The code written in any high-level or low-level language should be translated into machine level language and `translator` are used for this purpose. These translators are just computer programs, which accept a program written in high-level or low-level language and produce an equivalent machine language program an output. The three types of translators used are-

+ Assembler
+ Compiler
+ Interpreter

*Assembler* is used for converting the code of low-level language(assembly language) into machine level language.

*Compilers* and *interpreters* are used to convert the code of high-level language into machine language. The high level program is known as `source program` and the corresponding machine language program is known as `object program`. Although both compilers and interpreters perform the same task, there is a difference in their working.

A compiler searches all the errors of program and list them. If the program is error free then it converts the code of program into machine code and then the program can be executed by separate commands. An interpreter checks the errors of program statement by statement. After checking one statement, it converts that statement into machine code and then executes that statement. This process continues until the last statement of program or an erroneous statement occurs.

## History Of C

In earlier days, every language was designed for some specific purpose. For example `FORTRAN (Formula Translator)` was used for scientific and mathematical applications, `COBOL ( Common Business Oriented Language)` was used for business applications. 

The C language was developed by `Dennis Ritchie` in `1970s` at `AT&T Bell Laboratories`. *Murray Hill*, *New jersey*, initially it was designed for programming in the operating system called `UNIX`. After the advent of C, the whole UNIX operating system was rewritten usign it. Now almost the entire UNIX operating system and the tools supplied with it including the C compiler itself are written in C.

The C language is derived from the `B language`, which was written by `Ken Thompson` at `AT&T Bell Laboratories`. The B language was adopted from a language called `BCPL (Basic Combined Programming Language)`, which was developed by `Martin Richards` at `Cambridge University`. 

In 1982, a committee was formed by `ANSI (American National Standards Institute)` to standardize the C language. Finally in 1989, the standard for C language was introduced known as `ANSI C`. Generally most of the modern compilers conform to this standard.

## Characteristics Of C

C is the `middle level language`. It has the simplicity of a *high level language as well as the power of a low level language*. This aspect of C makes it suitable for writing both *application and system programs*. Thus it is an `excellent`, `efficient` and `general-purpose` language for most of the applications such as `mathematical`, `scientific`, `business` and `system software applications`. 

C is small language, consisting of only 32 Engllish words known as `Keywords`. The power of C is augmented by the library functions provided with it. Moreover, the language is extendible since it allows the users to add their library functions to the library.

## Structure Of C Program

A C program is a collection of one or more functions. Every function is a collection of statements and performs some specific task. The general structure of C program is-

```
Comments
Preprocessor directives
Global variables
int main(void)
{
    local variables
    statements
    .........
    .........
    return 0;
}
func1 ()
{
    local variables
    statements
    .........
    .........
}
func2 ()
{
    local variables
    statements
    .........
    .........
}

```

*Comments* can be placed anywhere in a program and are enclosed between the delimiters `/* adn */`. Comments are generally used for documentation purposes.

Preprocessor directives are processed through preprocessor before the C source code passes through compiler. The commonly used preprocessor directives are `#include` and `#define`. #include is used for including header files. #define is used to define symbolic constants and macros.

Every C program has one or more functions. If a program has only one functios then it must be `main()`. Execution of every C program starts with main() functions. It has two parts, declarations of local variables and statements. Statements in the main() functions executed one by one. The statement `return 0;` at the end of main() means that the functions has terminated successfully. Other functions are user-defined functions, which also have local variables and C statements. They can be defined before or after main(). It may be possible that some variables have to be used in many functions, so it is necessary to declare them globally. These variables are called *global variables*.

## Compilation and Execution Of C Program

There are different phases through which our program passes before being transformed into an executable form.

The following figure shows these phases-

                            source code
                                ||
                            Preprocessor
                                ||     
                            expanded code
                                |                   
                             Compiler
                                ||     
                            assembly code
                                ||
                             Assembler
                                ||
                            object code
    other object                ||               
        files    =====        Linker    =====  libraries
                                ||
                            executable code

> Preprocessor

The source code is the code that we write using any text editor and the source code file is given an extension `.c`. This source code is firstly passed through the preprocessor. The preprocessor expands this code and passes it to the compiler.

> Compiler

The extended code is passed to the compiler. The compiler converts this code into the machine's assembly language code.

> Assembler

This assembly language code is converted to object code by the system's assembler. This name of the object file is same as that of source file. In DOS the object file has extension `.obj` and in UNIX the extension is `.o`.

> Linker

Generally all programs written in C, use library functions. Library functions are precompiled and their object code is stored in library files with `.lib (or '.a')` extension. The linker combines this object code of the library functions with the object code of the program. Our program may also contain references to functions that are defined in other files. The linker links the object code of these files also to our program. So the job of the linker is to combine the object code of our program with the object code of other files and object code of library functions. The output of the linker is an executable file. In DOS the executable file has same name as that of source code file and has extension `.exe` and in UNIX the executable file is named as a `a.out` or the name of output with `-o` option.

## Environment For C

The steps involved in developing a C program are-

1. Program Creation
2. Program Compilation
3. Program Execution

+ Unix/Linux Environment

Generally a command line C compiler is provided with the Unix/Linux operating system. This compller is named as `cc or gcc`.

- Program Creation

In unix environment file can be created with vi editor as-
```

$ vi filename.c

```
Here `$` is the unix prompt. The file can be saved by pressing `ESC and SHIFT+zz`.
