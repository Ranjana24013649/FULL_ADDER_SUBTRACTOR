**NAME RANJANA R**

**REGISTER NO: 212224040270**

# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
Full Adder
![Screenshot (49)](https://github.com/user-attachments/assets/823e0395-f6ec-475c-a2bf-6be49b3f7fb0)
Full Subtractor
![Screenshot (72)](https://github.com/user-attachments/assets/8b913326-e835-42f1-ace7-413e3d13f47d)



**Procedure**

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

**Program:**

![Screenshot (66)](https://github.com/user-attachments/assets/d32b9451-4f26-4150-a78e-ff61107903fd)



![Screenshot (69)](https://github.com/user-attachments/assets/dcd73264-9ceb-4159-9553-f0bcd7aaf737)

**RTL Schematic**


![Screenshot (68)](https://github.com/user-attachments/assets/2968f80a-8ae2-48ba-b194-10e04dbc7bad)



![Screenshot (70)](https://github.com/user-attachments/assets/69f8e4e9-e336-4f88-a837-635b2fa178de)


**Output Timing Waveform**
Full adder
![Screenshot (67)](https://github.com/user-attachments/assets/23263333-d9c7-41b4-b343-028695b426a6)


Full subtractor
![Screenshot (71)](https://github.com/user-attachments/assets/f27456b4-e059-4d4a-ad39-2bba1fd3160a)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



