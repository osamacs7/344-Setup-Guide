
---

# **Metasploit Framework - SSH Login Brute-Force Module**

This repository contains detailed steps for using the **Metasploit Framework** and its **SSH Login Module (`auxiliary/scanner/ssh/ssh_login`)** to brute-force **SSH credentials** on a specified target system. This is useful for **penetration testing** and **red teaming** engagements.

---

## **⚠️ Disclaimer**
This guide is intended for **educational purposes only**. Unauthorized access or brute-forcing systems without proper permission is **illegal** and **punishable by law**. **Only use this guide in authorized testing environments.**

---

# **What Is Metasploit?**
[Metasploit](https://www.metasploit.com/) is a popular **penetration testing platform** that helps security professionals and ethical hackers identify, exploit, and validate vulnerabilities within systems.

---

---

# **Installation Guide**
---

### **Step 1: Install Metasploit Framework**
1. **Update the System:**
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```

2. **Install Metasploit Framework:**
   ```bash
   curl https://raw.githubusercontent.com/rapid7/metasploit-framework/master/msfupdate | bash
   ```

3. **Launch Metasploit Console:**
   ```bash
   sudo msfconsole
   ```



---

# **Security Recommendations**
- **Never run this against unauthorized targets.**
- **Use encrypted VPNs** when testing externally.
- **Document findings** for authorized penetration testing reports.

---
