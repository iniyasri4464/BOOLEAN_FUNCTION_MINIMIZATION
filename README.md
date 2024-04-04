# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**
![image](https://github.com/iniyasri4464/BOOLEAN_FUNCTION_MINIMIZATION/assets/152419072/07e15d59-9322-4033-acf2-f34702e28ede)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:Iniyasri.s
RegisterNumber:212223230081

// Verilog model:Circuit with boolean expressions
module ex02 (E,F,A,B,C,D);
input A, B, C, D;
output E,F;
assign E = A || (B && C) || ((!B) && D);
assign F=((!B) && C) || ( B && (!C) && (!D));
endmodule

```
*/


**RTL realization**
![image](https://github.com/iniyasri4464/BOOLEAN_FUNCTION_MINIMIZATION/assets/152419072/f38c47d7-186a-4f40-b0c5-85b3276215ad)



**Timing Diagram**
![image](https://github.com/iniyasri4464/BOOLEAN_FUNCTION_MINIMIZATION/assets/152419072/83552d90-7f08-41f6-8a3f-6aee29c6ea71)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

