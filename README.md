# Mini Project: Connecting Two Computers (Bus Topology)

## 📌 Project Overview
This project demonstrates the most basic network design in Cisco Packet Tracer:  
**two computers connected directly using a copper crossover cable**.  

Both devices are configured with static IP addresses in the **same subnet**, allowing them to successfully communicate via ICMP ping.

---

## 🏗️ Topology
![Topology Diagram]<img width="2560" height="1392" alt="Bus Topology" src="https://github.com/user-attachments/assets/d64a417b-af13-4980-901b-3bce30c69e2b" />


- **PC-1**: 192.168.10.10 / 255.255.255.0  
- **PC-2**: 192.168.10.15 / 255.255.255.0  
- Connection: **Copper Crossover** cable (required for direct PC-to-PC links)  

---

## ⚙️ Device Configuration
### PC-1
![PC-1 IP Configuration]<img width="2560" height="1392" alt="PC-1 IP config" src="https://github.com/user-attachments/assets/68e85d7c-20bd-4e06-9ccc-975340db94f2" />


### PC-2
![PC-2 IP Configuration]<img width="2560" height="1392" alt="PC-2 IP Config" src="https://github.com/user-attachments/assets/52079160-d905-49fc-9911-4f0aa955eaa4" />


---

## 🧪 Testing
Communication verified using **ping** from PC-2 to PC-1:

![Successful Ping]<img width="2560" height="1392" alt="Succesful Ping from PC-2 to PC-1" src="https://github.com/user-attachments/assets/316cc68d-31e3-4972-bbb2-19b8084b9ff2" />


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
