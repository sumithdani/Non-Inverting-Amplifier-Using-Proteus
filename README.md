## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="996" height="664" alt="image" src="https://github.com/user-attachments/assets/cb0e5f38-4846-4c45-b495-e7b309e44641" />

Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1039" height="660" alt="image" src="https://github.com/user-attachments/assets/2703ed11-be6f-4ed7-8f64-838dc4735ac5" />

## Tabulation
<img width="1090" height="261" alt="image" src="https://github.com/user-attachments/assets/61f3085b-86aa-49e9-8a35-b69d92d54e43" />

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
  **A non-inverting amplifier is an op-amp circuit where the input signal is applied to the positive (+) terminal of the operational amplifier. The output is taken from the op-amp output terminal, and a feedback network (usually resistors) is connected between output and the negative (–) terminal.
It amplifies the input signal without changing its polarity (no phase inversion).**
2.	What is the gain formula?
 <img width="601" height="252" alt="image" src="https://github.com/user-attachments/assets/d84e5be5-2abd-423a-a48a-b16a929f1b3d" />

3.	Why is output in phase?
  **The input is applied to the non-inverting (+) terminal, so the op-amp amplifies the signal directly.
Because of negative feedback, the op-amp adjusts its output to keep both inputs nearly equal. Since the input is on the positive terminal, the output follows the same polarity.
Hence, output has 0° phase shift (in phase with input).**
4.	What happens if Rf increases?
<img width="634" height="315" alt="image" src="https://github.com/user-attachments/assets/34fbe5de-60eb-42df-9415-4f71a91d27d6" />

5.	What is the input impedance of non-inverting amplifier?
  **The input impedance is very high (ideally infinite), because the input is applied directly to the op-amp’s non-inverting terminal.
In practical op-amps, it is typically in the range of megaohms to gigaohms.
High input impedance ensures very little current is drawn from the source, making it suitable for weak signals.**
