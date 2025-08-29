# The Real-World Vulnerability of Everyday Devices: An Empirical Cybersecurity Study  

 **Author:** Bozorov Ulugbek  
 **Date:** August 2025  

---

## Overview  
This repository contains my independent cybersecurity research paper:  
**“The Real-World Vulnerability of Everyday Devices: An Empirical Cybersecurity Study.”**  

The study investigates the **security posture of everyday devices**—including smartphones, laptops, IoT cameras, smart hubs, wearables, and smart TVs—through **sandboxed laboratory experiments**. It highlights how widespread reliance on weak default configurations, outdated firmware, and unencrypted communications exposes consumers to critical risks.  

---

## Methodology  

- **Lab Setup:** Sandboxed, isolated network (no public internet exposure).  
- **Devices Analyzed:** Smartphones, laptops, smart TVs, IoT cameras, smart hubs, wearables.  
- **Tools Used:**  
  - Nmap → network scanning & service discovery  
  - Wireshark → traffic inspection & protocol analysis  
  - OpenVAS → vulnerability assessment  
  - Metasploit → controlled exploit simulations  
  - Python scripts → automation & log parsing  

- **Risk Assessment Framework:** CVSS v3.1 (Common Vulnerability Scoring System).  

---

## Main Findings  

- **IoT Cameras & Smart Hubs** → Highest risk (outdated firmware, exposed ports, plaintext transmissions).  
- **Smart TVs** → Moderate risk (legacy software, unpatched vulnerabilities).  
- **Smartphones & Laptops** → Comparatively stronger, but still exposed to certain CVEs.  

**Example Results (Firmware & CVE Analysis):**

| Device Type   | Outdated Firmware (%) | High-Severity CVEs |
|---------------|------------------------|---------------------|
| Smartphones   | 10%                   | 2                   |
| Laptops       | 5%                    | 1                   |
| Smart TVs     | 40%                   | 4                   |
| IoT Cameras   | 50%                   | 5                   |
| Smart Hubs    | 25%                   | 3                   |
| Wearables     | 10%                   | 1                   |

---

## Recommendations  

1. Replace default credentials immediately after setup.  
2. Enable automatic firmware & software updates.  
3. Enforce encryption for all device communications.  
4. Segment IoT devices into separate subnets.  
5. Educate users on security hygiene.  
6. Encourage manufacturers to adopt baseline compliance standards.  

---

## Why is this important?

- **Academic Value:** Reproducible, empirical, cross-device security study.  
- **Professional Value:** Demonstrates advanced skills in vulnerability assessment, exploit simulation, and ethical cybersecurity practices.  
- **Portfolio Value:** Strong evidence of applied technical competence, suitable for competitions, internships, and university applications.  

---

## Contents  

- `https://drive.google.com/file/d/1OFsiHn7_Szs6Z8NYeWLAe5zGa0_0cGHU/view?usp=drive_link` → Full research paper (August 2025)  
-  

---

##  Ethical Disclaimer  

All experiments were conducted in a **closed, isolated sandbox environment**.  
No real-world systems, networks, or third-party devices were harmed or compromised.  

---

## About  

This project was completed as part of my **cybersecurity portfolio**.  
It indicates my passion in **offensive security, vulnerability research, and applied cybersecurity engineering**.  

---
