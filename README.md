# KT2021_ArithmeticLogicUnit
This project includes arithmetic logic unit made with logisim during KT lesson in Vilnius University.

Circuits explained:
Main - contains the whole logic of the project. Using IU (Input units) its possible to send information to ALU and see the output it provides. First two IU are for A and B values. The third one is for the operation it self (see operation list below).
ALU - arithmetic logic unit itself. It takes 3 inputs and produces 1 output. (Possible to add 1 more input - reset)
Explanations - this circuit contains functionality of popular logisim pre-made circuits. For example: adders, multipliers, shifters. Its possible to test and see how they work beneath the premade design.
Input Only - an input only circuit which connects to ALU and is more understandable and intuitive design.


Operation list:
With the third input only its possible to send the following commands:
0 - show first input
1 - show second input
2 - (not) first input
3 - (not) second input
4 - (or) two inputs
5 - (and) two inputs
6 - (xor) two inputs
7 - (sum) two inputs
8 - (multiply) two inputs
10 - (logical left) two inputs
11 - (logical right) two inputs
12 - (rotate left) two inputs
13 - (rotate right) two inputs
14 - const 0
15 - const 15
