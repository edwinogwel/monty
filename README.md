## MONTY

### The Monty Language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files

### Compilation
- ```gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty```

### The monty program
* Usage: ```monty file``` <br>
  - where ```file``` is the path to the file containing Monty byte code

### Tasks
0. Implement the ```push``` and ```pall``` opcodes <br>
   - ```push``` pushes an element to the stack <br>
   - ```pall``` prints all the values on the stack, starting from the top of the stack
