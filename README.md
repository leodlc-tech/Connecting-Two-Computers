# Mini Project: Connecting Two Computers (Bus Topology)

## 📌 Project Overview
This project demonstrates the most basic network design in Cisco Packet Tracer:  
**two computers connected directly using a copper crossover cable**.  

Both devices are configured with static IP addresses in the **same subnet**, allowing them to successfully communicate via ICMP ping.

---

## 🏗️ Topology
![Topology Diagram](images/Bus Topology.png)

- **PC-1**: 192.168.10.10 / 255.255.255.0  
- **PC-2**: 192.168.10.15 / 255.255.255.0  
- Connection: **Copper Crossover** cable (required for direct PC-to-PC links)  

---

## ⚙️ Device Configuration
### PC-1
![PC-1 IP Configuration](images/PC-1 IP config.png)

### PC-2
![PC-2 IP Configuration](images/PC-2 IP Config.png)

---

## 🧪 Testing
Communication verified using **ping** from PC-2 to PC-1:

![Successful Ping](images/Succesful Ping from PC-1 to PC-2.png)

**Result:** Replies received, proving that devices in the same subnet can exchange data when connected properly.

---

## 🎯 Learning Objectives
- Understand the concept of a **bus-style direct link** between two hosts.  
- Configure **static IP addressing** within the same subnet.  
- Verify communication using the **ping utility**.  
- Learn that a **copper crossover cable** is necessary for direct PC-to-PC connections without a switch or hub.

---

## 📂 Files
- [`Connecting-two-PCs.pkt`](Connecting-two-PCs.pkt) – Packet Tracer project file  
- Screenshots in `/images` folder  
- `README.md` (this documentation)

---

## 📚 Next Steps
This lab is part of a beginner networking series. Upcoming installments:  
1. Star Topology (using a central switch)  
2. Two Switches connected together  
3. Router integration  
4. Wireless connection  
5. DHCP simulation  
6. Application servers (HTTP, FTP, Email)  
7. IoT device simulation
