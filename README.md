# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME: SHARUKESH R
## REGISTER NUMBER: 212223220106
## DEPARTMENT: B.TECH (IT)
## YEAR: III

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:
## Counter :

<img width="1467" height="748" alt="Screenshot 2026-02-17 104629" src="https://github.com/user-attachments/assets/12be3c61-6fde-4935-b3cd-f6cd3a7f8d5b" />

<img width="1511" height="277" alt="Screenshot 2026-02-17 104338" src="https://github.com/user-attachments/assets/bae65eeb-9b64-411f-8c57-f386e35a0356" />

## Up Counter (CTU): 

<img width="1124" height="366" alt="Screenshot 2026-02-17 105059" src="https://github.com/user-attachments/assets/1fe07891-0faa-4252-b6e4-7c0db4083eaf" />

<img width="1095" height="305" alt="Screenshot 2026-02-17 105345" src="https://github.com/user-attachments/assets/9b0b228f-2f04-4617-b32d-816b5e2e4473" />

## Down Counter (CTD): 
<img width="1526" height="756" alt="Screenshot 2026-02-17 104226" src="https://github.com/user-attachments/assets/d688cbdb-3f61-4232-ba43-43bc3078c4c7" />

<img width="1505" height="448" alt="Screenshot 2026-02-17 104253" src="https://github.com/user-attachments/assets/06a1c237-8f49-41d6-837f-cc85d105cfb4" />

<img width="1239" height="625" alt="Screenshot 2026-02-17 104101" src="https://github.com/user-attachments/assets/239693ca-c691-451b-b5c2-a6537e0bbff2" />


## Up/Down Counter (CTUD): 
<img width="1533" height="662" alt="Screenshot 2026-02-17 105339" src="https://github.com/user-attachments/assets/c848a50c-40ca-43cc-a261-ce01caf4076a" />

<img width="1503" height="593" alt="Screenshot 2026-02-17 105542" src="https://github.com/user-attachments/assets/2c6ee127-5251-4503-a8f2-85dbe3d2490d" />

<img width="1552" height="771" alt="Screenshot 2026-02-17 105312" src="https://github.com/user-attachments/assets/313296df-8404-4e35-b894-f76f22c320c7" />

### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
