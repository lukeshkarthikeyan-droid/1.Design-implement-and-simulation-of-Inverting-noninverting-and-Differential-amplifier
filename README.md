# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1280" height="839" alt="image" src="https://github.com/user-attachments/assets/dfc1f04f-cf36-43f9-ad9d-5f003636dedc" />

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1280" height="769" alt="image" src="https://github.com/user-attachments/assets/adad74ce-d2c7-478f-8ad0-7a957954bf48" />


  **MODEL GRAPH:**
<img width="1031" height="812" alt="image" src="https://github.com/user-attachments/assets/24efbaa5-19f3-4283-ad4e-0cd7bb37f772" />


  **TABULATION:**
 <img width="1280" height="771" alt="image" src="https://github.com/user-attachments/assets/bf739b90-5960-474e-845e-bffe23e62b10" />


**MODEL CALCULATION:**
<img width="1600" height="683" alt="WhatsApp Image 2026-09-13 at 7 53 11 PM" src="https://github.com/user-attachments/assets/74eec40e-0c3c-40e4-8b6b-104b328f1775" />
**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1040" height="671" alt="WhatsApp Image 2026-09-14 at 7 14 19 PM" src="https://github.com/user-attachments/assets/d4014acf-23a7-4b0b-825d-56b99be0b5ba" />


  **MODEL GRAPH:**
<img width="1280" height="750" alt="WhatsApp Image 2026-09-14 at 7 14 53 PM" src="https://github.com/user-attachments/assets/670fd965-a6ac-4c86-a1ab-a93fb4a3052e" />


  **TABULATION:**
<img width="1280" height="691" alt="WhatsApp Image 2026-09-14 at 7 14 35 PM" src="https://github.com/user-attachments/assets/91d44342-bbb4-40d5-b0df-df882909f1e3" />

  **DIFFERENTIAL AMPLIFIER:**
  
  **CIRCUIT DIAGRAM**
<img width="1280" height="827" alt="WhatsApp Image 2026-09-14 at 7 18 25 PM" src="https://github.com/user-attachments/assets/368b1765-f0fe-4571-be57-2f16b0955650" />


  **MODEL GRAPH:**
<img width="1040" height="780" alt="WhatsApp Image 2026-09-14 at 7 18 34 PM" src="https://github.com/user-attachments/assets/64492197-c4dc-45b3-a0ee-7f5c57162d94" />


  **TABULATION:**
<img width="1040" height="859" alt="WhatsApp Image 2026-09-14 at 7 18 46 PM" src="https://github.com/user-attachments/assets/44727fed-93ed-4b45-a40b-438dc6bed7df" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






