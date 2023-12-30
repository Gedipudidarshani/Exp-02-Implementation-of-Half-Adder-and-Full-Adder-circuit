# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

Implementation-of-Half-Adder-and-Full-Adder-circuit
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
### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Gedipudi Darshani
RegisterNumber:212223230062
Half Adder:
![image](https://github.com/Gedipudidarshani/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139340574/531dee5f-8a86-49cf-967e-9b4597897976)
Full Adder:
![image](https://github.com/Gedipudidarshani/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139340574/90280cc4-4565-4c3f-8d62-8a8fb1bd07ba)


*/
# Logic symbol & Truthtable
![image](https://github.com/Gedipudidarshani/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139340574/8dca6364-8ced-4fed-8ed7-d007e6e9d2e0)

# RTL realization
![image](https://github.com/Gedipudidarshani/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139340574/103004c8-7bee-4dc5-819f-5d499a1fc3e3)


### Output:
![image](https://github.com/Gedipudidarshani/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139340574/83768995-fd01-4549-9685-99097ea04a80)


### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

