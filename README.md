# Smart Grid Cyber-Sentinel
Smart Grid Cyber-Sentinel is an interactive educational tool designed to visualize cybersecurity vulnerabilities within a modern Energy Production and Distribution ecosystem. Based on the lecture "Challenges of Digital Security" by Dr. Raoul Guiazon, this application transforms theoretical security concepts into a tangible, multi-step simulation.
## 🚀 Overview
The application provides a high-fidelity representation of a Smart Grid's architecture, divided into three critical zones:
* Zone A: Generation & Transmission (Power Plants, Substations)
* Zone B: Distribution & Operations (SCADA, Historian, HMI)
* Zone C: Consumer Edge (Smart Meters, Industrial IoT)

## ✨ Key Features
* Interactive Asset Mapping: Click on any physical or digital asset in the grid to view its specific vulnerabilities.
* Context-Sensitive Attack Menus: Each asset reveals a list of historically relevant or theoretical cyber-attacks (e.g., Replay Attacks, SQL Injection, Ransomware).
* Manual Propagation Control: Navigate through the four stages of a cyber-attack:
** Intrusion: Initial point of entry.
** Exploitation: Protocol-level manipulation.
** Delivery: Payload execution on target systems.
** Impact: Final grid-level consequences and disruptions. 

* Live Intelligence Feed: Detailed "terminal-style" feedback explaining the technical nuances and attacker methodology for every step.
* Visual Feedback: Dynamic CSS animations and state changes visualize data flow corruption across the infrastructure.

## 🛠️ Technology Stack
* Frontend: Single-file HTML5/CSS3 
* Logic: Vanilla JavaScript / TypeScript

## 📖 Glossary of Attacks
The simulator includes detailed modeling for:
* HMI Hijacking (Blind Operator Attack)
* DNP3 & Zigbee Replay Attacks
* Firmware Poisoning (Supply Chain Attack)
* Man-in-the-Middle (MitM) on Load Management
* SQL Injection on Data Historians
* Digital Twin Desynchronization
