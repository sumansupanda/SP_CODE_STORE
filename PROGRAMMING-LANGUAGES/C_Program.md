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
