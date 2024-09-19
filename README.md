# assembly-language-to-print-character
Program 1: Printing a Single Character

Clear and concise: The code effectively prints a single character to the screen using the INT 21H interrupt with function 02H.
Well-structured: The code follows a standard structure with a data segment, stack segment, code segment, and a MAIN procedure.
Comments: Adding comments would enhance readability, especially for explaining the purpose of each instruction and the role of the INT 21H interrupt.
Program 2: Converting Uppercase to Lowercase

Correct logic: The code accurately converts an uppercase letter to its corresponding lowercase letter by adding 32 to the ASCII value.
Efficient: The code avoids unnecessary instructions and directly modifies the register containing the character.
Comments: Adding comments would help clarify the purpose of adding 32 and the role of the INT 21H interrupt.
Program 3: Printing Multiple Characters

Effective use of string operations: The code leverages the LEA instruction to load the address of the string into DX and the INT 21H interrupt with function 09H to print the entire string.
Clear structure: The code maintains a well-organized structure with data, stack, code segments, and a MAIN procedure.
Comments: Adding comments would explain the purpose of the LEA instruction, the INT 21H interrupt with function 09H, and the role of the $ character in the string.
Program 4: Converting Lowercase to Uppercase

Accurate conversion: The code correctly converts a lowercase letter to its corresponding uppercase letter by subtracting 32 from the ASCII value.
Efficient implementation: The code directly modifies the register containing the character, avoiding unnecessary instructions.
Comments: Adding comments would clarify the purpose of subtracting 32 and the role of the INT 21H interrupt.
GitHub Comments:

When posting these programs on GitHub, consider adding the following comments:

Purpose of the program: Briefly describe what the program does (e.g., prints a character, converts case).
Explanation of key instructions: Highlight the purpose of important instructions, such as INT 21H, LEA, and the arithmetic operations used for case conversion.
Addressing potential questions: Consider addressing any questions that might arise, such as why a specific interrupt or instruction is used.
Example usage: Provide an example of how the program can be used or modified
