

# Virtualization Concepts ☁️

## Core Components 🧱

* **Bare-Metal Server 🖥️**: A physical server without an operating system directly installed. It serves as the foundation for virtualization.
* **Hypervisor ⚙️**: Virtualization software installed on a bare-metal server. It manages resources and creates virtual machines.
    * In VMware, this is called an **ESXi server**. 🏢
* **Virtual Machine (VM) 💻**: A software-based emulation of a physical computer that runs on top of a hypervisor. Also known as a **guest** or **instance**.
* **Virtualization Manager 🎛️**: A centralized console or tool used to manage hypervisors and their associated virtual machines.
    * In VMware, this is called **vCenter**. 🏢

## Virtual Desktop Infrastructure 🖥️➡️💻

* **Virtual Desktop (VDI) 🌐**: A virtual desktop environment hosted on a server and accessible from any device, providing users with a consistent and personalized computing experience.

## Migration Strategies 🔄

* **P2V (Physical to Virtual) ➡️💻**: The process of migrating a workload from a physical server to a virtual machine.
* **V2V (Virtual to Virtual) 💻➡️💻**: The process of migrating a virtual machine from one hypervisor or environment to another.

## Efficiency and Management Tools 🛠️

* **VM Template 📄**: A pre-configured virtual machine image that can be used as a blueprint to quickly create multiple identical virtual machines.
* **Snapshot 📸**: A point-in-time copy of a virtual machine's state, allowing for rollback to a previous configuration.
* **Cloning 👯**: Creating an exact, independent copy of an existing virtual machine.
---
