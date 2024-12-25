# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Theory**

![THEORY](https://github.com/user-attachments/assets/0a18ccc3-89bb-4563-a121-35e9939fc905)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module EXP2MAIN(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: Viswajith Lalithram R.V

RegisterNumber: 24000985


**RTL realization**

![EXP2MAIN LOGIC GATE](https://github.com/user-attachments/assets/56b6c6b3-eeac-409f-8b91-05dfcfd4dfc4)

**Timing Diagram**


![WAVEFORM -02](https://github.com/user-attachments/assets/e94ab547-59a7-4fd3-9078-e6b1682b5cee)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

