# Experiment 2B: Simple LAN with Switch using Straight-Through Cables

## 🎯 Objective
To demonstrate the use of straight-through cabling by designing a basic Local Area Network (LAN) using a switch.

---

## 🧰 Components Required

| Device | Quantity |
|--------|----------|
| PCs    | 2        |
| Switch | 1        |
| Copper Straight-through Cables | 2 |

---

## 🗂️ Addressing Table

| Device | Interface | IP Address     | Subnet Mask     |
|--------|-----------|----------------|-----------------|
| PC0    | Fa0/0     | 192.168.10.1   | 255.255.255.0   |
| PC1    | Fa0/0     | 192.168.10.2   | 255.255.255.0   |

---

## 🛠️ Steps

1. Drag and drop **2 PCs** and **1 switch** into the console.
2. Connect PC0 to **Switch (Fa0/0)** using **Copper Straight-through Cable**.
3. Connect PC1 to **Switch (Fa0/1)** similarly.

   📸 _Insert screenshot here_

4. Configure PC0:
   - IP address: `192.168.10.1`
   - Subnet mask: `255.255.255.0`

5. Configure PC1:
   - IP address: `192.168.10.2`
   - Subnet mask: `255.255.255.0`
_

6. Check connectivity:
   - On PC1, open Command Prompt
   - Type `ping 192.168.10.1`


Successfully set up a simple LAN using a switch and straight-through cables.
