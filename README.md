# printf

A simple printf function built by Ojonuba Jeremiah and Lucky Abiom for Alx software Engineering School.
# Welcome

Rebuild of the standard printf function in C. Our project required a function capable of printing with the %d, %c, %s, and %% specifiers to standard output. printf returns the number of characters printed (excluding the null byte at the end of strings). We were not asked to handle flag characters, field width, precision, or length.
# Format 

Our team chose to add %x ,%X, %b, %o, %u, %r, %R, and %p formatting. We relied on the library we have been building at Alx as well as new concepts gathered during this project.
# Supported Format Types
TYPE - OUTPUT

c - Single character

s - String of character

r - String in reverse

R - String in rot13

d - Integer in decimal

i - integer

% - Percent sign

x - Lowercase hex(loervase)

X - Uppercase hex (unsigned)

b -  signed binary

o -  signed octal

u - unsigned integer

p - pointer address

# Examples

Character: printf("%c", A); Output:: A

String: printf("%s", This is a string.); Output: This is a string.

Integer: printf("%i", 5); Output: 5

# File Functions

_printf.c
Own Printf Function Tha Performs Formatted Output Conversion And Print Data.

 # main.h
Header File Were All Prototypes Are Saved.

# get_print_func.c
Pointer To A Function That Selects The Correct Function To Perform The Operation.

# print_buf.c
Function That Prints The Buffer.

# handl_buf.c
Function That Concatenates The Buffer Characters.

# print_chr.c
Function That Writes The Character C To Stdout.

/* Identifier : %c */
# print_str.c
Function That Writes The String To Stdout.

/* Identifier : %s */
# print_int.c
Function That Prints An Integer.

/* Identifier : %i or %d */
# print_bnr.c
Function That Prints Decimal In Binary.

/* Identifier : %b */
# print_oct.c
Function That Prints Decimal In Octal.

/* Identifier : %o */
# print_hex.c
Function That Prints Decimal In Hexadecimal.

/* Identifier : %x */
# print_upx.c
Function That Prints Decimal In Uppercase Hexadecimal.

/* Identifier : %X */
# print_usr.c
Function That Prints A String And Values Of Non-Printed Chars.

/* Identifier : %S */
# print_unt.c
Function That Prints An Unsigned Integer.

/* Identifier : %u */
# print_rev.c
Function That Writes The String To Stdout In Reverse.

/* Identifier : %r */
# print_rot.c
Function That Writes The String To Stdout In Rot13.

/* Identifier : %R */
# print_add.c
Function That Prints The Address Of An Input Variable.

/* Identifier : %p */
# print_long_oct.c
Function That Prints Long Decimal Number In Octal.

/* Identifier : %lo */
# print_long_hex.c
Function That Prints Long Decimal Number In Hexadecimal.

/* Identifier : %lx */
# print_long_int.c
Function That Prints A Long Integer.

/* Identifier : %li */
# print_long_upx.c
Function That Prints A Long Decimal In Uppercase Hexadecimal.

/* Identifier : %lX */
# print_long_unt.c
Function That Prints A Long Unsigned Integer.

/* Identifier : %lu */
# print_short_oct.c
Function That Prints Short Decimal Number In Octal.

/* Identifier : %ho */
# print_short_hex.c
Function That Prints Short Decimal Number In Hexadecimal.

/* Identifier : %hx */
# print_short_int.c
Function That Prints A Short Integer.

# print_short_upx.c
Function That Prints A Short Decimal In Uppercase Hexadecimal.

/* Identifier : %hX */
# print_short_unt.c
Function That Prints A Short Unsigned Integer.

/* Identifier : %hu */
# print_num_hex.c
Function That Print A Number In Hexadecimal Begining With 0 And x.

/* Identifier : %#x */
# print_num_oct.c
Function That Prints A Number In Octal Begining With 0 And o.

/* Identifier : %#o */
# print_num_upx.c
Function That Prints A Number In Uppercase Hexadecimal.

/* Identifier : %#X */
# print_plus_int.c
Function That Prints An Integer With Plus Symbol.

/* Identifier : %+i */
# print_space_int.c
Function That Prints An Integer Begining With 0 And u.

/* Identifier : % i */
# ev_print_func.c
Function That Returns The Amount Of Indetifiers.


# Authors

Ojonuba Jeremiah - github.com/spartan124
Lucky Abiom -github.com/faemous
 
 # End