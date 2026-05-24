# Linux Network Services Deployment using Ubuntu & VirtualBox
This project demonstrates the installation, configuration, and management of essential Linux network services using Ubuntu Linux in a virtualized environment powered by Oracle VirtualBox. The system simulates a small enterprise network consisting of server and client machines communicating through configured virtual adapters.
The project focuses on practical implementation of networking concepts, Linux server administration, and deployment of commonly used network services.

# 🚀 Features
- Virtual network creation using Oracle VirtualBox
- Internet connectivity through NAT networking
- Secure private communication using Host-Only networking
- FTP server deployment for file transfer
- Apache web server hosting
- DNS server configuration for domain resolution
- DHCP server setup for automatic IP assignment
# 🛠️ Configured Services
## FTP Server
- Software: vsftpd
- Used for secure file sharing and transfer between systems
## Web Server
- Software: Apache2
- Hosts web pages accessible within the local network
## DNS Server
- Software: bind9
- Resolves domain names into IP addresses
## DHCP Server
- Software: isc-dhcp-server
- Automatically assigns IP addresses to client machines
# 🌐 Network Configuration
### Adapter 1 — NAT
Provides internet access for package installation and system updates.
### Adapter 2 — Host-Only Adapter
Creates an isolated internal network between virtual machines for secure communication.
# 💻 Technologies Used
Ubuntu Linux
Oracle VirtualBox
Apache2
vsftpd
bind9
isc-dhcp-server
⚙️ Project Workflow
Install Ubuntu on VirtualBox
Configure NAT and Host-Only adapters
Install required Linux network services
Configure FTP, DNS, DHCP, and Apache servers
Test communication between client and server systems
# 🎯 Project Objective

The objective of this project is to develop practical understanding of Linux networking, server administration, virtual networking, and deployment of enterprise-level network services in a virtual environment.

✅ Conclusion

This project successfully demonstrates the configuration and deployment of essential Linux network services using Ubuntu and VirtualBox. It provides hands-on experience with network administration, service management, and virtual infrastructure setup commonly used in enterprise environments.
