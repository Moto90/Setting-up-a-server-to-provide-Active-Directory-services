# Windows Server 2022 VM Setup for Active Directory Hosting

This repository documents the steps involved in setting up a local virtual machine (VM) instance to host **Active Directory** services using **Windows Server 2022**. This is the foundational step in configuring directory services for enterprise environments.

---

## 🧰 Objectives

- Obtain a trial version of **Windows Server 2022**
- Install the OS on a local VM (e.g., using VirtualBox or VMware)
- Perform basic post-install configuration to prepare the server for future Active Directory role setup

---

## 🛠️ Technologies Used

- **Windows Server 2022**
- **VirtualBox** (or any virtualization tool of choice)
- **Local Host Machine** (Windows/Linux/Mac)

---

## 📋 Setup Steps

### 1. Download Windows Server 2022
- Access Microsoft's official evaluation center
- Download the ISO file for Windows Server 2022 (trial version)

### 2. Install Windows Server 2022 on a Virtual Machine
- Create a new VM instance in VirtualBox or your chosen hypervisor
- Allocate:
  - Minimum 2 CPUs
  - 4 GB RAM (recommended)
  - 60 GB storage
- Mount the ISO and start the installation

### 3. Perform Basic Configuration
- Set up a secure administrator password
- Assign a static IP (optional, but recommended)
- Rename the server (e.g., `AD-Host`)
- Ensure Windows Updates are enabled
- Enable remote desktop (optional for remote management)
- Take VM snapshots to preserve configuration state

---

## 📸 Screenshots

Include screenshots of the following:
- VM creation summary
- Installation progress screen
- Windows Server login screen
- Server Manager dashboard after initial setup

---

## 📝 Notes

- This lab does **not** include the Active Directory role installation—only the base VM and OS configuration.
- Ensure that virtualization is enabled in your BIOS/UEFI if you encounter errors starting the VM.

---

## 📁 Repository Structure

