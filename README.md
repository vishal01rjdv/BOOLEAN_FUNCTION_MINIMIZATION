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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

i)module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
ii) module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
Developed by:VISHAL R RegisterNumber:25004464

**RTL realization**
<img width="683" height="776" alt="Screenshot 2025-10-16 151405" src="https://github.com/user-attachments/assets/369224dd-9d8a-469f-a786-2eadb0659e93" />

**Output:**

**RTL**

**Timing Diagram**
<img width="686" height="659" alt="Screenshot 2025-10-16 151434" src="https://github.com/user-attachments/assets/03d969ca-6130-448a-95be-05727124d76c" />

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

