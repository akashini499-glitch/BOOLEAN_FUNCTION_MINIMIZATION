 # BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by: AKASHINI V
Register Number:25016886


**RTL realization Output:**

MINIMIZATION OF BOOLEAN FUNCTION
i)
<img width="887" height="436" alt="Screenshot 2025-11-26 183743" src="https://github.com/user-attachments/assets/266c93c9-5773-4ced-90ac-35193ba4120b" />
ii)
<img width="472" height="271" alt="Screenshot 2025-11-26 184522" src="https://github.com/user-attachments/assets/7db9a5c6-8d4d-43f6-be5c-592c420d1dc9" />

**RTL Timing Diagram**

<img width="1919" height="1024" alt="Screenshot 2025-11-26 184033" src="https://github.com/user-attachments/assets/ffdea694-d582-4e2b-b274-e89ef4e30748" />
<img width="1919" height="1018" alt="Screenshot 2025-11-26 184647" src="https://github.com/user-attachments/assets/93bd58f8-9174-40de-b3ea-5c42740855a5" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

