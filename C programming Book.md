What is C ?

C is a 3rd generation general-purpose (*designed to be used for writing software in a wide variety of application domains.*) , procedural( it follows order of the set of commands , first line executed first) , imperative (*step-by-step instructions for the computer)*, cross platform ( *Run on every Operating System such as Mac OS, Windows, Linux etc*) , Structural ( *It divides the problem into smaller structural blocks each of which handles a particular responsibility. like , if - else block, function block etc .*) computer programming language.

‌

In 1972, a great computer scientist Dennis Ritchie created a new programming language called 'C' at the Bell Laboratories(Now Nokia ) for UNIX operating system(*Now Mack OS , i.e. Linux is also UNIX-Like OS* ). It inherits from 'ALGOL', 'BCPL' and 'B' programming languages. Initially C was used for UNIX. But now it can be used to create any type of software. Since it was created many years ago , developers have made many updates. To assure that 'C' language will remain standard, American National Standards Institute (ANSI) defined a commercial standard for 'C' language in 1989. Later, it was approved by the International Standards Organization (ISO) in 1990. 'C' programming language is also called 'ANSI C'.

‌

Many other programming languages such as C++(Can be called the Update version of C!) ,Java is developed from C programming language. Programming language like Python (4th generation language) interpreter (CPython), and Java Compiler is written in C programming language (*i.e. Today, the Java compiler is written in Java, while the JRE is written in C*.).



Where C programming language is used.

C programming language was first developed in Bell Telephone Laboratories to develop the UNIX operating system.So, we can say that C was initially used for Operating System development. But now it can be used for any purpose. Some common purpose is given bellow

‌

- Operating Systems
- Language Compilers
- Assemblers
- Text Editors
- Print Spoolers
- Network Drivers
- Modern Programs
- Databases
- Language Interpreters
- Utilities
- IOT applications.
- Web Browsers




Why to learn C

C is the base of other programming languages . Other Programming languages like C++,PHP,Java, JavaScript,Dart are directly or indirectly have borrowed syntax/features from C programming language. So, By learning C programming language we can easily switch to other programming languages .

‌

C produces efficient programs , It can handle low-level activities .And it is faster than any other 3rd generation languages. C is fast, like nearly assembly language . And The GNU **C supports** the x86(32 bit) architecture quite well, and includes the ability to insert **assembly code** within **C** programs . Those features make C a more powerful language .Since C is simple and fast programming , it is widely used in the software industry to create various application software. There are many jobs available for a 'C' developer in the current market.

‌

Also C is Simple,Machine Independent or Portable,Rich Library, Memory Management, Fast Speed, Pointers, Recursion, Extensible .

C Environment Setup

If you want to make a program using C , you definitely need a Text Editor (Where you write your C programming code) and a C Compiler (which turns your code to machine readable instructions) installed on your computer.

Text Editor:

A text editor is a type of computer program that edits plain text files. You can edit plain text , save ,and print(open text for reading plain text).

Visual Studio Code(I personally use this), Sublime Text, Atom, Notepad++ are some popular Text Editors for all platforms (Windows ,Mac ,Linux ) .

All C Program file must have extension .c 

C Compiler:

As C is a 3rd generation language , it’s code is readable for humans not for the computer.
Computers only understand the machine language . So we need another software that works like a bilingual . It translates our C code to machine readable code. 

Some C compilers are **Turbo C , Tiny C ,Portable C Compiler, GNU Compiler Collection (GCC),    Clang**

To write a C program you need one of the text editors and one of the compilers .
Or you can use C IDE(i*ntegrated development environment* ) .Which is a combination of Text Editor and Compiler with debug facility. 

Code::Blocks is a *free C, C++ IDE* created to meet the most demanding needs of the developers of C and C++. This is an IDE with all the features you need for C and C++ development


Netbeans C++ IDE consists of a lot of project-based templates for C and C++, that provides the capability to build applications with dynamic and static libraries in C and C++. It consists of amazing features that make it more popular among web developers.


Eclipse is one of the most popular and powerful IDE’s For C/C++ which offers open-source utility and functionality for C and C++ programmers. New users can find this IDE as simple to use and work upon




C Programming Language Structure

Basic Syntax of C programming language Which you must have to write to create a C program.


#include<stdio.h>

int main()

{

`   `//Your Code here

`   `printf("Hello world!");


`   `return 0;

}

‌

Here, in first line , #include<stdio.h> here '#include' is a pre-processor , pre-processors instructs the compiler to do required pre-processing before the actual compilation. All preprocessor commands begin with a hash symbol (#). Some other pre-processors are ( **#define , #undef , #ifndef )**

‌

If we want a to use others library ( build in or our created ) we have to include the library header using '#include' preprocessor .

‌

