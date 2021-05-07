# KT2021_ArithmeticLogicUnit
This project includes arithmetic logic unit made with logisim during KT lesson in Vilnius University.

Circuits explained: <br>
Main - contains the whole logic of the project. Using IU (Input units) its possible to send information to ALU and see the output it provides. First two IU are for A and B values. The third one is for the operation it self (see operation list below). <br>
ALU - arithmetic logic unit itself. It takes 3 inputs and produces 1 output. (Possible to add 1 more input - reset) <br>
Explanations - this circuit contains functionality of popular logisim pre-made circuits. For example: adders, multipliers, shifters. Its possible to test and see how they work beneath the premade design. <br>
Input Only - an input only circuit which connects to ALU and is more understandable and intuitive design. <br>


Operation list: <br>
With the third input only its possible to send the following commands: <br>
0 - show first input <br>
1 - show second input <br>
2 - (not) first input <br>
3 - (not) second input <br>
4 - (or) two inputs <br>
5 - (and) two inputs <br>
6 - (xor) two inputs <br>
7 - (sum) two inputs <br>
8 - (multiply) two inputs <br>
10 - (logical left) two inputs <br>
11 - (logical right) two inputs <br>
12 - (rotate left) two inputs <br>
13 - (rotate right) two inputs <br>
14 - const 0 <br>
15 - const 15 <br>
