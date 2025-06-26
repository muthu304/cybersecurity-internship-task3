# 🛡️ Cybersecurity Internship – Task 3: Vulnerability Scan using Nessus

## 🎯 Objective
Perform a basic vulnerability assessment on a local system using the Nessus Essentials vulnerability scanner and understand how to identify, analyze, and prioritize potential risks.

---

## 🛠️ Tools Used
- **OS**: Kali Linux
- **Vulnerability Scanner**: [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
- **Scan Type**: Full system scan
- **Scan Target**: Localhost (127.0.0.1)

---

## ⚙️ Setup & Execution

### 🔧 Installation Steps
1. Download Nessus `.deb` file from [Tenable Downloads](https://www.tenable.com/downloads/nessus).
2. Open Terminal and navigate to Downloads:
   ```bash
   cd ~/Downloads
---

## Sample Detected Vulnerabilities

-Apache HTTP Server < 2.4.52 Multiple Vulnerabilities
-Severity: Critical
-CVSS Score: 9.8
-Description: Several memory corruption vulnerabilities.
-Fix: Upgrade Apache to the latest version.
-OpenSSH < 8.5 Multiple Weaknesses
-Severity: High
-CVSS Score: 7.5

##Description: Older versions allow downgrade attacks.

-Fix: Update to OpenSSH 8.5 or later.
-Outdated Kernel Version
-Severity: Medium
-Description: Multiple known kernel vulnerabilities.
-Fix: Update the Linux kernel and reboot the system.


##🧠 Key Learnings

-Understood the process of vulnerability scanning.
-Differentiated between severity levels (CVSS).
-Learned the importance of patch management and regular scanning.
-Got familiar with Nessus Essentials and its web interface.