Here 'stdio.h' is a header file. It's a standard file for input and output files. The 'stdio' is the acronym of "Standard Input and Output " and all header files have extension .h here '.h' represents that it is a header file. The in build library lies between < library name > . And our own build library lies between double inverted commas . ie. " library name". then the syntax shall be #include " library name ". (*ie. you have to use quote instead of angular brackets*)

‌

And a library is a collection of functions and variables . (we will discuss more about the function below).

‌

'int main() ', here 'int' is a return type . 

return type means which type of data the function will return.

the return types are ( int ,char, float, double and void ) 

here int (integer number   i,e. 1,5, -10 , 0 etc. ) , char (character i.e. 'a','c','y','1' etc. ) 

float (floating number i.e. 1.5,8.6,9.8 etc. ) double ( it’s also a floating number )

main(){} is a function. printf() is a function defined in the stdio.h header file.


Data Type In C 

Data are units of information . We can also say “data are a set of values of qualitative or quantitative variables about one or more persons or objects”. Your information like name ( mine “sanzid”) , age (mine 23), height ( mine 5”6’) , weight ( 46kg) e.t.c. .

Here we can define all the informations in some category , 

1. A set of characters (i.e. ‘A’,’B’, ‘x’ ‘s’,’1’,’6’ e.t.c)
1. Numeric values.

Numeric values can also be integer or floating values .

And all the information above mentioned can also be considered as a man’s basic data.

In, C programming language we have  two types of data (data type).

1. Primitive ( C programming default / basic )
1. Derived ( aggregation of primitive data types)

C programming language has 4 basic data types.

1. int (to represent integer data )
1. char ( to represent character data)
1. float ( to represent floating point data )
1. double (to represent floating point data like float , but it contains more accurate values than float)

C programming language is system architecture dependent. Means , it’s primitive data type varies on system architecture(x32 bit, x64 bit).

1. int  Data type:
1. It stores integer numeric values.
1. The size can be 2,4 or 8 byte (  *bit is the acronym of “binary digit “ ) is the smallest unit of data in a computer. A **bit** has a single binary value, either 0 or 1. And 1 byte = 8 bit)*
1. *int (2 byte) can store values from -32,768 to +32,767 (i.e. 16 bit computer takes 2 bite default )*
1. *int (4 byte) can store values from -2,147,483,648 to +2,147,483,647. (i.e. 32,64 bit computer takes it default )*
1. For safety , if you want to store from -32,768 to +32,767  use **short int** rather than int,  from -2,147,483,648 to +2,147,483,647 use **long int** rather than int, and if you want to use 8 bit (10^18) then use **long long int** rather than int.

\2. float Data type:

1. It is used to store decimal numbers (*numbers with floating point value*) with single precision.
1. float storage size is 4 byte . float precision after decimal point is 6( *it gives the accurate value of 6 digits after decimal point*) .
1. i.e.  458.75896 

\3.  double Data type:

1. double is also used to store decimal numbers like float data type.
1. double storage size is 8 byte . and double precision after decimal point is 10 (*it gives the accurate value of 10 digits after decimal point)*
1. *i.e. 8545.87632689656*
1. *To store bigger numbers we can use ‘long double ‘ .* 
1. *double can store 10^15 and long double can store 10^19 .*

*4.* char Data Type:

1. char  is used to store  characters- things like letters, punctuation, and spaces. In a computer, characters are stored as numbers, so char holds integer values that represent characters. The actual translation is described by the ASCII standard .
1. char storage size is 1 byte ( 8 bits) . 
1. It can store numbers between -128 to 127 or 0 to 255.

\5. void Data Type:

1. void means nothing. void is an  empty data type that contains no  value. We use void data type in functions when we don’t want to return any value to the calling function (We will discuss later about function). If we use void data type in any function , we can’t return any value, but we can use return keyword, with no value.
1. C uses void for another purpose, void pointer(We will discuss later about pointers). void pointer means initially it does not contain any data type and it acts like a generic data type. And we can point any data using a void pointer , but while dereferencing we must use explicit type casting ( We will discuss later about type casting ).


Function in C programming : 

Basically a function in programming is like a mathematical function . 

A function is a block of code that takes zero or more parameters/ arguments, does something with these parameters and returns something. (ie. f(x) = x2+ 5, in this function if we pass f(2) = 22+ 5 = 9. From the following mathematical function we get  the output, the computer programming functions deal the same. )

In c programming ,we must create a function named main(){}. Because the c compiler starts executing the program from the main function. And after main we have a pair of parentheses and after that we have curly braces. We pass arguments in the parentheses , and all our statements are in the curly braces.

And there are also many standard library functions , such as printf() [is used to print something in console],scanf() [ is used to take input from console ] etc.

And we also can create our own function.


Rules of semicolon

1. Semicolons are the end statement in c
1. The semicolon tells that the current statement has been terminated and other statements following are new statements.
1. Usage of semicolons in C will remove ambiguity and confusion while looking at the code.
1. They are not used in between the control flow(We will discuss it letter) statements but are used in separating the conditions in looping.




