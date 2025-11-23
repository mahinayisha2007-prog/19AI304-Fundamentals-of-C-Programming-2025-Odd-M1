# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 18-11-2025
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```
#include <stdio.h>

int main() {
int intLiteral = 25;
float floatLiteral = 10.75;
char charLiteral = 'A';
char stringLiteral[] = "Hello";

printf("Integer Literal: %d\n", intLiteral);
printf("Float Literal: %.2f\n", floatLiteral);
printf("Character Literal: %c\n", charLiteral);
printf("String Literal: %s\n", stringLiteral);

return 0;
}
```
# Output:

<img width="381" height="173" alt="517405203-6f6faa3a-b60d-49c8-aca8-b762bffea8d2" src="https://github.com/user-attachments/assets/37fee487-3ded-434b-abb5-e1ee2e8099d1" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 18-11-2025
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```
#include <stdio.h>

#define MACRO_VALUE 100

int main() {
const int constVar = 50;

printf("Macro constant value: %d\n", MACRO_VALUE);
printf("Constant variable value: %d", constVar);

return 0;
}
```
# Output:

<img width="359" height="129" alt="516043738-835d7c42-79bd-40a4-8cb7-3ecd348d6e99" src="https://github.com/user-attachments/assets/26b091ae-4aff-4ea9-b72a-3ba68e06d005" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 18-11-2025
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```
#include <stdio.h>
int main() {
int a = 10;
float b = 12.5f;
double c = 45.987654;
char d = 'A';
printf("Integer value: %d\n", a);
printf("Float value: %.2f\n", b);
printf("Double value: %lf\n", c);
printf("Character value: %c", d);
return 0;
}
```
# Output:

<img width="368" height="185" alt="516044176-5a5f9e2e-34d6-4405-8d68-77b11e36d6f6" src="https://github.com/user-attachments/assets/4e2486a2-c54d-4e80-bd51-581a484b5bac" />

# Result: 
Thus To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen was implemented and executed successfully, and the required output was obtained.

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 18-11-2025
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
int main() {
int a, b;
printf("Enter two integers: ");
scanf("%d %d", &a, &b);
printf("\n--- Arithmetic Operations ---\n");
printf("Sum (a + b): %d\n", a + b);
printf("Difference (a - b): %d\n", a - b);
printf("Product (a * b): %d\n", a * b);
printf("Quotient (a / b): %d\n", a / b);
printf("Remainder (a %% b): %d\n", a % b);
printf("\n--- Bitwise Operations ---\n");
printf("AND (a & b): %d\n", a & b);
printf("OR (a | b): %d\n", a | b);
printf("XOR (a ^ b): %d\n", a ^ b);
printf("Left shift (a << b): %d\n", a << b);
printf("Right shift (a >> b): %d\n", a >> b);
printf("Bitwise NOT of a (~a): %d\n", ~a);
printf("Bitwise NOT of b (~b): %d\n", ~b);
return 0;
}
```

# Output:

<img width="498" height="474" alt="517413116-ebe85282-bb6f-43aa-bf7f-30d7601765a3" src="https://github.com/user-attachments/assets/88c4e147-8cea-4369-b7a2-fa815c2d119f" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
#include <ctype.h>

int main() {
char ch;

printf("Enter a character: ");
scanf("%c", &ch);

if (ch=='a' || ch=='e' || ch=='i' || ch=='o' || ch=='u' ||
    ch=='A' || ch=='E' || ch=='I' || ch=='O' || ch=='U') {

    printf("Vowel\n");

} else {

    if (isalpha(ch)) {
        printf("Consonant\n");
    } else {
        if (isdigit(ch)) {
            printf("Digit\n");
        } else {
            printf("Special symbol\n");
        }
    }
}

return 0;
}
```

# Output:

<img width="292" height="75" alt="517413848-87fda5f6-b3fa-403e-9fd1-310a51b1b2e8" src="https://github.com/user-attachments/assets/59eac498-55b5-484a-a57a-15c46cdc8f34" />
<img width="297" height="60" alt="517413953-9343b049-35a8-426c-801c-fbc2d4bdddef" src="https://github.com/user-attachments/assets/0da5f234-23ad-4c5e-a50b-44b8bd6f17a3" />
<img width="316" height="76" alt="517414169-bab29596-d5c8-48fb-a076-11ed3408cc1c" src="https://github.com/user-attachments/assets/2e699628-7650-4d79-9b9b-98a56df9d31e" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


