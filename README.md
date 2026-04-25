# Active-Directory-Lab

## 📌 Overview

Built a fully functional Active Directory lab environment using virtualization to simulate a real-world enterprise network.

## 🛠️ Technologies Used

- Windows Server 2019
- Windows 11 
- VirtualBox
- Active Directory (AD DS)
- DNS
- DHCP

## 🧱 Lab Architecture

- **Domain Controller:** DC01 (192.168.10.10)
- **Client Machine:** PC01 (DHCP assigned)
- **Domain:** lab.local

## ⚙️ Configuration Steps

### 1. Domain Controller Setup

- Installed Windows Server
- Configured static IP (192.168.10.10)
- Installed AD DS and DNS roles
- Promoted server to Domain Controller

### 2. Client Configuration

- Installed Windows 11 Pro
- Configured DNS to point to DC
- Joined domain (lab.local)

### 3. DHCP Setup

- Configured DHCP scope: 192.168.10.100–192.168.10.200
- Set DNS server to 192.168.10.10

### 4. Active Directory Management

- Created Organizational Units (OUs)
- Created users and groups
- Applied Group Policy Objects (GPO)

## 🧪 Testing & Validation

- Successful ping between client and server
- DNS resolution using nslookup
- Domain join successful
- DHCP assigning IP addresses dynamically

## 🎯 Key Skills Demonstrated

- Active Directory Administration
- DNS & DHCP Configuration
- Network Troubleshooting
- Virtualization (VirtualBox)
