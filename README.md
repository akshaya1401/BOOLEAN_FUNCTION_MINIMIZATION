
## Name: Santhanalakshmi S
## Reg No: 212225040376

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

Developed by: RegisterNumber:212225040376
~~~
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module exe02(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
~~~

**Output:**
<img width="377" height="348" alt="Screenshot 2026-05-26 084110" src="https://github.com/user-attachments/assets/98e06b72-de2c-4250-b6fb-3ddad016a9e2" />

**Timing Diagram**
<img width="1446" height="850" alt="Screenshot 2026-05-26 084125" src="https://github.com/user-attachments/assets/3d69ec68-ed49-419b-9ddf-841c001120c3" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

