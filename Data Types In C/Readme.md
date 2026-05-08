**Data Types**
C is a Statically typed Language
--> You Must declare the type of every variable.
--> Once Declared, the type cannot be changed.
--> This is because each type uses different memory and Supports Operations.

**Types Of data**

1. Primitive Data Types
   --> The most basic data types that are used for representing simple values.
   --> int, char, float, double, Void

2. Derived data types
   --> Derived from the primitive or built-in datatypes.
   --> array, pointers, function

3. User Defined Data Types
   --> Defined by the user himself.
   --> Structure, union, enum

**Format Specifier**
Define the type of Data being printed or read
**Format Specifer // Description**
%c --> For character type.
%d, %i --> For signed integer type.
%f --> For float type.
%ld or %li --> Long
%lf --> Double
%lu --> Unsigned int or unsigned long
%lli or %lld --> Long long
%llu --> Unsigned long long
%o --> Octal representation
%p --> Pointer
%s --> String
%u --> Unsigned int

**Escape Sequence**
\t - Tab
\n - NewLine
\b - Backspace
\" - Double Quotes
\' - Single Quotes
\\ - Backslash
\? - Question mark
%% - Percentage

**Literal Constant**
Literals are the constant values that are assigned to the Variables.
--> Integer Literal - Prefixes, Suffixes
--> Float Literal
--> Character Literal
--> String Literal

1. Integer Literals
   Integer Literal are used to represent and store integer values.

Prefixes: They are classified based on their prefix (starting characters) which define the number system (base).

Types of Integer Literals:

1. Decimal (Base 10)
   --> Digit: 0-9
   --> No Prefix
   --> Example: 56, 78

2. Octal (Base 8)
   --> Prefix: 0
   --> Digits: 0-7
   --> Example: 045, 076

3. Hexadecimal (Base 16)
   --> Prefix: 0x or OX
   --> Digit: 0-9 and a-f or A-F
   --> Example: 0x23A, OXb4C

4. Binary (Base 2)
   --> prefix: 0b or OB
   --> Digit: 0 and 1
   --> Example: 0b101, 0B111

Suffixes: Integer literals can be written with suffixes to show their type.

12345678901234LL // long long int
500U // unsigned int
75L // long int
30UL // unsigned long int
100LL // long long int
200ULL unsigned long long int
