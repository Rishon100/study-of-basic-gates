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

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:V RISHON ANAND
 
 RegisterNumber: 212224240135

     module exp12 (a, b, y1,y2,y3,y4,y5,y6,y7);
       input a, b;
       output y1,y2,y3,y4,y5,y6,y7;

     nand (y1, a, b);
	    not(y2,a);
      or (y3, a, b);
     and (y4, a, b);	
	    nor(y5, a, b); 
	    xor(y6, a, b);
	    xnor(y7, a, b);
	 
    endmodule
 
**Logic symbol & Truthtable**

**NAND gate**

![Screenshot 2025-03-15 215201](https://github.com/user-attachments/assets/70aeaed5-8b8e-4174-a498-181992f93e1f)


**OR gate**

![Screenshot 2025-03-15 215150](https://github.com/user-attachments/assets/ce69c881-0fb1-4517-b5aa-23d8a787c803)


**AND gate**

![Screenshot 2025-03-15 215145](https://github.com/user-attachments/assets/a5ddd2ea-55b4-431a-8aa9-704cee06c97a)


**NOR gate**

![Screenshot 2025-03-15 215206](https://github.com/user-attachments/assets/5776bc8b-ac03-4843-b574-77e773134f16)


**XNOR gate**

![Screenshot 2025-03-15 215210](https://github.com/user-attachments/assets/3c4508fa-a1b3-4f00-9df1-20c554333774)


**NOT gate**

![Screenshot 2025-03-15 215137](https://github.com/user-attachments/assets/3ec8e43a-50f6-4c67-b1d3-15f249847096)


**RTL realization Output:** 
![Screenshot 2025-03-15 214039](https://github.com/user-attachments/assets/08f4ae39-e9be-4525-a6be-2ecd00746e54)


**RTL**
![Screenshot 2025-03-15 214304](https://github.com/user-attachments/assets/8803f0a2-3b50-41b4-a3dd-681167a70851)

**Result:**
Thus the truth table of logic gates in Quartus II using verilog programming is studied and verified.

