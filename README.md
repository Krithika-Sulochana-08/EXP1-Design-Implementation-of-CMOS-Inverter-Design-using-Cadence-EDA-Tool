# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

  ![CIRCUIT](https://github.com/user-attachments/assets/3b7b9fc0-957c-4358-a04b-59dd108a3c22)

#### 2. Transient Response Setup:
![ANALYSES_SETTINGS](https://github.com/user-attachments/assets/5ef20b0f-fc91-4373-8ca2-f267a3ce26ae)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:

 ![TRANS_SETTINGS](https://github.com/user-attachments/assets/1935e6b9-fb19-45d8-b9a6-c59ac3c217ce)


## Output
#### 1.Transient Analysis Output

![CADENCE_OUTPUT](https://github.com/user-attachments/assets/1dba966f-093c-494f-80d7-e882939fe62e)

#### 2.DC Analysis Output

![image](https://github.com/user-attachments/assets/e6b8b6c7-378f-449e-82a5-72286f238b02)

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











