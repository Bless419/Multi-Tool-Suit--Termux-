# Multi-Tool-Suit--Termux-
A professional all in one security and network analysis toolkit with beautiful GUI web 

# ⚡ Agent Security - Multi-Tool Suite

**Developed by Wayo**

---

## 🛡️ **15 Powerful Security Tools in One Suite**

A professional all-in-one security and network analysis toolkit with a beautiful web GUI.

---

## 🚀 **Quick Setup**

```bash
# 1. Install dependencies
pkg update && pkg upgrade -y
pkg install -y python python-pip
pip install requests

# 2. Create directory
mkdir ~/agent-multi-tool
cd ~/agent-multi-tool

# 3. Save files
# - multi_tool.py (main application)
# - launch.sh (launcher script)

# 4. Make executable
chmod +x multi_tool.py launch.sh

# 5. Run
./launch.sh
```

Then open: **http://localhost:8888**

---

## 🔧 **Available Tools**

### 1. 🔍 **Port Scanner**
- Scan open ports on any target
- Identify running services
- Fast and efficient scanning
- **Use**: `target: scanme.nmap.org, ports: 1-1000`

### 2. 📋 **WHOIS Lookup**
- Domain registration information
- Registrar details
- Expiration dates
- **Use**: `domain: example.com`

### 3. 🌐 **DNS Lookup**
