# _printf()

The printf is a project collaboration between Joshua Oloton and Godwin, students of ALX.

_printf() is a function that performs formatted output conversion and print data.

Prototype:

	int _printf(const char *format, ...)
**Format** is the string being printed.

_printf() is a variadic function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:

    %[flags][length]specifier
The return value is the amount of chars printed.

## File Functions
### _printf.c
Own custom printf Function That Performs Formatted Output Conversion And Print Data.

### main.h
Header File Containing All Prototypes Are Saved.

### get_func.c
Pointer To A Function That Selects The Correct Function To Perform The Operation.

### print_buf.c
Function That Prints The Buffer.

buf.c
Function That Concatenates The Buffer Characters.

print_chr.c
Function That Writes The Character C To Stdout.

/* Indentifier : %c */

print_str.c
Function That Writes The String To Stdout.

/* Indentifier : %s */

print_int.c
Function That Prints An Integer.

/* Indentifier : %i or %d */

print_bnr.c
Function That Prints Decimal In Binary.

/* Indentifier : %b */

print_oct.c
Function That Prints Decimal In Octal.

/* Indentifier : %o */

print_hex.c
Function That Prints Decimal In Hexadecimal.

/* Indentifier : %x */

print_upx.c
Function That Prints Decimal In Uppercase Hexadecimal.

/* Indentifier : %X */

print_usr.c
Function That Prints A String And Values Of Non-Printed Chars.

/* Indentifier : %S */

print_unt.c
Function That Prints An Unsigned Integer.

/* Indentifier : %u */

print_rev.c
Function That Writes The String To Stdout In Reverse.

/* Indentifier : %r */

print_rot.c
Function That Writes The String To Stdout In Rot13.

/* Indentifier : %R */

print_add.c
Function That Prints The Address Of An Input Variable.

/* Indentifier : %p */

print_long_oct.c
Function That Prints Long Decimal Number In Octal.

/* Indentifier : %lo */

print_long_hex.c
Function That Prints Long Decimal Number In Hexadecimal.

/* Indentifier : %lx */

print_long_int.c
Function That Prints A Long Integer.

/* Indentifier : %li */

print_long_upx.c
Function That Prints A Long Decimal In Uppercase Hexadecimal.

/* Indentifier : %lX */

print_long_unt.c
Function That Prints A Long Unsigned Integer.

/* Indentifier : %lu */

print_short_oct.c
Function That Prints Short Decimal Number In Octal.

/* Indentifier : %ho */

print_short_hex.c
Function That Prints Short Decimal Number In Hexadecimal.

/* Indentifier : %hx */

print_short_int.c
Function That Prints A Short Integer.

/* Indentifier : %hi */

print_short_upx.c
Function That Prints A Short Decimal In Uppercase Hexadecimal.

/* Indentifier : %hX */

print_short_unt.c
Function That Prints A Short Unsigned Integer.

/* Indentifier : %hu */

print_num_hex.c
Function That Print A Number In Hexadecimal Begining With 0 And x.

/* Indentifier : %#x */

print_num_oct.c
Function That Prints A Number In Octal Begining With 0 And o.

/* Indentifier : %#o */

print_num_upx.c
Function That Prints A Number In Uppercase Hexadecimal.

/* Indentifier : %#X */

print_plus_int.c
Function That Prints An Integer With Plus Symbol.

/* Indentifier : %+i */

print_space_int.c
Function That Prints An Integer Begining With 0 And u.

/* Indentifier : % i */

ev_print_func.c
Function That Returns The Amount Of Indetifiers.

Authors
Joshua Oloton and Godwin Effiong