Comments In C

Computer programming is the giving instructions to the machines . What we write is for computers, Human beings can't easily understand those codes. For helping others to understand those codes easily we simply leave notes .So that we can understand why the programmer made those statements. And the C compiler ignores those comments to execute.

In C programming language , We can use use two types of comment 

1. Single line comment, “//” double forward slash .
1. Multi line comment , “/\*     multi line comments \*/ “ One forward slash and an asterisk symbol is the starting of comments and an asterisk and forward slash means the end of comment.

// this is the single line comment.

/\* 

Here is the multi line comments

We can use any number of lines comment

Everything will be ignored by the C compiler


\*/

It is a good practise to write down the comments while programming, Other programmers and many days later it will also help you to easily understand those blocks of statements and you can reuse and modify them easily.


Return Statement

C return statement is used for terminating the function with some value (defined in function return type) . A function must have to set a return type before declaring a function.if we need not to return any value from where the function is called , we use “void “ return type. 




C compilation process

Compilation

Compilation is the process of making the source code (.c file) into a machine readable instruction object code(.o file) code. As C is a mid level language , we need to make it machine readable code through a compiler.

The compiler checks source code for any syntactical or structural errors and generates object code with extension **.obj** (in Windows) or **.o** (in Linux) if source code is error free.

**The compilation process has four stapes:**

1. Pri-processing
1. Compiling
1. Assembling
1. Linking

Pri-processing :

The source code first goes through pri-processor , on that stage it does several deeds

1. Remove unexpected white spaces and comments form the source code.
1. It adds all the required libraries for the source code.(if we include our own created separate .c or .h file )
1. Replace all the macros (#define preprocessor) to the original values.

After doing this it generate a  (filename).i or (filename).ii file,

Compiling :

After finishing pre-processing process a temporary .i or .ii file is created and the compiler does several deeds of that .ii or .i file

1. Checks whether the source code is syntactically correct.
1. Optimize the code
1. Convert .i or .ii file to assembly code

And generate (filename).s assembly code.



Assembling :

In this phase, the assembler converts the assembly code(generated by compiler) to the machine readable object code (filename).o file. It is not human readable , and the text editors can’t also show that code.

Linking:

C linker links oue object files together . C library functions are previously  compiled,and are in .dll(windows) or .a(Mac or Linux) .our code object file should have to link to those object files, and if we want to add another object file to our code linker plays a vital role in this scenario . And after combining all those object files, linker generates an executable program on Windows (.exe) and linux or mac it generates (a.out) runnable scripts.

gcc filename.c -save-temps -Wall -o (output file name)

Tokens

Tokens are the smallest individual units that make up a complete C program. They are like cells of a human body, or bricks of a building.

C tokens are categorized in 6 categories,

1. Keyword
1. Identifier
1. Constant
1. Strings
1. Operators
1. Punctuators 

Keyword:

Keywords are the reserved words or pre-defined words whose meaning is already known to the compiler. Each keywards has different meanings to the compiler and it can’t be changed.Means that each keyword performs a particular task and we can’t use those keywords to name identifires . We are allowed to use those keywords for which exact purpose they are created.

There are 32 keywords in the C programming language.





|auto|double|int|struct|
| :- | :- | :- | :- |
|break|else|long|switch|
|case|enum|register|typedef|
|char|extern|return|union|
|const|float|short|unsigned|
|continue|for|signed|void|
|default|goto|sizeof|volatile|
|do|if|static|while|


Identifiers :

Identifiers are the name given to variables, constants, functions and user-defined data. Identifiers are the name you give to a variable , function ,array, pointer etc. so that we can reuse those values using those names. Identifiers is a user defined name to identify an entity. It must have to be unique and can’t be the keywords. There are some rules in C programming language to create Identifiers also known as naming conventions of C programming language.

\1.     The first character in an identifier must be an alphabet or an underscore and can be followed only by any number of alphabets, or digits or underscores.

\2.     They must not begin with a digit.

\3.     Uppercase and lowercase letters are distinct. That is, identifiers are case sensitive.

\4.     Commas or blank spaces are not allowed within an identifier.

\5.     Keywords cannot be used as an identifier.

\6.     Identifiers should not be of length more than 31 characters. (though there is no limits but  the compiler considers the first 31 characters only)

\7.     Identifier names must be unique.

By following the rules you are free to give any name to your identifier , but you should always try to give a meaningful  and easy to use and read name to your identifier. So that , someone  can easily get an idea about the idea of an identifier only by reading the name of the identifier. It will also help you to read your code many days later.

Some valid Identifiers : 




Loop

Loop means perform the same task again and again. In programming sometimes we need to do the same task again and again . 



For()

while()

Do{

}while()




Recursion :

Recursion is a process of calling a function by itself  directly or indirectly
