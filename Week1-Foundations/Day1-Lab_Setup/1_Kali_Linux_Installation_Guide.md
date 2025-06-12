# Kali Linux Lab Setup Guide

## Tools Used
- VirtualBox 7.0
- Kali Linux 2023.4 (ISO)

## Installation Steps
1. **Download Kali ISO**:  
   Official link: [kali.org/get-kali](https://www.kali.org/get-kali/)
2. **Create Virtual Machine**:
   - RAM: 4GB | Storage: 50GB (Dynamic)
   - Network: Bridged Adapter
3. **Post-Install Setup**:
   ```bash
   sudo apt update && sudo apt full-upgrade -y
   sudo apt install wireshark tshark nmap

# Verification

  ```bash
  kali@kali:~$ ip a  # Confirm network interface
  ```
