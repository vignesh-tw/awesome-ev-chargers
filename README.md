# awesome-ev-chargers

# ⚡ EV Charger Learning & Development Hub

Welcome to the **EV Charger Dev Hub** – a curated knowledge base for learning, building, and scaling **EV charging solutions** for:

- 🛵 Two-wheelers  
- 🚗 Four-wheelers  
- 🚌 Electric Buses  
- 🚛 Heavy-duty Trucks  

This page is your one-stop guide to **technologies, standards, hardware design, simulations, business strategy**, and **real-world deployments** of both **AC and DC EV chargers**.

Disclaimer: I took a bit of AI help to fetch contents from different sources, not all of them are validated and approved, feel free to raise a PR to improve this document 🙏

---

## 📘 Table of Contents

1. [Overview](#overview)
2. [Technical Whitepapers & Guides](#technical-whitepapers--guides)
3. [EV Charging Standards](#ev-charging-standards)
4. [Videos & Real-World Examples](#videos--real-world-examples)
5. [Simulation & Hardware Design](#simulation--hardware-design)
6. [Grid Integration & Smart Charging](#grid-integration--smart-charging)
7. [Fleet & Depot Charging for Heavy Vehicles](#fleet--depot-charging-for-heavy-vehicles)
8. [Business & Deployment Resources](#business--deployment-resources)
9. [Learning Roadmap](#learning-roadmap)

---

## 🧭 Overview

This repository helps new engineers, builders, and entrepreneurs understand and build EV charging systems from scratch—starting with **electronics and simulation** to **real deployment and business scaling**.

Whether you're prototyping a home AC charger or deploying a 450kW DC charger for electric buses, you'll find all the fundamentals and advanced resources here.

---

## 📄 Technical Whitepapers & Guides

| Title | Type | Link |
|-------|------|------|
| Comprehensive Review of EV Charging Architectures | Survey Paper | [Read](https://arxiv.org/abs/2209.15242) |
| Real-Time Simulation of EV Chargers (AC/DC) | Simulation Paper | [Read](https://arxiv.org/abs/2111.02506) |
| Charging Heavy-Duty Trucks: Fast vs Swapping | Analysis | [Read](https://arxiv.org/abs/2503.08080) |
| ICCT Guide: Charging for Battery-Electric Trucks | Technical Planning | [PDF](https://theicct.org/wp-content/uploads/2022/12/charging-infrastructure-trucks-zeva-dec22.pdf) |
| Siemens Whitepaper: Depot Charging for Fleets | Whitepaper | [PDF](https://assets.new.siemens.com/siemens/assets/api/uuid%3Ac96f7c8b-c737-4a2f-bca2-8038fd25bd5b/Whitepaper-Charging-Solutions-for-Electric-Commercial-Vehicles-Depots.pdf) |
| TE Connectivity: Time-to-Charge for Commercial Vehicles | Whitepaper | [PDF](https://www.te.com/content/dam/te-com/documents/industrial-and-commercial-transportation/global/ict-hivonex-addressing-the-time-to-charge-white-paper.pdf) |
| NYSERDA: Managed Charging & VGI | Smart Charging | [PDF](https://www.nyserda.ny.gov/-/media/Project/Nyserda/Files/Publications/Research/Transportation/22-09-Electric-Vehicle-Managed-Charging-White-Paper.pdf) |

---

## ⚙️ EV Charging Standards

| Standard | Description |
|----------|-------------|
| **IEC 61851** | AC and DC charging systems, general interface behavior |
| **IEC 62196** | Plug/connector types (Type 1, Type 2, CCS, CHAdeMO, GB/T) |
| **SAE J1772** | AC Charging connector and protocol (North America) |
| **SAE J3068** | 3-phase AC support for heavy EVs |
| **SAE J3105** | Pantograph-style automatic DC charging for buses |
| **ISO 15118** | Communication standard enabling Plug & Charge, V2G |

For quick reference:  
- [IEC 61851 - Wikipedia](https://en.wikipedia.org/wiki/IEC_61851)  
- [SAE J1772 - Wikipedia](https://en.wikipedia.org/wiki/SAE_J1772)  
- [ISO 15118 - Wikipedia](https://en.wikipedia.org/wiki/ISO_15118)  

---

## 🎥 Videos & Real-World Examples

| Title | Platform | Link |
|-------|----------|------|
| EV Charger + BMS + Controller Tutorial | YouTube | [Watch](https://www.youtube.com/watch?v=VAHbsqvyqDE) |
| IEC 62196 Connectors & Design Tutorial | YouTube | [Watch](https://www.youtube.com/watch?v=NAI8jJW04Vs) |
| Electric Bus Charging with Pantograph (Rotterdam) | YouTube | [Watch](https://www.youtube.com/watch?v=DYZBXdLctsc) |
| CUTRIC Inductive Charging for Buses | YouTube | [Watch](https://www.youtube.com/watch?v=5iawcx5WPjk) |

---

## 🛠 Simulation & Hardware Design

### 🔌 Hardware

- **Holtek Smart Charger (for 2W EVs)**  
  MCU-based charger with HT45F5Q-X – includes schematics and embedded code  
  🔗 [Holtek Website](https://www.holtek.com/en/products/mcu/obd?utm_source=chatgpt.com)

- **Totem Pole PFC + Full Bridge DC-DC**  
  Topology commonly used in on-board EV chargers (2kW to 22kW)

---

### 🧪 Simulation Tools

- **Simulink Example: Onboard Charger for 2-Wheelers**  
  Includes: AC/DC converter, Isolated DC-DC, Control Loops  
  🔗 [MathWorks Model](https://it.mathworks.com/help/sps/ug/on-board-charger-for-two-wheeler-electric-vehicle.html)

---

## ⚡ Grid Integration & Smart Charging

Understand how chargers interact with the utility grid:

- VGI (Vehicle Grid Integration)
- Time-of-use optimization
- Load balancing & demand response
- Plug & Charge security (ISO 15118)

🧾 Recommended Reads:
- [NYSERDA VGI Whitepaper](https://www.nyserda.ny.gov/-/media/Project/Nyserda/Files/Publications/Research/Transportation/22-09-Electric-Vehicle-Managed-Charging-White-Paper.pdf)
- [ISO 15118 Plug & Charge](https://en.wikipedia.org/wiki/ISO_15118)

---

## 🚌 Fleet & Depot Charging for Heavy Vehicles

| Resource | Type | Link |
|---------|------|------|
| Siemens Depot Charging Whitepaper | Fleet Deployment | [PDF](https://assets.new.siemens.com/siemens/assets/api/uuid%3Ac96f7c8b-c737-4a2f-bca2-8038fd25bd5b/Whitepaper-Charging-Solutions-for-Electric-Commercial-Vehicles-Depots.pdf) |
| TE Connectivity: 10-Minute Charging Design | Tech Whitepaper | [PDF](https://www.te.com/content/dam/te-com/documents/industrial-and-commercial-transportation/global/ict-hivonex-addressing-the-time-to-charge-white-paper.pdf) |
| CUTRIC Inductive Charging | YouTube Panel | [Watch](https://www.youtube.com/watch?v=5iawcx5WPjk) |

---

## 🏗 Business & Deployment Resources

- **Blink Charging: EV Station Deployment Guide**  
  Business plan, infrastructure tips, and location strategy  
  🔗 [Read Here](https://blinkcharging.com/blog/a-guide-to-ev-charging-station-design-for-business-owners)

- **India Focus**: Study local policies, FAME subsidies, DISCOM permissions, and make-in-India hardware sourcing.

---

## 🧠 Learning Roadmap

| Step | Focus | Resources |
|------|-------|-----------|
| ✅ Step 1 | Learn AC/DC conversion and charger architecture | [Whitepapers](#technical-whitepapers--guides), [Simulink](#simulation--hardware-design) |
| ✅ Step 2 | Understand global standards & connector types | [Standards](#ev-charging-standards) |
| ✅ Step 3 | Build prototype 2W/4W onboard chargers | [Holtek](#hardware), [MathWorks](#simulation--hardware-design) |
| ✅ Step 4 | Study high-power chargers (fleet, depots) | [Depot Papers](#fleet--depot-charging-for-heavy-vehicles) |
| ✅ Step 5 | Learn grid-smart and V2G integration | [VGI Paper](#grid-integration--smart-charging) |
| ✅ Step 6 | Plan business model & deployment | [Blink Charging](#business--deployment-resources) |

---

## 💡 Contributions Welcome

Feel free to fork, star, or contribute your own:

- Tutorials
- Circuit designs
- Simulation files
- Videos or reference materials

---

## 🛠 Made By

This repository is maintained by an aspiring EV entrepreneur and engineer with a vision to make affordable, scalable charging infrastructure for India and beyond.

---

**Let’s electrify the future, one charger at a time. ⚡**
