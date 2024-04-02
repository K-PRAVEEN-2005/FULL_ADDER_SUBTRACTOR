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
![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/9f1f1c26-48df-4bb8-b005-b312a5ca2476)

![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/027a0699-bc0c-46a6-b267-d2697ec21534)

**Procedure**
STEP 1: Use module project name(input,output) to start the Verilog programmming. 

STEP 2: Assign inputs and outputs using the word input and output respectively. 

STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression. 

STEP 4: Use each output to represnt onre for differnce and the other for borrow. STEP 5: End the verilog program using keyword endmodule.


**Program:**
DEVELOPED BY: Praveen K

REGISTER NO: 212223230153
![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/629cd264-3e2f-465e-8d60-91a8d3016316)

![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/d84979b4-66cd-4689-83c0-d7233901fc2a)
**RTL Schematic**
![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/d7aaf04a-02c9-4301-93bd-0ab8eb736590)


**Output Timing Waveform**
![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/b408222d-563f-4ccc-923e-d1b762a7c133)
![image](https://github.com/K-PRAVEEN-2005/FULL_ADDER_SUBTRACTOR/assets/145742724/e584f7aa-c8e0-4b79-ba97-c4ff5dd9fce8)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



