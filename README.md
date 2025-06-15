
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


## Output


![Image](https://github.com/user-attachments/assets/0ba22bb2-810c-4a74-921f-d6a2236e716c)
![Image](https://github.com/user-attachments/assets/75ebea78-0f9e-45d2-95ce-541a6c66d5d0)
![Image](https://github.com/user-attachments/assets/12e4ff0c-b1d8-4451-9e7b-15caf225a791)
![Image](https://github.com/user-attachments/assets/3853352e-8f2a-49ec-a23e-3f6561e7168d)
![Image](https://github.com/user-attachments/assets/e2502ac0-8ac0-4bba-bf86-4a7a905ea7d9)
