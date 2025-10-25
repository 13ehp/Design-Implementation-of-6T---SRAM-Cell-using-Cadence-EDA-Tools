
## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)



## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

<img width="1625" height="861" alt="Screenshot 2025-10-25 190939" src="https://github.com/user-attachments/assets/185f6cc7-55d1-443e-9133-941212aec24e" />




## Output
<img width="1621" height="854" alt="Screenshot 2025-10-25 191008" src="https://github.com/user-attachments/assets/44ffd82e-ef9e-4dec-bfbc-bdfd707f2a81" />
<img width="1617" height="857" alt="Screenshot 2025-10-25 191035" src="https://github.com/user-attachments/assets/d785ecc6-0a83-4b41-8c70-ccd4e66fb8d6" />

<img width="1622" height="864" alt="Screenshot 2025-10-25 191107" src="https://github.com/user-attachments/assets/8acf7d54-529c-4655-a7e3-611c46c27a5c" />







## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


