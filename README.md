# DC-DC Buck Converter – BL8034
## Project Overview

Designed a DC-DC step-down (Buck) Converter using the BL8034
switching regulator.

The circuit converts a higher DC input voltage into a regulated
lower DC output voltage using a switching regulator, power inductor,
input/output filtering capacitors, and a feedback resistor network.

The project was designed using EasyEDA with focus on practical
power-supply circuit design, component selection, power routing,
filtering, and PCB layout considerations.

## Key Features

- BL8034 buck converter IC
- DC input power interface
- Switching regulator topology
- Power inductor for energy storage
- Input filtering capacitors
- Output filtering capacitors
- Feedback voltage-setting resistor network
- Power input/output connectors
- Ground plane considerations
- Compact power-supply design
- EasyEDA schematic and PCB design

## Circuit Blocks

### Input Stage

The input stage provides DC power to the converter and includes
input capacitors for filtering and reducing input-side voltage
ripple and switching noise.

### Buck Converter Stage

The BL8034 operates as the main switching regulator. The switching
node drives the power inductor to transfer energy to the output.

### Output Stage

The output stage consists of the power inductor, output capacitors,
and feedback network to provide a regulated DC output.

### Feedback Network

The resistor divider connected to the feedback pin is used to
set and regulate the required output voltage.

## PCB Design Considerations

The PCB layout should consider:

- Short high-current switching paths
- Proper placement of input bypass capacitors
- Close placement of the inductor to the switching node
- Proper output capacitor placement
- Short feedback routing
- Ground-plane design
- Thermal management
- Power trace width
- Component placement
- Noise and EMI reduction
- DRC verification

### Schematic
<img width="2362" height="1672" alt="SCH_Schematic" src="https://github.com/user-attachments/assets/185fa09f-68fb-4cb2-9438-86f79680e94c" />

### PCB Layout
<img width="2160" height="1398" alt="PCB_PCB1_2026-10-06" src="https://github.com/user-attachments/assets/114c1972-e44c-41ee-b033-c45df7b64f56" />

### 3D PCB View
<img width="2160" height="1319" alt="3D_PCB1_2026-10-06" src="https://github.com/user-attachments/assets/6fb3fde0-48f1-404e-b94f-877b1f57be58" />




