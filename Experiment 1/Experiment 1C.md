# Part 3: Study of Network Cables and Color Codes

## Overview
This document provides an in-depth study of different types of network cables used in computer networking, focusing on copper and fiber optic cables. It also covers the standard color codes for copper straight-through and crossover cables, along with explanations on the purpose and typical use cases of each cable type within a network.

---

## 1. Types of Network Cables

### Copper Cables
- **Straight-Through Cable**  
  Used to connect different types of devices (e.g., computer to switch, switch to router). The wiring is identical on both ends (pin 1 to pin 1, pin 2 to pin 2, etc.).

- **Crossover Cable**  
  Used to connect similar devices directly (e.g., computer to computer, switch to switch). It crosses the transmit and receive pairs, allowing direct communication without a switch or hub.

### Fiber Optic Cables
- **Single-Mode Fiber (SMF)**  
  Transmits infrared laser light (wavelength ~1310 or 1550 nm) over long distances with minimal loss. Used in WANs and long-distance telecommunications.

- **Multi-Mode Fiber (MMF)**  
  Transmits infrared LED light (wavelength ~850 nm) for shorter distances, typically within LANs, data centers, and building backbones.

---

## 2. Standard Color Codes for Copper Cables

### Straight-Through Cable (TIA/EIA 568B Standard)
| Pin | Wire Color   |
|------|-------------|
| 1    | White/Orange|
| 2    | Orange      |
| 3    | White/Green |
| 4    | Blue        |
| 5    | White/Blue  |
| 6    | Green       |
| 7    | White/Brown |
| 8    | Brown       |

*(Both ends use the same wiring)*

### Crossover Cable
| Pin | Wire Color (End 1) | Wire Color (End 2) |
|------|--------------------|--------------------|
| 1    | White/Orange       | White/Green        |
| 2    | Orange             | Green              |
| 3    | White/Green        | White/Orange       |
| 4    | Blue               | Blue               |
| 5    | White/Blue         | White/Blue         |
| 6    | Green              | Orange             |
| 7    | White/Brown        | White/Brown        |
| 8    | Brown              | Brown              |

---

## 3. Purpose and Usage of Each Cable Type

| Cable Type            | Purpose                                           | Usage Example                             |
|-----------------------|-------------------------------------------------|------------------------------------------|
| Copper Straight-Through| Connects different device types for communication| PC to switch, switch to router           |
| Copper Crossover      | Connects similar device types directly           | PC to PC, switch to switch (without hub) |
| Single-Mode Fiber     | High-speed, long-distance data transmission      | WAN links, long-distance backbone        |
| Multi-Mode Fiber      | Medium-distance high-speed connections           | LANs, data centers, building backbones   |

---

## References
- Cisco Networking Academy: Cabling and Network Media  
- TIA/EIA-568-B Wiring Standard  
- Fiber Optic Association: Fiber Types and Applications  
