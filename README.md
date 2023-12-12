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
![Screenshot 2023-12-12 212846](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/ae9bf5d0-bfa5-4d7f-b0c6-7e5cd932fa97)

## Full Adder
![Screenshot 2023-12-12 212916](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/e83c6d5b-93ba-4d29-affd-63d914a4783d)


Logic symbol & Truthtable
RTL realization

### Output:
### RTL
## Half Adder
![Screenshot 2023-12-12 212939](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/0b827ad4-eedc-424c-ba6a-1583158b2206)

## Full Adder
![Screenshot 2023-12-12 212959](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/8b363af5-fefb-4a9e-86bb-c081426f89cc)

### TIMING DIAGRAM
## Half Adder
![Screenshot 2023-12-12 213049](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/c9184a04-fd5b-4683-8f62-a7989f240d86)

## Full Adder
![Screenshot 2023-12-12 213131](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/289c0b61-1304-499c-bd4d-c4bbe1f38885)


### TRUTH TABLE 
## Half Adder
![Screenshot 2023-12-12 213150](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/c61a5916-9f74-4b15-92c6-29aaa2d52dc1)

## Full Adder
![Screenshot 2023-12-12 213209](https://github.com/Gokul1410/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153058321/c37372f7-58a3-4974-a699-c1c8e4c8709f)


### Result:
Thus the Implementation of Half Adder and Full Adder circuit are studied and the truth table for different logic gates are verified.

