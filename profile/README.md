# neXa

**neXa is an open industrial automation framework built on Beckhoff TwinCAT 3.**

Developed by ATI, neXa provides reusable, standardized automation components that reduce development time, improve consistency, and simplify the development of industrial machines and automation systems.

---

## Why neXa?

Industrial automation projects often repeat the same fundamental functionality:
cylinders, valves, axes, devices, sequences, HMI integration, diagnostics, and communication.

neXa turns these recurring tasks into reusable building blocks.

Our goal is simple:

> **Spend less time rebuilding standard functionality and more time developing the machine.**

neXa is designed around:

- **Reusable components** – Standard functionality implemented once and reused across projects.
- **Consistent architecture** – Similar devices follow similar interfaces, behaviour and diagnostics.
- **Modular design** – Use only the libraries required by your application.
- **Faster development** – Reduce repetitive PLC and HMI engineering.
- **Hardware simulation** – Develop and test functionality without the complete machine hardware.
- **Industrial use** – Built from experience developing and commissioning real automation systems.

---

## neXa Ecosystem

neXa consists of independent TwinCAT libraries covering common automation functionality.

Examples include:

| Library | Purpose |
| --- | --- |
| **TcCylinder** | Pneumatic and hydraulic cylinder control |
| **TcDeviceBase** | Common foundation for neXa devices |
| **TcNexaHmi** | Integration with the neXa HMI ecosystem |
| ... | More libraries are being prepared |

Each library has its own repository, documentation, examples and release history.

---

## Getting Started

neXa is organized as a collection of independent TwinCAT libraries.

Each library repository contains:
- Installation instructions
- Supported TwinCAT versions
- Dependencies
- API documentation
- Usage examples
- Release notes
- Compatibility information

Choose the library you need and follow the documentation in its repository.
For most projects, start with the core libraries and add only the components your application requires.

---

## Built for TwinCAT 3

neXa is developed primarily for **Beckhoff TwinCAT 3** and follows the TwinCAT library model.

Libraries are versioned independently so projects can use the required versions while the framework continues to evolve.

---

## Open Source

neXa is intended to be publicly available for use by automation engineers, machine builders and system integrators.

We want the framework to become useful beyond our own projects and encourage feedback, testing and contributions from the automation community.

---

## About ATI

neXa is developed and maintained by **ATI – Automation Technology Integrator**.

We develop industrial automation software, robot integration, machine vision solutions and automation systems.

🌐 https://ati.mk

---
