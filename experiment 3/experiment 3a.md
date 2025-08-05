# 💻 Experiment 3 – Router Configuration

## 🎯 Objective
To demonstrate how to configure IP addresses on a router to enable communication between two PCs through it.

---

## 🧠 Pre-requisites
- Understanding of IP Addressing and Subnetting
- Classes of IP Addresses
- Basic Networking concepts

---

## 🛠️ Components Required

| Device  | Quantity |
|---------|----------|
| PCs     | 2        |
| Router  | 1        |
| Copper Cross-over Cable | 2 |

---

## 📋 Addressing Table

| Device   | Interface         | IP Address     | Subnet Mask      | Gateway         |
|----------|------------------|----------------|------------------|-----------------|
| PC0      | Fa0/0            | 192.168.10.2   | 255.255.255.0    | 192.168.10.1    |
| PC1      | Fa0/0            | 192.168.11.2   | 255.255.255.0    | 192.168.11.1    |
| Router0  | GigabitEthernet0/0 | 192.168.10.1 | 255.255.255.0    | -               |
| Router0  | GigabitEthernet0/1 | 192.168.11.1 | 255.255.255.0    | -               |

---

## 🧪 Procedure (5 Steps)

### 🔹 Step 1: Physical Setup
- Place 2 PCs and 1 Router on the simulation area (e.g., Cisco Packet Tracer).
- Connect:
  - PC0 → Router0 (GigabitEthernet0/0) using a **cross-over cable**
  - PC1 → Router0 (GigabitEthernet0/1) using a **cross-over cable**

### 🔹 Step 2: Configure PC0
- Click PC0 → **Config** tab → **FastEthernet0**
  - IP Address: `192.168.10.2`
  - Subnet Mask: `255.255.255.0`
- In **Settings**, set **Default Gateway**: `192.168.10.1`

### 🔹 Step 3: Configure PC1
- Click PC1 → **Config** tab → **FastEthernet0**
  - IP Address: `192.168.11.2`
  - Subnet Mask: `255.255.255.0`
- In **Settings**, set **Default Gateway**: `192.168.11.1`

### 🔹 Step 4: Configure Router Interfaces
- Click Router0 → **Config** tab
- Select **GigabitEthernet0/0**
  - IP Address: `192.168.10.1`
  - Subnet Mask: `255.255.255.0`
- Select **GigabitEthernet0/1**
  - IP Address: `192.168.11.1`
  - Subnet Mask: `255.255.255.0`

### 🔹 Step 5: Verify Connectivity
- Go to PC1 → **Desktop** → **Command Prompt**
- Run the command:
  ```bash
  ping 192.168.10.2
<img width="1307" height="517" alt="experiment 3a screenshot" src="https://github.com/user-attachments/assets/d9769711-36dd-4951-b6c2-8aeeccdf4801" />
<img width="538" height="446" alt="experment 3a screensot 2 " src="https://github.com/user-attachments/assets/c577200e-2c3e-4fbd-91ef-a779c1b307d3" />

