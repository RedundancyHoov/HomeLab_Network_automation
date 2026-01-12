# Homelab Network Automation

This lab demonstrates automation of a small enterprise-style network using **Ansible**. It includes:

- **Juniper EX3400 switch** (Layer 3)  
- **Cisco 1921 router**  
- VLANs, routing, and connectivity testing  

Features:

- Gathers facts from devices (hostname, OS version, interfaces)  
- Uses **Juniper as a jump host** for legacy Cisco devices with old SSH crypto  
- Fully inventory-driven with group and host variables  
- Compatible with modern Linux Ansible control nodes  

This setup is ideal for experimenting with network automation, inventory management, and Ansible playbooks in a home lab environment.

