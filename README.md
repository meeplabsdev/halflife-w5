# Orange Pi Zero 3 HAT
|<img width="906" height="728" alt="image" src="https://github.com/user-attachments/assets/63c0a244-a349-46ad-ad35-98171d00b304" />|<img width="906" height="724" alt="image" src="https://github.com/user-attachments/assets/8652df47-8ef6-4950-af9d-cfe0334d4ac6" />|
|---|---|

This is a HAT for the Orange Pi Zero 3, which adds some extra features!

# What it is
This project was created for week 5 of [halflife](https://halflife.hackclub.com/)! I designed the schematic and PCB using [KiCad](https://www.kicad.org/), as a hat for the [Orange Pi Zero 3](http://www.orangepi.org/orangepiwiki/index.php/Orange_Pi_Zero_3). It adds the following features:
- New USB C power input, with better filtering and control (limited to 5v, maybe PD/QC in the future)
- Connections for the power, display controller and touch controller of [this](https://www.aliexpress.com/item/1005008698035882.html) display
- Headphone amplifier and 3.5mm jack for the LINEOUT exposed by the 13 pins
- Separate LoRa board that can be used via USB or connected to the HAT internally over SPI/UART
- 1 button and 1 rotary encoder on the front face, 5 buttons on the back face, all controls are along the side
- Support for connecting and using the 5 buttons from the IO board of the aforementioned display as extra inputs
- Almost entirely through-hole components, exceptions are the headphone amplifier, 4 JST connectors, large electrolytic caps and the mosfets
- Also its jam packed

# Hardware
Schematic:

<img width="1395" height="691" alt="image" src="https://github.com/user-attachments/assets/f0832cd9-8cd8-49b6-9ef8-e03bad12274e" />

PCB:
|<img width="962" height="773" alt="image" src="https://github.com/user-attachments/assets/00ef95e1-5d29-405b-be0e-e097d65697ae" />|<img width="960" height="771" alt="image" src="https://github.com/user-attachments/assets/f989617f-14cc-4549-b237-2e1fc7394522" />|
|---|---|

# Cost
This is a rough outline of the cost, see [`BOM.csv`](bom.csv) for more details.

| Part | Cost |
| --- | --- |
| [Main HAT](https://jlcpcb.com/) | $4.00 |
| [LoRa board](https://jlcpcb.com/) | $8.00 |
| [LoRa board stencil](https://jlcpcb.com/) | $7.22 |
| [LoRa antenna](https://www.aliexpress.com/item/1005008297942095.html) | $4.75 |
| [All board components](https://lcsc.com/) | $53.77 |
| **Total + Shipping** | **$99.70** |
