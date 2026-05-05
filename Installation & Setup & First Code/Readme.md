Installation & Setup

1. Install VS Code (Visual Studio Code)

VS Code is a powerful code editor made by Microsoft —
lightweight, customizable, and perfect for C programming.

Download Link:
https://code.visualstudio.com/

2. Install MinGW (C Compiler)

To run C programs, we need a compiler. For Windows, we’ll
install MinGW (Minimalist GNU for Windows).

Download Link:

https://www.mingw-w64.org/downloads/

3. Path

After install, copy the bin folder path and add it to System
Environment Variables:
Search: “Environment Variables” → Open
Under System Variables, find Path → Edit
Click New → Paste the copied bin path
Click OK on all dialogs

s h e r y i a n s c o d i n g s c h o o l
Write Your First C Program – Namaste Duniya
File Setup:
Open VS Code
Create a new folder → Open it in VS Code
Inside the folder, create a new file: namaste.c
Paste this code:

Run the C Program via Terminal
Steps to Compile & Run:
In Windows : (Using MinGW + VS Code Terminal)
Open the Terminal in VS Code:
Menu → Terminal → New Terminal
OR shortcut: Ctrl + ~
Compile your code using gcc: gcc namaste.c -o namaste.exe
Run the compiled program: ./namaste.exe
For macOS (Using VS Code + Xcode CLI Tools)
Open the Terminal in VS Code:
Compile your program using: gcc namaste.c -o namaste
Run your program : ./namaste
