# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
**half adder:**
![image](https://github.com/user-attachments/assets/43983dae-03bd-490e-9103-183f156dd15b)

**half subtractor:**
![image](https://github.com/user-attachments/assets/0e80b7d3-6228-451b-81b0-28088dbaab18)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:SHASWANTH MATHAV.S RegisterNumber:24900884*/
**Program:**
![Screenshot 2024-12-17 142817](https://github.com/user-attachments/assets/b0afd1d0-22d1-4b36-827b-c670b065466c)

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: shaswanth mathav s /  RegisterNumber: 24900884

**RTL Schematic**
![Screenshot 2024-12-17 142847](https://github.com/user-attachments/assets/aeccaddf-33dc-451e-8a79-6d40c9dc35cb)
![Screenshot 2024-12-17 142902](https://github.com/user-attachments/assets/26c1d97c-07c8-4bdb-adab-3f482a1f99b7)


**Output/TIMING Waveform**
![Screenshot 2024-12-17 142916](https://github.com/user-attachments/assets/08678c4c-afbf-4c77-a37b-55deb7a77dfd)
![Screenshot 2024-12-17 142928](https://github.com/user-attachments/assets/f73dd3e7-7baa-4db4-baa7-9fa8f744c903)


**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


