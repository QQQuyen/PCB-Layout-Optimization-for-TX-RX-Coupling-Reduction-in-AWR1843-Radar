# PCB-Layout-Optimization-for-TX-RX-Coupling-Reduction-in-AWR1843-Radar

## overview
This project studies methods to reduce coupling between TX and RX antennas in a 77 GHz mmWave radar system using the AWR1843 chip.
The project focuses on PCB layout, antenna structures, transmission lines, and electromagnetic simulation.

## Contents
The project studies several methods used to reduce antenna coupling, including: Via stitching and via shielding, DGS, Metamaterial, Antenna rotation and arrangement, Different transmission line structure. The project explains why some methods are suitable or not suitable for mmWave PCB design.

Analyzed a 6-layer PCB stackup based on TI design guidelines for AWR1843 mmWave radar systems. RF signal layers. Ground structure. Dielectric materials. Transmission line requirements

Simulation of different antenna structures and RF layouts was performed using Keysight ADS to compare coupling performance through S-parameters.

Tool: Altium design, Keysight ADS

### Stackup PCB
<img width="300" alt="image" src="https://github.com/user-attachments/assets/e285b597-9ca6-410e-b09e-8808fefa591c" />
<img width="300"  alt="image" src="https://github.com/user-attachments/assets/7ac96024-8af6-4844-a3e1-3b0172b817bb" />
<img width="300"  alt="image" src="https://github.com/user-attachments/assets/8c48a9a4-69e8-4af1-9fa6-62ed56180e4d" />

### Anten
<img width="300"  alt="image" src="https://github.com/user-attachments/assets/732ce6b6-2933-4597-86db-9006dd3640e4" />
<img width="300"  alt="image" src="https://github.com/user-attachments/assets/4208a461-cc13-498f-9e27-745b88530c50" />

.

<img width="300"  alt="image" src="https://github.com/user-attachments/assets/6e46086e-b1ac-4bb8-bff3-34f23e24e804" />

### PCB 
<img width="400" alt="image" src="https://github.com/user-attachments/assets/e94ebad3-965b-4afb-b32c-9a99f95f4716" />


### Different antenna structures
<img width="400" alt="image" src="https://github.com/user-attachments/assets/fe324bac-0d8c-4af9-9fdc-f277537fefc6" />

.
<img width="300"  alt="image" src="https://github.com/user-attachments/assets/4ade2d37-2b3b-43fe-96e9-e33fee44fe72" />
<img width="300" alt="image" src="https://github.com/user-attachments/assets/666c4e0b-76c7-4c0f-b5c0-4f2498bbad26" />

<img width="300"  alt="image" src="https://github.com/user-attachments/assets/e6389933-a3f5-4ef3-b42e-280f4ee96de9" />
<img width="300" alt="image" src="https://github.com/user-attachments/assets/58a7dd28-a478-437b-b1a1-caaabb45c073" />







## Folder Structure


**ADS/** Keysight ADS simulation projects

**antencoupling/** PCB antenna structures for coupling analysis

**PCB_Project/** Schematic and PCB layout of the antenna section for AWR1843

**report/** Vietnamese project report and documentation

**References/**  AWR1843BOOST schematic, layout, and BOM; TI design guidelines for AWR1843; Theoretical reference documents; AWR1843 datasheet; Datasheets of substrate materials (ROGER, FR4)
