
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="583" height="212" alt="image" src="https://github.com/user-attachments/assets/6fa6f221-acfa-4060-8799-4b00403ad383" />


## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="586" height="124" alt="image" src="https://github.com/user-attachments/assets/35e166ab-e6e1-41ed-8c3f-fe58fb397e25" />


## TABULATION  
![WhatsApp Image 2025-11-24 at 08 03 31_97b3fcd8](https://github.com/user-attachments/assets/0b8688f3-f3a2-4fe3-8303-f62c06c28b7f)

Vin=5.5V

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain (Vo/Vi) | Gain (dB) |
| -------------- | ---------------------------- | ------------ | --------- |
| 1 kHz          | 3.48 V                       | 0.476        | -6.07     |
| 5 kHz          | 4.74 V                       | 0.948        | -0.46     |
| 10 kHz         | 9.73 V                       | 1.986        | 5.87      |
| 20 kHz         | 11.47 V                      | 2.29         | 7.21      |
| 50 kHz         | 12.90 V                      | 2.58         | 8.23      |
| 75 kHz         | 12.85 V                      | 2.58         | 8.23      |
| 100 kHz        | 10.85 V                      | 2.17         | 6.72      |
| 150 kHz        | 8.47 V                       | 2.17         | 6.72      |
| 250 kHz        | 5.48 V                       | 1.694        | 4.57      |
| 500 kHz        | 0.94 V                       | 1.094        | 0.796     |
| 1 MHz          | 0.1 V                        | 1.194        | -14.24    |

---

## MODEL GRAPH

<img width="674" height="331" alt="image" src="https://github.com/user-attachments/assets/4f1a3561-a68b-426b-91b4-58973e611fc4" />

![WhatsApp Image 2025-11-24 at 08 03 30_1dc4e97d](https://github.com/user-attachments/assets/c8ede5df-feba-4d2f-a0f1-23e99f72bfa3)

---

## RESULT

Hence, the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link is verified.
