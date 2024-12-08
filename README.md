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

Developed by:bharath D

RegisterNumber:24900875

```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**

![image](https://github.com/user-attachments/assets/4c32ddb2-e980-4e54-b713-68e904b51915)

**TRUTH TABLE**

![image](https://github.com/user-attachments/assets/abd95429-a90b-4503-b4ab-65959c1600b9)
![image](https://github.com/user-attachments/assets/ad8c4655-be91-4bbd-9115-5200e7bcba93)


**Output:**
**RTL**

![image](https://github.com/user-attachments/assets/7a535de6-2309-43a8-98b8-e615b457a96d)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

