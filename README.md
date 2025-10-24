# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

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
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram
### Schematic of 2-Bit Multiplier:
<img width="1919" height="1079" alt="Screenshot 2025-10-24 160102" src="https://github.com/user-attachments/assets/bbdf66f6-d91f-49bc-8e7b-be04030e5d63" />


## Output
### Transient Analysis Output:
<img width="1919" height="1079" alt="Screenshot 2025-10-24 160132" src="https://github.com/user-attachments/assets/9eb6fe6c-c524-445a-b6c9-7581a839ca5f" />
<img width="1919" height="1079" alt="Screenshot 2025-10-24 160501" src="https://github.com/user-attachments/assets/cdae4263-4714-4d6f-a2fe-2a10c857aebf" />


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


<img width="1919" height="1079" alt="Screenshot 2025-10-24 160333" src="https://github.com/user-attachments/assets/343bcd13-5036-434f-ac32-74cc8bf4fbc5" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
