# Pointers
Pointers are symbolic representations of addresses. They enable programs to simulate call-by-reference as well as to create and manipulate dynamic data structures.
## THEORY
Iterating over elements in arrays or other data structures is one of the main use of pointers.<br>
The address of the variable you’re working with is assigned to the pointer variable that points to the same data type (such as an int or string).<br>
The reason we associate data type with a pointer is that it knows how many bytes the data is stored in. When we increment a pointer, we increase the pointer by the size of the data type to which it points.<br>

## ALGORITHM
1)Start<br>
2)Declare a character array str and initialize it with the string "Hello, world!".<br>
3)Declare a character pointer ptr and set it to point to the first character of the str array.<br>
4)Enter a while loop to iterate through the characters of the string until the null terminator ('\0') is reached:<br>
a. Check if the character pointed to by ptr is not equal to the null terminator.<br>
b. If true, increment the ptr to point to the next character.<br>
c. Repeat steps a and b until the null terminator is encountered.<br>
5)Calculate the length of the string by subtracting the address of the start of the array (str) from the current address of ptr.<br>
6)Display the length of the string to the console.<br>
7)End<br>

## CONCLUSION
Hence in this repository programs like calculating length of string using pointers was done. 


