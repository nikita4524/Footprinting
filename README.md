
# 🔍 Footprinting with Nmap
✅ Author
Nikita Patil
Student | Cybersecurity Enthusiast | Project Creator

This project demonstrates **footprinting** using the powerful Nmap tool on Kali Linux. The goal is to scan a remote host and identify open ports, services, and other key network details — a common step in ethical hacking and penetration testing.


## 🛠️ Tools Used

 **Nmap 7.95**
 **Kali Linux**
 **Terminal/Command Line**


## 📌 Command Used
nmap -A scanme.nmap.org -oN footprint_result.txt

-A: Enables OS detection, version detection, script scanning, and traceroute.
-oN: Saves the output to a file (footprint_result.txt).

📊 Sample Output

PORT        STATE   SERVICE       VERSION
22/tcp      open    ssh           OpenSSH 6.6.1p1 Ubuntu 
80/tcp      open    http          Apache httpd 2.4.7 (Ubuntu)
9929/tcp    open    nping-echo
31337/tcp   open    tcpwrapped



