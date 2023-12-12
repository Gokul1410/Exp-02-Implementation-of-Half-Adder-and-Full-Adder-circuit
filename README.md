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

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:GOKUL.C

RegisterNumber:23014093

## Half Adder
![Screenshot 2023-12-12 212846](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/bf77f606-9c1e-4635-8253-e414c9c616e9)

## Full Adder
![Screenshot 2023-12-12 212916](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/bb37a2b6-b205-4b47-8414-3cf84f57d8aa)

Logic symbol & Truthtable

### Output:

### RTL
## Half Adder
![Screenshot 2023-12-12 212939](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/6e2bbd5d-afe5-4159-bc13-0dd8c6c066be)

## Full Adder
![Screenshot 2023-12-12 212959](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/a8641adc-33ac-4e69-8d6d-cfb5d1146d5f)


### TIMING DIAGRAM
## Half Adder
![Screenshot 2023-12-12 213049](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/5b9bda9a-9419-4e0a-a549-0ec192b0cc44)

## Full Adder
![Screenshot 2023-12-12 213131](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/1ae7e2fb-a9fa-4fb2-952a-5c75fc676d6b)



### TRUTH TABLE 
## Half Adder
![Screenshot 2023-12-12 213150](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/96fe3bb6-c1b2-4095-b74f-516d8aa06ef1)

## Full Adder
![Screenshot 2023-12-12 213209](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/2aa5a27a-3bd4-41db-bf90-291feaaf0d26)



### Result:

