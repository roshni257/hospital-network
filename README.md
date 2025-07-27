# 🏥 Hospital Network Simulation - Cisco Packet Tracer

This project is a simulation of a **hospital network** designed for SVP Hospital in Ahmedabad, India using **Cisco Packet Tracer**. It showcases a realistic and scalable hospital infrastructure, including separate zones for reception, staff, ICU, patient rooms, doctor's offices, data center, and associated college and classroom networks.

---

## 📁 Project Overview

The network is segmented into **eight functional sections**, each with its own devices, access points, and subnets, connected to a centralized data center:

1. **Reception**
   - Multiple PCs for administrative tasks
   - Connected to main switch and firewall (ASA 5506)
   - Subnet: `192.168.2.0/24`

2. **Staff Room (VS NICU)**
   - Staff PCs and an IP Phone for internal communication
   - Subnet: `192.168.2.0/24`

3. **Intensive Care Unit (ICU)**
   - Patient monitoring systems and terminal access
   - Subnet: `192.168.2.0/24`

4. **Doctor's Office**
   - Doctor's PCs and a wireless access point
   - Subnet: `192.168.4.0/24`

5. **Central Data Center**
   - Core switch (handling all major routing)
   - EMR/EHR Server, File Storage Server, Backup Server
   - VLANs for Medical, Admin, IoT, and Guest:
     - VLAN 10 - Medical: `192.168.10.0/24`
     - VLAN 20 - Admin: `192.168.20.0/24`
     - VLAN 30 - IoT: `192.168.30.0/24`
     - VLAN 40 - Guest: `192.168.40.0/24`

6. **Patient Rooms**
   - Wireless laptops for patient use
   - Wi-Fi router with security enabled (WEP key: `1111222233`)
   - Subnet: `192.168.50.0/24`

7. **SBB College**
   - Workstations for hospital college department
   - Connected via Switch2 to Central Data Center

8. **Student Classroom**
   - Laptops, Smartphones, and Wireless Access Points
   - Demonstrates educational or training access
   - IoT simulation elements included

---

## 🔌 Technologies Used

- **Cisco Packet Tracer**
- **Switches:** Cisco 2960-24TT
- **Router:** Wireless Router 2811
- **Firewall:** ASA 5506-X
- **Servers:** EHR System, File Server, Backup Server
- **Wireless Access Points** & IP Phones
- **VLAN Configuration** for network segmentation
- **Wi-Fi Security** with WEP

---

## ⚙️ Features

- Segregated VLANs for better performance and security
- Server infrastructure supporting EHR and file storage
- Real-time patient and staff connectivity simulation
- Wireless and wired devices integration
- Classroom and college network extension for training/education
- Simulated IP addressing and network services

---

## 🛠️ How to Use

1. Open the project file (`.pkt`) using **Cisco Packet Tracer 8.x or later**.
2. Run simulation mode to monitor traffic flow.
3. Test communication between departments (ping, file access).
4. Modify VLANs, subnets, or servers to suit other institutions.

---

## 📌 Notes

- All IP addressing is simulated and does not reflect real hospital data.
- Wireless keys and server configurations are generic and for demonstration purposes only.
- Best viewed on devices with large screen due to network complexity.

---

## 📷 Project Screenshot

<img width="631" height="335" alt="image" src="https://github.com/user-attachments/assets/f95c085e-4c8d-4f90-bf98-59016bdbeaa4" />


---

## 🧑‍💻 Author

**Roshni Rana**  
B.Tech CSE | Minor in Marketing  
UI/UX & Network Simulation Enthusiast

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

