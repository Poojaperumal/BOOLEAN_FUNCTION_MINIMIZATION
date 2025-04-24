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


**PROGRAM:

module Ex21(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule

module Ex22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
 

Developed by:POOJA.P RegisterNumber: 212224100041


**RTL realization**

**Output:**
![Screenshot 2025-04-24 175140](https://github.com/user-attachments/assets/65a8e8ca-5c24-4062-bb2e-bd8978ce3bfd)


![Screenshot 2025-04-24 180224](https://github.com/user-attachments/assets/0810f786-eddb-4961-a7e6-4dff83998549)





**RTL**

![Screenshot 2025-04-24 175351](https://github.com/user-attachments/assets/dccdc746-8e1a-4b56-a281-029a07b8d54e)


![Screenshot 2025-04-24 180422](https://github.com/user-attachments/assets/bcdc9400-767a-4537-9f94-69cb99920839)



**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

