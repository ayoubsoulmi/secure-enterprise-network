# Secure Enterprise Network Design (Cisco Packet Tracer)

This project demonstrates the design and implementation of a secure multi-building enterprise network using Cisco Packet Tracer.  
The final `.pkt` file contains the full configuration, including subnetting, VLANs, routing, device hardening, NAT/PAT, firewalls, and site-to-site VPNs.

---

## ⭐ Features Implemented

### 🔐 1. Device Hardening
- Encrypted privileged passwords  
- Console, VTY, and AUX protection  
- SSH-only remote access  
- MOTD security banner  
- Disabled unused ports and basic switch security  

### 🖧 2. Network Segmentation
- VLANs for Finance, Payroll, Admin, Director, PA, Amenities, Manufacturing, Testing, Warehouses, and Security  
- Separate IP subnets for each building and department  
- Reduced broadcast domains and improved internal isolation  

### 📡 3. Secure Dynamic Routing (RIP v2)
- RIP version 2 with MD5 authentication  
- Prevents unauthorized routing updates and route poisoning  

### 🚧 4. Firewall / ACL Controls
- ACL-based or zone-based firewalls  
- Inter-VLAN and inter-building traffic restricted to essential services  
- Least-privilege access between security zones  

### 🌐 5. NAT & PAT
- PAT for outbound internet access (Amenities network)  
- Internal networks protected from public exposure  
- IP conservation and endpoint anonymization  

### 🔐 6. Site-to-Site VPNs
- Encrypted VPN tunnels between buildings  
- Protects against MITM and eavesdropping  
- Verified encrypted connectivity between sites  

---

## 📁 Files in This Repository
- **final-network.pkt** — Final Cisco Packet Tracer simulation with all security features  

---

## 📘 Summary
This project demonstrates a complete secure enterprise architecture following industry standards and defense-in-depth principles.  
It includes segmentation, access control, encrypted communication, device hardening, and network-level protection for a realistic multi-building environment.

---

## 📬 Author
Ayoub Soulmi  
