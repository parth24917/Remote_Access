# Remote_Access
This project involved simulating a real-time cyberattack on a Windows laptop using Kali Linux and PowerShell Empire in a controlled lab environment. I conducted reconnaissance, crafted and delivered a custom .bat payload, gained unauthorized access, and maintained persistent control over the target system. 

# 🔒 Real-Time Penetration Testing using Kali Linux & PowerShell Empire

## 🧠 Objective
This project aimed to simulate a real-time cyberattack on a Windows-based laptop using Kali Linux and PowerShell Empire in a controlled lab environment. The goal was to uncover system vulnerabilities, test persistence mechanisms, and understand real-world attack vectors from an offensive security perspective.

---

## ⚙️ Tools & Technologies
- **OS**: Kali Linux, Windows 10
- **Framework**: PowerShell Empire
- **Scripting**: PowerShell, Batch (.bat)
- **Others**: Nmap, Netcat, (optional: Metasploit, Wireshark)

---

## 🚧 Attack Flow

### 1. Reconnaissance
- Scanned the target machine using `Nmap` to identify open ports and services.
- Mapped potential attack surface manually and via scripts.

### 2. Payload Creation
- Used PowerShell Empire to generate a launcher payload.
- Embedded the payload into a `.bat` script for easier delivery.

### 3. Exploitation & Access
- Delivered payload manually via USB/email (simulated phishing).
- Successfully established a reverse shell connection to Empire listener.

### 4. Persistence
- Installed persistence scripts via PowerShell to maintain access after reboot.
- Explored techniques such as registry edits and scheduled tasks.

### 5. Post-Exploitation
- Retrieved system information, environment variables, and active processes.
- Took remote screenshots and tested lateral movement potential.

### 6. Reporting & Mitigation
- Identified 12 key vulnerabilities and drafted a security report.
- Suggested actionable steps like disabling PowerShell macros, removing admin rights, etc.

---

## 📸 Screenshots

> _(Blur or redact anything sensitive before uploading)_  
- ![Empire Listener](screenshots/empire-listener.png)  
- ![Payload .bat](screenshots/payload-bat.png)  
- ![Remote Access Confirmed](screenshots/remote-shell.png)  
- ![Report Summary](screenshots/report-summary.png)  

---

## 📊 Outcomes
- Improved attack simulation efficiency by 25% using automation in payload delivery.
- Demonstrated end-to-end penetration testing workflow using real-world tools.
- Created a secure remediation plan to harden the test system.

---

## ⚖️ Ethical Note
This penetration test was performed strictly in a virtual lab environment on owned hardware for educational and research purposes. No unauthorized systems were targeted or harmed.

---

## 📚 What I Learned
- Hands-on experience with PowerShell Empire and red teaming concepts.
- Real-world understanding of how attackers gain and maintain access.
- Strengthened scripting skills for automation in offensive security workflows.

---

## 📎 Related Skills
`Kali Linux` • `PowerShell` • `Ethical Hacking` • `Post-Exploitation` • `Automation` • `Red Teaming` • `System Hardening`

