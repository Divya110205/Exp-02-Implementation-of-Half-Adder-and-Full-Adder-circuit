# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: A.DIVYA
RegisterNumber:  212222230034
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
HALFADDER
![Screenshot (38)](https://user-images.githubusercontent.com/119404855/231665587-1ea70b6a-a73b-478e-843f-bc0de9ef710c.png)

FULLADDER
![Screenshot (39)](https://user-images.githubusercontent.com/119404855/231665660-e8e13765-d0d9-40e8-9e71-b4920c79dff4.png)

### TIMING DIAGRAM
HALFADDER

FULLADDER
![out](https://user-images.githubusercontent.com/119404855/231665888-35b5fe2f-79a0-4f1e-947d-5c787165e607.png)


### TRUTH TABLE 
![WhatsApp Image 2023-04-13 at 11 01 10 AM](https://user-images.githubusercontent.com/119404855/231666431-a20b4f80-51ae-492c-971a-e9e22c435f5b.jpeg)


### Result:
The experiment for halfadder and fulladder is completed successfully.
