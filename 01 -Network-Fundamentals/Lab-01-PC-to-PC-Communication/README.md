# 🖥️ Lab 01: PC-to-PC Communication Using Copper Cross-Over Cable

## 📌 Overview

This lab demonstrates how to establish communication between two PCs using a Copper Cross-Over cable in Cisco Packet Tracer. IP addresses were configured manually, and connectivity was verified using the `ipconfig` and `ping` commands.

---

## 🎯 Objective

- 🔗 Connect two PCs using a Copper Cross-Over cable
- 🌐 Configure IPv4 addresses manually
- 🧪 Verify network configuration using `ipconfig`
- 📡 Test connectivity using `ping`
- 📚 Understand basic peer-to-peer communication

---

## 🖼️ Network Topology

```text
PC0  <------------>  PC1
```

---

## 🛠️ Devices Used

| Device                     | Quantity |
| -------------------------- | -------- |
| 🖥️ PC                      | 2        |
| 🔌 Copper Cross-Over Cable | 1        |

---

## 🌍 IP Address Configuration

| Device | IP Address   | Subnet Mask   |
| ------ | ------------ | ------------- |
| 🖥️ PC0 | 192.168.10.1 | 255.255.255.0 |
| 🖥️ PC1 | 192.168.10.2 | 255.255.255.0 |

---

## ⚙️ Configuration Steps

### 1️⃣ Add Two PCs

- Drag and drop two PCs into the workspace.

### 2️⃣ Connect the PCs

- Select **Copper Cross-Over Cable**.
- Connect PC0 and PC1.

### 3️⃣ Configure IP Addresses

#### 🖥️ PC0

```text
IP Address: 192.168.10.1
Subnet Mask: 255.255.255.0
```

#### 🖥️ PC1

```text
IP Address: 192.168.10.2
Subnet Mask: 255.255.255.0
```

---

## 🔍 Verification Commands

### 📋 Check Network Configuration

Run the following command on both PCs:

```cmd
ipconfig
```

### 📡 Test Connectivity

From PC0:

```cmd
ping 192.168.1.2
```

From PC1:

```cmd
ping 192.168.1.1
```

---

## ✅ Verification Results

### PC0 Ping Result

```text
Reply from 192.168.1.2: bytes=32 time<1ms TTL=128
```

### PC1 Ping Result

```text
Reply from 192.168.1.1: bytes=32 time<1ms TTL=128
```

---

## 🎉 Result

✔️ Successfully connected two PCs using a Copper Cross-Over cable.

✔️ IPv4 addresses were configured correctly.

✔️ `ipconfig` displayed the assigned IP configuration.

✔️ `ping` confirmed successful communication between both PCs.

---

## 📚 Commands Used

```cmd
ipconfig
ping
```

---

## 🧠 What I Learned

- 🌐 Basic IPv4 Address Configuration
- 🔌 Usage of Copper Cross-Over Cable
- 📋 Verifying IP settings using `ipconfig`
- 📡 Testing connectivity using `ping`
- 🖥️ Basic peer-to-peer networking concepts

---

## 📸 Screenshots

- 📷 topology.png

---

## 👨‍💻 Author

**Alok Gupta**  
🎓 Bachelor in Computer Engineering  
📚 Cisco Networking Labs Journey
