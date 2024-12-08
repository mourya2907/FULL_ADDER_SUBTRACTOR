

Implementation-of-Full-Adder-and-Full-subtractor-circuit

## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## Full Adder and Full Subtractor

## Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

## Figure -1 FULL ADDER

## Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## Truthtable
![Screenshot 2024-12-08 185337](https://github.com/user-attachments/assets/bbd49ea4-b5a9-4609-a352-720f27190a52)
![Screenshot 2024-12-08 185521](https://github.com/user-attachments/assets/3a386af8-5421-4837-a9f4-932607ba2495)



## Procedure
1. Type the program in Quartus software
2. Complile and run the program
3. Generate the RTL schematic and save the logic diagram
4. Create nodes for inputs and outputs to generate the timing diagram
5. For different inputs combination generate the timing diagram
   



## Program:

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
### Developed by: Mourya G
### RegisterNumber:24006288


## RTL Schematic
![Screenshot 2024-12-08 185541](https://github.com/user-attachments/assets/db7350a9-3448-47f4-a2db-74052a1b1927)
![Screenshot 2024-12-08 185636](https://github.com/user-attachments/assets/8aaf6417-0db8-4e42-9ad7-86c58b6b503f)



## Output Timing Waveform
![Screenshot 2024-12-08 185716](https://github.com/user-attachments/assets/ef9c9aba-efa1-4ab0-ab45-fcd1abfeeafe)
![Screenshot 2024-12-08 185740](https://github.com/user-attachments/assets/5bd84be2-8444-4c63-b8f6-cfef22e8e523)




## Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



