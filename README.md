# 🌐 Corporate Office Network Simulation  

![Cisco Packet Tracer](https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-blue)  
![Status](https://img.shields.io/badge/Status-Completed-success)  
![Networking](https://img.shields.io/badge/Networking-DHCP%2C%20OSPF%2C%20VLANs%2C%20DNS-orange)  
![License](https://img.shields.io/badge/License-MIT-lightgrey)  

This project demonstrates the design and implementation of a **corporate office network** using **Cisco Packet Tracer**. The network integrates VLANs, DHCP, OSPF, DNS, HTTP, and Email servers to simulate a real enterprise environment.  

---

## 📂 Project Structure  

- **`project_galaxy1.pkt`** → Main Cisco Packet Tracer simulation file  
- **`docs/`** → Documentation & diagrams  
  - `report.pdf` → Full networking lab report  
  - `block_diagram.png` → High-level network topology  
- **`configs/`** → Device configurations (routers & switches)  

---

## 🚀 Features  

- VLAN segmentation & switch trunking  
- DHCP for automatic IP allocation  
- OSPF routing across multiple routers  
- Sub-interfaces with encapsulation  
- HTTP, Email & DNS server setup  
- Tested with `ping`, `tracert`, and client applications  

---

## 📐 Network Topology  

![Network Block Diagram](/docs/block%20diagram.png)

---

## ▶️ How to Run  

1. Install **Cisco Packet Tracer**.  
2. Open `project_galaxy1.pkt`.  
3. Start all devices in the simulation.  
4. Test the network:  
   - Run `ipconfig` on PCs → verify DHCP  
   - Use `ping` / `tracert` → check connectivity  
   - Access hosted web page (`http://domainname`)  
   - Send/receive emails via configured clients  

---

## 📊 Results  

- ✅ DHCP successfully assigned IPs  
- ✅ VLAN communication worked via trunking  
- ✅ Website accessible via DNS  
- ✅ Email system functional  

---

## 👨‍💻 Author  

**Emran Bhuiyan (Anik)**  
📚 B.Sc. in Computer Science & Engineering  
🏫 Eastern University, Spring 2024  
🖥 Course: Computer Networks Lab (CSE 415)  

---

## 📜 License  

This project is licensed under the **MIT License** – free to use and modify with credit.  
