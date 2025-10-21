# Ubuntu-Server-Administration
## Overview
This project involved configuring and managing an Ubuntu virtual machine on Microsoft Azure to simulate real-world server administration tasks. Over the course of several assignments, I implemented services, hardened security, and automated processes used in enterprise environments.

---

## Key Implementations
- **User & SSH Management:** Created users, configured public-key authentication, disabled root login, and secured SSH with Fail2Ban.
- **Web Hosting:** Deployed Apache and PHP to host a custom index page and WordPress site.
- **Database Setup:** Installed and configured MySQL with PHP integration.
- **LDAP Integration:** Set up phpLDAPadmin and tested directory authentication for WordPress.
- **VPN Configuration:** Generated keys and established secure connections using OpenVPN.
- **Remote Access:** Enabled xRDP + XFCE for GUI remote access from macOS.
- **Firewall & Networking:** Used UFW and Vyatta routing to control traffic and simulate enterprise networking.
- **Automation:** Used Bash scripts and cron jobs for maintenance tasks and logging.

---

## Tools & Technologies
**OS:** Ubuntu 20.04 LTS  
**Services:** Apache, Nginx, MySQL, LDAP, VPN, NTP, Fail2Ban, OpenSSH  
**Languages:** Bash, PHP  
**Platform:** Azure Cloud VM  
**Other:** MS Remote Desktop, phpLDAPadmin, WordPress  

---

## Repository Contents
- `config-files/` – sanitized versions of key configuration files  
- `scripts/` – automation scripts used for setup  
- `docs/` – course reports and write-ups (PDFs)  
- `screenshots/` – verification images  

---

## Sample Output
![VM GUI](screenshots/rdp_gui.png)
![Apache Landing Page](screenshots/apache_page.png)

---

## 📚 Lessons Learned
- Managing users, groups, and permissions securely
- Configuring Linux networking, DNS, and routing
- Integrating authentication systems (LDAP, VPN)
- Automating builds and server monitoring
- Troubleshooting real-world deployment issues on cloud VMs
