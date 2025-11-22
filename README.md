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

```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

### Developed by:MAHALAKSHMI P

### RegisterNumber:25017517


**RTL realization**
<img width="1818" height="446" alt="Screenshot 2025-11-22 090908" src="https://github.com/user-attachments/assets/52c8c258-60ba-4b3c-ace5-40e33518238e" />

**RTL**
<img width="856" height="437" alt="Screenshot 2025-11-22 090826" src="https://github.com/user-attachments/assets/b803aa47-ed5c-490c-be83-d3d13bab3a9d" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

