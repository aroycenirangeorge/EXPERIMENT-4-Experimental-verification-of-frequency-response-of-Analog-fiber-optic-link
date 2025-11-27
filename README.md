
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

<img width="613" height="371" alt="image" src="https://github.com/user-attachments/assets/27a8648b-2eaa-47a1-ad8f-238145527368" />

---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Analog Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|    50HZ        |         138V                 |   0.644      |   1.938    |
|    3.33HZ      |         1500                 |   0.700      |   1.549    |
|    9.86HZ      |         1480                 |   0.691      |   1.603    |
|    10.2KHZ     |         1480                 |   0.691      |   1.605    |
|    13KHZ       |         1460                 |   0.68       |   1.674    |
|    16KHZ       |         1440                 |   0.672      |   1.726    |
|    33MHZ       |         1400                 |   0.684      |   1.844    |
|    3MHZ        |         136V                 |   0.028      |   1.526    |

---

## MODEL GRAPH

<img width="900" height="430" alt="image" src="https://github.com/user-attachments/assets/b33d5569-acb5-44a1-9cfa-c1519d45aeb9" />

## OUTPUT GRAPH

![WhatsApp Image 2025-11-23 at 14 11 48](https://github.com/user-attachments/assets/695a5e2e-b809-486c-b43b-7d5d1e0a0b2e)

---

## RESULT

Thus,the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link are verified.
