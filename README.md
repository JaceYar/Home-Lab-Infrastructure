# 🏗️ Home Lab Infrastructure
**The virtualization and networking foundation for cybersecurity research and systems engineering.**


---

| 📖 Overview | |
| :--- | :---: |
| This repository documents the technical architecture of my personal Homelab. Built on **Proxmox**, this environment is a dedicated sandbox for: <br><br> <ul><li>**Networking Fundamentals:** Layer 2/3 switching, VLAN segmentation, and infrastructure basics.</li><li>**Defense-in-Depth:** Deploying SIEM solutions like **Wazuh** for real-time threat monitoring.</li><li>**Red Team Simulations:** Isolated penetration testing against targets like **Metasploitable** and **DVWA**.</li><li>**Software Validation:** Testing personally built networking tools, such as my **C++ Packet Sniffer**.</li></ul> | <img src="media/rack-angled.png" width="400" alt="Homelab Rack"> |
---

## 🔧 Core Infrastructure Tech Stack
* **Hypervisor:** `Proxmox` – Managing virtualized hardware resources.
* **SIEM/Monitoring:** `Wazuh` – Open-source platform for log analysis and threat detection.
* **Analysis:** `Wireshark` – Network protocol analyzer for inspecting traffic at the packet level.
* **Offensive Tools:** `Kali Linux` – Penetration testing distribution.
* **Targets:** `Metasploitable` & `DVWA` – Vulnerable systems for security practice.

---

## 🧪 Development & Testing Ground
This lab serves as the primary validation environment for my custom-coded networking tools.

### **Current Project:** C++ Packet Sniffer (Wireshark Clone)
I am utilizing this infrastructure to test a personally developed packet sniffer written in **C++**.

* **Validation:** Capturing live traffic generated between lab VMs (e.g., Kali to DVWA).
* **Performance:** Observing how the application handles data streams within an isolated virtual network.
* **Comparison:** Using the industry-standard Wireshark to verify the accuracy of my sniffer's output.

---

## 🚧 Infrastructure Roadmap
- [ ] **VLAN Validation:** Perform connectivity testing between segments to verify firewall/switch rules.
- [ ] **pfSense Integration:** Replace standard bridges with a virtualized firewall for advanced routing and network segmentation.
- [ ] **IP Management:** Implement a structured IP Schema for better lab scalability.

---

## 🔗 Connected Portfolios
* 🛡️ **[Cybersecurity-Portfolio](LINK_HERE):** Red Team / Blue Team research and lab reports.
* 💻 **[Software-Development](LINK_HERE):** Source code for my C++ Packet Sniffer and other networking tools.

---

## 📫 Contact
* **LinkedIn:** [Jace Yarborough](https:://www.linkedin.com/in/jace-yarborough-522b6429a)
* **Email:** jaceyarborough@proton.me

---

> [!IMPORTANT]
> All testing is performed in a safe, local, and legal environment for educational purposes only.
