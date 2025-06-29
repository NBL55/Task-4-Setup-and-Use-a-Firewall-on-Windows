# Task-4-Setup-and-Use-a-Firewall-on-Windows
Configure and test **Windows Firewall** to block **port 23 (Telnet)**, verify the block using Telnet, and understand how firewalls filter network traffic.
Tools Used
- Windows Firewall (`wf.msc`)
- PowerShell
- Telnet Client

---

## 📌 Steps Performed

### 1️⃣ Enable Telnet Client
Installed via:
- Control Panel → Programs → Turn Windows features on or off → Check **Telnet Client**.
- Or using PowerShell:
  ```powershell
  dism /online /Enable-Feature /FeatureName:TelnetClient
