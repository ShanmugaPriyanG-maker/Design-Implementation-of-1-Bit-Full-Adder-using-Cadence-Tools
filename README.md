# Ex No: 05 - Design & Implementation of 1-Bit Full Adder Using Cadence Virtuoso

## Aim
The aim is to design and implement a 1-bit Full Adder using Cadence Virtuoso and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the 1-bit Full Adder design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **Full Adder circuit** using **CMOS**.
- Connect the inputs (**A, B, Cin**) and outputs (**Sum, Cout**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the output logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

<img width="712" height="433" alt="image" src="https://github.com/user-attachments/assets/ac1969f6-b2b5-4394-9dba-d457dfa5ebe9" />


## Truth Table for 1-Bit Full Adder
![image](https://github.com/user-attachments/assets/328fae3c-b83a-4cd6-b394-54323dc59673)


## Schematic Diagram
### 1. Schematic of 1-Bit Full Adder:
<img width="2507" height="1300" alt="Screenshot 2025-10-18 135101" src="https://github.com/user-attachments/assets/855c118b-6007-4c2d-8561-76f704a37a36" />

![image](https://github.com/user-attachments/assets/1a962018-9d6b-4246-ab5f-424602551e87)



## Output
### Transient Analysis Output:
<img width="713" height="839" alt="Screenshot 2025-10-18 133440" src="https://github.com/user-attachments/assets/9f2bbb04-6260-47fe-9675-7d5bfbec4ea1" />
<img width="1202" height="876" alt="Screenshot 2025-10-18 133417" src="https://github.com/user-attachments/assets/63c4405f-eded-4b90-a6b0-6715fc8d7e54" />
<img width="2880" height="1800" alt="Screenshot 2025-10-18 133402" src="https://github.com/user-attachments/assets/f2a939a5-62e3-4e7f-9fdd-7fe4e6fcf401" />

## Results
1. Successfully designed the **1-bit Full Adder** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Full Adder**.
3. Observed **correct logic switching behavior** in response to input signals.
