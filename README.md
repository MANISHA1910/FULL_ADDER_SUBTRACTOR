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
![Screenshot (172)](https://github.com/user-attachments/assets/38e273ae-3200-4215-a39e-0c9c57f0cb93)


**Procedure**

Write the detailed procedure here
1.write a code in quartus software by creating a new project wizard .
2.run the program to get output
3.then open the RTL viewer and download the image
4.pen the new file with university program VWF
5.set end timer and execute then downloading the waveform

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming
![Screenshot (173)](https://github.com/user-attachments/assets/d246f9ec-9f14-441b-aa6f-a1609c4f5a59)
. Developed by: MANISHA.M RegisterNumber:24900673
*/

**RTL Schematic**
![Screenshot (174)](https://github.com/user-attachments/assets/9aaeaff8-5790-4368-a824-f52f6347ec7e)


**Output Timing Waveform**
![Screenshot (175)](https://github.com/user-attachments/assets/e11ddd76-f396-4a48-8b8e-3b6b588ec67c)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



