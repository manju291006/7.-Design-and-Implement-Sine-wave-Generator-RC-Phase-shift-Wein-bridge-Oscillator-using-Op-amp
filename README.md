# 7.-Design-and-Implement-Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillator-using-Op-amp
**Aim:**
To design and implement Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillato-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,3.3K,1.5K,33K,15K,1MΩ	2
7.	Capacitor	0.1 µF	3
8.	Connecting wires and probes	As required	


**THEORY:**

**RC PHASE SHIFT OSCILLATOR**

RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .

**WIEN BRIDGE**

A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
 

**DESIGN:**

**RC PHASE SHIFT OSCILLATOR**

fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1  > 10 R
R1 =10 R = 33 k.
Rf = 29R1=1MΩ


**WIEN BRIDGE OSCILLATOR**

Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ


**PROCEDURE:**

1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.


  **CIRCUIT DIAGRAM**
  <img width="437" height="237" alt="image" src="https://github.com/user-attachments/assets/3a5f2b33-7dad-44c0-8931-1fb7f5e47643" />

  <img width="408" height="252" alt="image" src="https://github.com/user-attachments/assets/0c148d94-f508-44a3-aacc-3e30f75394f2" />




  **MODEL GRAPH:**
  <img width="371" height="193" alt="image" src="https://github.com/user-attachments/assets/75d405f9-b1ab-4617-b914-501612a981b7" />

  <img width="392" height="180" alt="image" src="https://github.com/user-attachments/assets/97be5742-d692-42d3-9e27-8977e49cd3bc" />




  **TABULATION:**
<img width="1280" height="667" alt="WhatsApp Image 2026-09-16 at 9 08 41 PM" src="https://github.com/user-attachments/assets/8ac82bc9-1364-4314-9678-8e4b5b1f9980" />
  
<img width="1280" height="720" alt="WhatsApp Image 2026-09-16 at 9 08 54 PM" src="https://github.com/user-attachments/assets/5c87cf11-d694-474d-8ee6-ca64de399485" />

 **Graph**
 <img width="1080" height="1216" alt="WhatsApp Image 2026-09-16 at 9 09 38 PM" src="https://github.com/user-attachments/assets/8251d0ec-8fa1-49f0-ba9c-f43ae1b30e62" />


 




**RESULT:**
Thus a RC Phase Shift and Wien Bridge oscillators designed and tested using op-amp IC 741.
 

