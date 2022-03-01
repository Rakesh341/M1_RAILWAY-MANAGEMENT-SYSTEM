# Usage of Preprocessors in C

* The C preprocessor is a macro processor that is used automatically by the C compiler to transform your program before actual compilation. It is called a macro processor because it allows you to define macros, which are brief abbreviations for longer constructs.

 ## The C preprocessor provides four separate facilities that you can use as you see fit:

* Inclusion of header files. These are files of declarations that can be substituted into your program.

* Macro expansion. You can define macros, which are abbreviations for arbitrary fragments of C code, and then the C preprocessor will replace the macros with their definitions throughout the program.

* Conditional compilation. Using special preprocessing directives, you can include or exclude parts of the program according to various conditions.

* Line control. If you use a program to combine or rearrange source files into an intermediate file which is then compiled, you can use line control to inform the compiler of where each source line originally came from.











## Here are the below steps to run the code
 
 * For Running and Building the code
   * Type make run in terminal
 * For Running the Building tests
   * Type make run_test in terminal
 * For static analysis
   * Type make static_analysis in terminal
 * For dynamic analysis
   * Type make dynamic_analysis in terminal
 * For code coverage
   * Type make coverage in terminal
 * For cleaning
   * Type make clean in terminal
