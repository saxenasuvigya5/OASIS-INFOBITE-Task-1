# Task 1: Basic Network Scanning with Nmap

## 🔍 Objective
The goal of this task is to perform a basic network scan using **Nmap** to identify open ports and running services on a local machine or virtual machine (VM). This task helps in understanding how attackers may profile a system and how defenders can harden it.

---

## 🛠 Tools Used
- **Nmap**: A powerful open-source network scanning tool used for security auditing and network discovery.

---

## 🧪 Steps Performed

1. **Installation of Nmap**
   - Installed Nmap on the system using the package manager.
     - For Linux: `sudo apt install nmap`
     - For Windows: [Downloaded from official website](https://nmap.org/download.html)

2. **Performed a Network Scan**
   - Targeted a local VM with the following basic scan:
     ```
     nmap -sS -Pn -T4 <target-ip>
     ```

3. **Identified Open Ports and Services**
   - Example output:
     - Port 22/tcp → SSH
     - Port 80/tcp → HTTP
     - Port 443/tcp → HTTPS

4. **Documented the Findings**
   - Each open port and associated service was analyzed for potential vulnerabilities.
   - Common reasons for concern:
     - Port 22 (SSH): If default credentials are used, it can be a major risk.
     - Port 80/443 (HTTP/HTTPS): Web services may have exploitable vulnerabilities.
     - Unknown ports/services: May indicate hidden or suspicious services.

---

## 📁 GitHub Deliverables

- `nmap_scan_results.txt`: Contains the full output of the Nmap scan.
- `README.md`: This documentation file explaining the task and results.
- Screenshots of the Nmap scan output have been added to `/screenshots` folder.

---

## 🎥 Demo Video (Optional)
**How to Perform a Basic Network Scan with Nmap**  
The video explains:
- Installing Nmap
- Running a scan
- Interpreting the results

---

## ✅ Internship Requirement
This task is marked as **required** for successful completion of the cybersecurity internship with Oasis Infobyte.

---

## 📌 Notes
- Ensure that scanning is done only on systems you own or have permission to scan.
- Unauthorized scanning may be considered illegal or unethical.

---

