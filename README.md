# Week 1 - Project Module 1: Cybersecurity Lab Setup

## Project Overview
This project documents the step-by-step setup of a secure Cybersecurity Testing Lab using **Oracle VirtualBox** and **Kali Linux** based on the Week 1 instructions.

## Phase 1: VirtualBox Network Configuration
A dedicated virtual network was successfully configured with the following parameters:
- **Network Type:** NAT Network
- **Network Name:** NatNetwork
- **IPv4 Prefix:** 10.0.0.0/24
- **DHCP Server:** Enabled

## Phase 2: Guest OS Installation & Settings
- **Operating System:** Kali Linux (Pre-built VirtualBox architecture).
- **Network Adapter:** Connected straight to the created `NatNetwork`.
- **System Integration:** Enabled Bidirectional Shared Clipboard and Drag'n'Drop.

## Phase 3: Static IP Configuration
Inside the Kali Linux interface, the network adapter settings were configured manually:
- **IP Address:** 10.0.0.2
- **Netmask:** 24 (255.255.255.0)
- **Gateway:** 10.0.0.1
- **DNS Server:** 8.8.8.8

## Phase 4: Environment Snapshot
- A safe laboratory restore point was successfully created and named **"clean install"** to protect the base setup from future configuration issues.
