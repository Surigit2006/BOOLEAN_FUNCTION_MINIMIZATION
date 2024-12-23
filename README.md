# BOOLEAN_FUNCTION_MINIMIZATION
**DATE:**  23/09/24




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

Developed by:M.K.Suriya prakash  RegisterNumber:24901016
```
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```
**RTL realization**




![Screenshot 2024-12-20 141952](https://github.com/user-attachments/assets/11430fa3-a55e-4de4-a507-02f7005b742b)


![Screenshot 2024-12-20 142024](https://github.com/user-attachments/assets/c21dd2a8-1512-41b0-b57f-b23099dd4eb0)










**Waveform**





![image](https://github.com/user-attachments/assets/1ec2c831-8e6c-4048-91e6-462644610a3d)

![image](https://github.com/user-attachments/assets/e7c96db3-c094-4d33-9981-98230359f2a5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

