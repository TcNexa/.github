# 🏗 TcNexa Framework

**TcNexa** is a modular automation framework developed by **ATI Software Engineering DOO Skopje**, built on **Beckhoff TwinCAT 3**.  
It provides reusable TwinCAT libraries to simplify and standardize industrial machine programming.

---

## 🌟 Key Principles
- **Modular Design** – Each library focuses on a single purpose.
- **Reusable Function Blocks** – Write once, use everywhere.
- **Safety First** – Built-in error handling and safe states.
- **Hardware Simulation** – Test without real hardware.

---

## 📚 Available Libraries

| Library | Description | Repository |
|----------|-------------|------------|
| **TcCylinder** | Control of mono- and bi-stable cylinders | [Link](./TcCylinder) |
| **TcCylinderThreePos** | Three-position cylinder control | [Link](./TcCylinderThreePos) |
| **TcValves** | Valve control and utilities | [Link](./TcValves) |
| **TcSafety** | Safety and emergency stop logic | [Link](./TcSafety) |
| **TcUtils** | General helper functions and utilities | [Link](./TcUtils) |

---

## ⚙️ Requirements
| Component            | Minimum Version |
|----------------------|-----------------|
| TwinCAT 3 Engineering| 3.1.4024.22 |
| Visual Studio Integration | Included with TwinCAT |
| Tc2_Standard | Beckhoff default |
| Tc2_System   | Beckhoff default |

---

## 🚀 Getting Started
1. Clone the repositories you need:
   ```bash
   git clone https://github.com/ati-software-engineering/TcCylinder.git
