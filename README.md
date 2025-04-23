# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**


![image](https://github.com/user-attachments/assets/e6bbf05e-0e9b-4c74-8a59-8ff18488de3e)

![image](https://github.com/user-attachments/assets/a4cc5425-533b-4441-a63c-afdea949e625)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module EXP_3_1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
module EXP_3_2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: MAHALAKSHMI B
RegisterNumber: 212224040182*/


**RTL realization**

1-A

![image](https://github.com/user-attachments/assets/40c09514-d69b-490b-90bf-cc9e33a79e2e)
1-B

![image](https://github.com/user-attachments/assets/c0c0d34c-0a40-4c34-bf29-a97e9e42d6be)


**Timing Diagram**

2-A

![image](https://github.com/user-attachments/assets/c26e049f-a421-45e4-b979-63813cdad49c)
2-B

![image](https://github.com/user-attachments/assets/393e0777-0cd4-48d8-84b8-dcdb4b24b083)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

