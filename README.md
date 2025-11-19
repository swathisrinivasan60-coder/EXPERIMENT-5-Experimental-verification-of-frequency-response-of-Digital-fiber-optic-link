
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

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
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM
![WhatsApp Image 2025-11-19 at 18 47 13_0496fbbc](https://github.com/user-attachments/assets/a2b30237-5f58-4e2a-a43e-9b2dfbf3b9ba)



---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**



---

## TABULATION  
**Transmission through Digital Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|                |                              |              |            |
![WhatsApp Image 2025-11-19 at 18 50 45_57829028](https://github.com/user-attachments/assets/5e8fb290-10d3-45c1-9d49-d7837eb6ccd3)

---

## MODEL GRAPH

![WhatsApp Image 2025-11-19 at 18 48 04_9f91260e](https://github.com/user-attachments/assets/6911366e-f42b-4965-b1d4-243fd5b95878)

![WhatsApp Image 2025-11-19 at 18 50 45_08e0c8a0](https://github.com/user-attachments/assets/88fc2744-0070-4480-b451-fc97fdc4885c)

---

## RESULT


Thus the experimental verification of frequency response of digital fiber optic link was studied and verified successfully.
