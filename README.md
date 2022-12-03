# MASM-8086-using-C

Here in this project I have created a C program which read machine code instruction that are perform in MASM 8086. Same machine code can peroform here and it will give the same output what machine code of MASM 8086 give.

The machine code instructions are below,

000 AL  AX <br/>
001 CL  CX <br/>
010 DL  DX <br/>
011 BL  BX <br/>
100 AH  SP <br/>
101 CH  BP <br/>
110 DH  SI <br/>
111 BH  DI <br/>

Instruction&emsp;&emsp;Machine code <br/>
Int number&emsp;&emsp;11001101  number <br/>
Mov reg, number&emsp;&emsp;1011wreg  number&emsp;&emsp;w:0 for byte      1 for word <br/>
Mov DH,23 is (10110110)(23) &emsp;&emsp; Mov CX,1000 is (10111001)(232)(3)  Since:1000=3*256+232
