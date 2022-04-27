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
Developed by: kathirvel.A
RegisterNumber:212221230047
```module basicgates(a,b,y1,y2,y3,y4,y5);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a);
nand(y4,a,b);
nor(y5,a,b);
endmodule
```
*/
Logic symbol & Truthtable
RTL realization

### Output:
HALF ADDER:
Logic Symbol & Truth Table:

![image](https://user-images.githubusercontent.com/94911373/165544155-7db64993-2da0-4acb-b841-5412811346af.png)

![image](https://user-images.githubusercontent.com/94911373/165544224-088c3152-a17b-4472-b83a-38a187790e49.png)

RTL realization:

![image](https://user-images.githubusercontent.com/94911373/165544334-657cbf7d-7d43-463f-87ef-1f0799900b42.png)

Timing Diagram:

![image](https://user-images.githubusercontent.com/94911373/165544605-349bb576-7839-442d-ac91-c2fd73825cbe.png)



FULL ADDER:
Logic Symbol & Truth Table:

![image](https://user-images.githubusercontent.com/94911373/165544720-2bc24b3c-53e3-465c-ba70-7e4d2b60c14d.png)

![image](https://user-images.githubusercontent.com/94911373/165544761-deea7d2d-2cec-4ea5-be3d-8902f9d81c6c.png)


RTL realization:

![image](https://user-images.githubusercontent.com/94911373/165544916-8ba2e088-5322-49e1-8316-e5a701983d56.png)


Timing Diagram:

![image](https://user-images.githubusercontent.com/94911373/165545068-8817930f-c3d2-41b1-b41f-8f9864b9c34d.png)



Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming



