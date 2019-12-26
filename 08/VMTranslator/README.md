Usage:

terminal:
for each vm file in subdir of Chapter 08:
python path\to\VMtranslator.py path\to\file.vm

VMEmulator (from the project tools) path\to\fileVME.tst to generate the actual .out file
CPUEmulator (from the project tools) path\to\file.tst to test your written .asm file (that generates .out) against .cmp

Note:
There is somewhere an error in the VMtranslator python code, cannot validate the .cmp with the .asm generated file