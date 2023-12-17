# Simple Stack Based Virtual Machine

A simple stack based virtual machine, using simple virtual machine concepts.

* The `c` is for pushing bytes
* The `e` is used to emit bytes
* The `h` halts the program.

We all know a character is one byte long.
In here characters can be instructions.
The characters `c`, `e` and `h` were chose to be instructions.

1. We create `stack` and `object` data structures

2. We create `push` and `pop` functions for the stack

3. We use those to store and retrieve values from the `.vm` file

4. We iterate through characters in the file

5. We use an array of function pointers 
to retrieve the type of function to trigger 
based on the current character (byte) in the while loop

6. When the function is triggered, we pass the charcter to the stack.

7. At the end, the file should have an `h` to halt (stop the execution).

