### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
```
module exp_1(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and g1(y1,a,b);
or g2(y2,a,b);
not g3(y3,a);
nand g4(y4,a,b);
nor g5(y5,a,b);
xor g6(y6,a,b);
xnor g7(y7,a,b);
endmodule
```
Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: RegisterNumber: 
 
**Logic symbol & Truthtable**
![IMG-20241209-WA0024](https://github.com/user-attachments/assets/0bd2720a-ad68-4cca-a949-967465f48772)
![IMG-20241209-WA0022](https://github.com/user-attachments/assets/b470b89d-4937-423f-b100-0aef5f3d8eb7)
![IMG-20241209-WA0023](https://github.com/user-attachments/assets/f2d54b06-6b18-4f20-b8af-f045f3e13ae0)
![IMG-20241209-WA0024](https://github.com/user-attachments/assets/64ddefd0-a2fd-453e-bf58-3180ff100658)
![IMG-20241209-WA0022](https://github.com/user-attachments/assets/adadd3aa-12ff-40ff-ab07-fc9dc61a3004)
![IMG-20241209-WA0025](https://github.com/user-attachments/assets/33b7aec7-9fbd-495c-8676-3c2f8889b52e)
![IMG-20241209-WA0026](https://github.com/user-attachments/assets/b1414fab-f685-41e2-bd76-6cdda373951b)


**RTL realization Output:** 
![IMG-20241209-WA0028](https://github.com/user-attachments/assets/f89f1caf-3b72-470e-a83d-38a774f40ecd)

**RTL**
![IMG-20241209-WA0028](https://github.com/user-attachments/assets/fdc51e5b-49aa-424e-a1e5-58b338b99b15)

**Result:**
Thus the Basic digital ICs and the verification of truth tables for different logic
gates were studied and successfully realized using Verilog.

