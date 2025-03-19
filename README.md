### Name : V Rakshita
### Register No: 212224100049

# Exp 1 : Study of Logic Gates

## **Aim:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## **Equipments Required:**

Software – Quartus prime 

## **Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

### **AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

### **OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

### **NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

### **NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

### **NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

### **Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

### **Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## **Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## **Program**
```
module EXP1(a,b,yand,yor,ynot,yxor,ynor,ynand,yxnor);
input a,b;
output yand,yor,ynot,yxor,ynor,ynand,yxnor;
and(yand,a,b);
or(yor,a,b);
not(ynot,a);
xor(yxor,a,b);
nor(ynor,a,b);
nand(ynand,a,b);
xnor(yxnor,a,b);
endmodule
```
 
## **Logic symbol & Truthtable**

![WhatsApp Image 2025-03-18 at 11 51 46 AM](https://github.com/user-attachments/assets/62fd7108-69b8-4686-abed-f7d906214b66)
![WhatsApp Image 2025-03-18 at 11 57 18 AM](https://github.com/user-attachments/assets/60891ef7-0907-4278-84f0-14b4ff79e5dc)


## **Wave form**

![WhatsApp Image 2025-03-18 at 11 51 55 AM](https://github.com/user-attachments/assets/388c449d-a4ad-464a-a908-a1b26c779c40)


## **Result:**
The truth table of logic gates in Quartus II has been studied and verified using Verilog programming.
