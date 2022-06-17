## MONTY

### The Monty Language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. **The goal of this project is to create an interpreter for Monty ByteCodes files**

### Compilation
- ```gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty```

### The monty program
* Usage: ```monty file``` <br>
  - where ```file``` is the path to the file containing Monty byte code

### Tasks
0. Implement the ```push``` and ```pall``` opcodes <br>
   - ```push``` pushes an element to the stack <br>
   - ```pall``` prints all the values on the stack, starting from the top of the stack
1. Implement the ```pint``` opcode <br>
   - ```pint``` prints the value at the top of the stack
2. Implement the ```pop``` opcode <br>
   - ```pop``` removes the top element of the stack
3. Implement the ```swap``` opcode <br>
   - ```swap``` swaps the top two elements of the stack
4. Implement the add opcode
5. Implement the nop opcode
6. Implement the sub opcode
7. Implement the div opcode
8. Implement the mul opcode
9. Implement the mod opcode
10. Comments
11. Implement the pchar opcode
12. Implement the pstr opcode
13. Implement the rotl opcode
14. Implement the rotr opcode
15. Implement the stack and queue opcodes
16. Write a Brainf*ck script that prints School
17. Write a Brainf*ck script that adds two digits given by the user
18. Write a Brainf*ck script multiplies two digits given by the user
19. Write a Brainf*ck script multiplies two digits given by the user
    - And print the result, followed by a new line
