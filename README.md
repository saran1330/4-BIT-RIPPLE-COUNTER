# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**
1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.
<img width="761" height="330" alt="523431929-8abcf52c-7c28-4962-903b-434f656af970" src="https://github.com/user-attachments/assets/dc39d59b-01d3-4f5d-9d25-86f9d3bede63" />

 Developed by:SARAN RAJ M 
 
 RegisterNumber:212225240138


**RTL LOGIC FOR 4 Bit Ripple Counter**
<img width="977" height="468" alt="523431981-fe875245-9246-4ee4-8a2b-a7eed6879db1" src="https://github.com/user-attachments/assets/b7de9e01-11b5-47f6-bc05-4b673ab0c436" />

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
<img width="1597" height="222" alt="523432005-a039f7c3-f9fe-4f0a-b97b-1e143f054c5b" src="https://github.com/user-attachments/assets/33d838cc-c087-42b5-879e-5e07130f2cee" />

**RESULTS**
Thus 4 Bit Ripple Counter has been implemented using verilog and validated their functionality using their functional tables
