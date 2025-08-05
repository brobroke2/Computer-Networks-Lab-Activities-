# Experiment 2A: Demonstration of Peer-to-Peer (P2P) Network using Copper Cross-over Cable

## 🎯 Objective
To demonstrate the copper cross-over cabling by designing a Peer-to-Peer (P2P) network.

---

## 🧰 Components Required

| Device | Quantity |
|--------|----------|
| PCs    | 2        |
| Copper Cross-over Cable | 1 |

---

## 🗂️ Addressing Table

| Device | Interface | IP Address     | Subnet Mask     |
|--------|-----------|----------------|-----------------|
| PC0    | Fa0/0     | 192.168.10.1   | 255.255.255.0   |
| PC1    | Fa0/0     | 192.168.10.2   | 255.255.255.0   |

---

## 🛠️ Steps

1. Drag and drop **2 PCs** in the simulation window.
2. Select **Connectivity** > choose **Copper Cross-over Cable**.
3. Connect PC0 to PC1 using the cross-over cable.
4. On PC0:
   - Go to `Desktop` > `IP Configuration`
   - Set IP address: `192.168.10.1`
   - Subnet mask: `255.255.255.0`

  
5. On PC1:
   - Set IP address: `192.168.10.2`
   - Subnet mask: `255.255.255.0`

  

6. To verify connectivity:
   - Open Command Prompt on **PC0**
   - Type `ping 192.168.10.2`

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/48ed4d06-827c-4c2b-9c3b-312adaac70fd" />


   



Successfully demonstrated peer-to-peer network connection using a copper cross-over cable.

