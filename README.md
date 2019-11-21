# Introduction
Building a modern computer from first principles called Hack from scratch (Hardware hierarchy: Chips and Logic Gates, Hardware Platform, Machine Language; Software hierarchy: Assembly Language, Virtual Machine, High-Level Language & Operating System)
Hack is a 16-bit computer equipped with a screen and a keyboard. 
Reference for the build is the Book "The lements of computing systems" by Noam Nisan and Shimon Schocken.
The link to the book and its resources can be accessed here: https://www.nand2tetris.org/
The website contains references to their free Software and additional coursera course.
Material in shape of powerpoint/pdf can be found here: https://www.nand2tetris.org/course

# Getting Started
1. Setup:
    - download the nand2tetris software (windows or OS)
    - download the latest java drivers: https://java.com/en/download/win10.jsp
    - add the tools folder of the nand2tetris software to the Path variable. 
        In windows:  
        $env:Path += "D:\path\to\nand2tetris\tools"

2. The Software tools:
    - the software tools include: hardware simulator, CPU emulator, VM emulator, Assembler, Compiler, Operating system, Text Comparer
    - The link with guides to the tools can be found here: https://www.nand2tetris.org/software

3. Prepare programming setup:
    - create a new dir
    - copy nand2tetris\projects\01-13 to your dir
    - open your dir in your favorite editor (e.g. VS code)
    - Download if possible extension for nand2tetris (hack linting)

4. Execute a script:
    - on windows: open cmd or powershell:
        HardwareSimulator.bat .\path\to\file.tst