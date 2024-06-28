# Home-lab-vm-setup
# Installing VMware Workstation on Your Computer

This guide provides detailed steps to install VMware Workstation on your computer, covering both Windows and Linux operating systems.

## Table of Contents
1. [Introduction](#introduction)
2. [System Requirements](#system-requirements)
3. [Downloading VMware Workstation](#downloading-vmware-workstation)
4. [Installing on Windows](#installing-on-windows)
5. [Installing on Linux](#installing-on-linux)
6. [Activation and Licensing](#activation-and-licensing)
7. [Post-Installation Configuration](#post-installation-configuration)
8. [Troubleshooting](#troubleshooting)
9. [References](#references)

## Introduction
VMware Workstation is a powerful virtualization software that allows you to run multiple operating systems on a single physical machine. This guide will walk you through the installation process for both Windows and Linux platforms.

## System Requirements
Before installing VMware Workstation, ensure your system meets the following requirements:
- **Operating System**: Windows 10 or higher, or a supported Linux distribution.
- **Processor**: 64-bit x86 CPU with at least 2 GHz.
- **Memory**: Minimum 4 GB RAM (8 GB or more recommended).
- **Disk Space**: At least 10 GB free space for installation and additional space for virtual machines.
- **Other**: BIOS-level hardware virtualization support (Intel VT-x or AMD-V).

## Downloading VMware Workstation
1. Go to the [VMware Workstation Pro download page](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html).
2. Select the appropriate version for your operating system (Windows or Linux).
3. Click on the download link and save the installer to your computer.

## Installing on Windows

### Step 1: Run the Installer
1. Locate the downloaded installer file (`.exe`) and double-click to run it.
2. If prompted by User Account Control, click `Yes` to allow the installer to make changes to your device.

### Step 2: Start the Installation
3. The VMware Workstation Setup Wizard will appear. Click `Next` to begin the installation.
4. Accept the End User License Agreement (EULA) by checking the box and clicking `Next`.

### Step 3: Choose Installation Options
5. **Installation Directory**: Choose the default location or specify a different folder for the installation.
6. **Enhanced Keyboard Driver**: Check the box if you want to install the enhanced keyboard driver for better compatibility with certain operating systems.
7. **Check for Product Updates**: Opt to enable or disable checking for product updates during startup.
8. **Join VMware's Customer Experience Improvement Program**: Opt in or out as per your preference.

### Step 4: Shortcuts and Install
9. Choose whether to create shortcuts on the Desktop and Start Menu, then click `Next`.
10. Click `Install` to begin the installation process.

### Step 5: Complete Installation
11. Once the installation is complete, click `Finish` to exit the Setup Wizard.
12. Restart your computer if prompted to complete the installation.

## Installing on Linux

### Step 1: Prepare Your System
1. Open a terminal window.
2. Update your system packages using the following commands:
   ```bash
   sudo apt update && sudo apt upgrade -y
   
For Debian-based systems like Ubuntu
sudo dnf update -y

For Fedora systems
sudo yum update -y

