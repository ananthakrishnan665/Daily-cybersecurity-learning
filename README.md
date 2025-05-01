# Daily-cybersecurity-learning
Tracking my daily learning
# Day 1 - Cybersecurity Basics and Lab Setup

## ✅ What I Learned Today

- Understood what cybersecurity means and why it is critical in today's world.
- Learned about different types of cyber attacks (Malware, Phishing, Ransomware, DDoS, etc.).
- Explored the basic role and responsibilities of a SOC Analyst.
- Successfully installed Kali Linux using VirtualBox for creating a safe lab environment.
- Started my 6-week cybersecurity challenge with daily commitment.

## 📅 Date
April 26, 2025

## 🔥 Notes
Building strong basics is the foundation for becoming a successful cybersecurity professional. Consistency matters more than speed!



# Day 2 - Linux Commands + Cybersecurity Basics

## ✅ What I Practiced:
- Basic Linux navigation and file handling commands
- System information and user permission commands
- Practiced inside Kali Linux terminal

## ✅ What I Learned:
- CIA Triad importance in cybersecurity
- How Firewalls and IDS/IPS protect systems
- Types of cyber attacks (phishing, malware, social engineering)

## 📅 Date
April 27, 2025

## 🔥 Reflection:
feeling something fresh.

## Day 3 - Intermediate Linux Skills & Cybersecurity Basics
#🚀 Today's Focus:
1.Intermediate Linux Skills
2.Cybersecurity Concepts: Threat Actors and Attack Vectors

##🖥️ Commands Practiced:
➔ Linux File Permissions:
chmod — Change file permissions

chown — Change file ownership

chgrp — Change file group ownership

➔ User Management:
adduser — Create a new user

deluser — Delete a user

passwd — Set or change user password

su  — Switch user

whoami — Display current username

##🛡️ Cybersecurity Concepts Learned:
Threat Actors — Individuals or groups behind cyber attacks (e.g., Hackers, Nation-states, Insiders, Cyber crimimals, Hacktivist, cyber Terrorist etc)

Attack Vectors — Methods used to breach systems (e.g., Malware, Phishing, Exploiting vulnerabilities etc)

##🧠 Conclusion:
Understanding Linux permissions is essential to secure files and systems.
Proper user management helps prevent unauthorized access.
Recognizing common threat actors and attack vectors builds strong cyber defense awareness.

##📂 Practice Artifacts:
Test files for permission changes
User creation and switching exercises
Notes on threat actors and attack vectors
Test multiple usecases

##📅 Date:
April 28, 2025


📅 Day 4 - Linux Networking Commands and Network basics
Today’s Focus:
Network basics
Theory learned:
1. IP Address (IPv4 vs IPv6) - IP Address: Unique ID for a device on a network.

IPv4: 32-bit  – limited addresses.

IPv6: 128-bit – almost unlimited.

2. MAC Address - Hardware ID of a network interface .

3, Subnet Mask, Gateway, DNS
Subnet Mask: Defines local network range (e.g., 255.255.255.0).

Gateway: Router IP to access outside networks(Internet).

DNS: Converts domain names to IPs (e.g., google.com → 142.250.190.14).

4. DHCP & Auto IP Assignment
DHCP auto-assigns IP, Subnet, Gateway, and DNS.

Devices request an IP, and DHCP server responds with settings.

5. Check Network Info - ifconfig 

6. Manually Set IP
Windows/macOS/Linux: Network settings → set IP to “Manual” or “Static” → enter IP, Subnet, Gateway, DNS.



#Understanding and practicing essential Linux networking commands used by SOC analysts and cybersecurity professionals.

🔧 Commands Practiced:
ip a – Displays all IP addresses and interfaces.

ip route – Shows routing table.

hostname -I – Displays my system IP address.

ping google.com – Tests internet connectivity (Here i select Google).

traceroute google.com – Traces route to a domain.

nslookup google.com – Performs a basic DNS lookup.

dig google.com – Performs an advanced DNS query.

netstat -rn – Displays routing table and interface info.

ifconfig – Displays network interfaces (legacy tool).

🧠 What I Learned:
What is IP Address, MAC Address, Subnet Mask, Gateway, DNS, and DHCP

check device's network information

How to manually configure IP

How to view IP and routing details.

How to trace and test network connectivity.

How DNS works and how to inspect it with dig and nslookup.

How SOC analysts use these tools for incident response and diagnostics.

##📅 Date:
April 29, 2025


# 🚀 Day 5 – Linux Permissions and User Management

## ✅ What I Learned Today

### 🔐 File & Directory Permissions
- **Read (r), Write (w), Execute (x)** permissions for User, Group, and Others
- Viewing permissions: `ls -l`
- Modifying permissions:
  - `chmod 755 filename`
  - Symbolic method: `chmod u+x file`
- Special permissions:
  - SUID (chmod 4755)
  - SGID (chmod 2755)
  - Sticky bit(chmod +t)
  - visudo- Add to sudo

### 👤 User & Group Management
- Add user: `adduser username`
- Delete user: `deluser username`
- Modify user: `usermod -aG groupname username`
- Create group: `addgroup groupname`
- View users: `cat /etc/passwd`
- View groups: `cat /etc/group`
- Set/change password: `passwd username`

### 🛡 Security Relevance
- Proper permissions prevent unauthorized access and privilege escalation.
- Misconfigurations like world-writable files or wrong ownership can be exploited.

## 🔁 Commands Practiced
```bash
ls -l
chmod 755 test.sh
chmod u+x file
chown user:group file
adduser test1
deluser test1
usermod -aG sudo test1
passwd test1
##📅 Date:
April 30, 2025


# Day 6: Networking Basics

## 🧠 What I Learned
- What is an IP address (IPv4 vs IPv6)
- MAC Address
- Subnet Mask
- Default Gateway
- DNS (Domain Name System)
- Types of IP Addresses (Private vs Public, Static vs Dynamic)
- What is DHCP (Dynamic Host Configuration Protocol)
- Basic Networking Commands: ping, ip a, ifconfig, netstat

## 💻 Commands Practiced

ping google.com
ip a
ip route   
ifconfig
netstat -r
traceroute google.com  
nslookup google.com


## 📝 Notes
- IP is like a digital address to identify devices on a network.
- MAC is a unique hardware ID burned into the network card.
- Subnet Mask separates the network and host portions of an IP.
- DNS resolves domain names into IP addresses.
- DHCP dynamically assigns IP addresses to devices.

## 🔁 Addons
- Difference between Static and Dynamic IP
- Private IP Ranges and their uses

##📅 Date:
May 1, 2025
