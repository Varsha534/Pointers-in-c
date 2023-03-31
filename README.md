# Pointers-in-C

What are Pointers?
A pointer is a variable whose value is the address of another variable, i.e., direct address of the memory location. Like any variable or constant, you must declare a pointer before using it to store any variable address. 

Syntax of C Pointers
datatype * pointer_name;

How to Use Pointers?
To use pointers in C, we must understand below two operators:

1. Addressof Operator
The addressof operator ( & ) is a unary operator that returns the address of its operand. Its operand can be a variable, function, array, structure, etc.

Syntax of Address of Operator
&variable_name;

2. Dereferencing Operator
The dereference operator ( * ), also known as the indirection operator is a unary operator. It is used in pointer declaration and dereferencing.

C Pointer Declaration:
In pointer declaration, we only declare the pointer but do not initialize it. To declare a pointer, we use the * dereference operator before its name.

data_type * pointer_name;
The pointer declared here will point to some random memory address as it is not initialized. Such pointers are also called wild pointers that we will study later in this article.

C Pointer Initialization: 
When we assign some value to the pointer, it is called Pointer Initialization in C. There are two ways in which we can initialize a pointer in C of which the first one is:

Method 1: C Pointer Definition
datatype * pointer_name = address;
The above method is called Pointer Definition as the pointer is declared and initialized at the same time.

Method 2: Initialization After Declaration
The second method of pointer initialization in C the assigning some address after the declaration.

datatype * pointer_name;
pointer_name = addresss;
