# 🔥 Firewall Configuration Task

## 📋 Overview
This repository contains the completion of Task 4 from the Cyber Security Internship - setting up and configuring firewall rules on Windows/Linux systems.

## 🎯 Objective
Configure and test basic firewall rules to allow or block network traffic using Windows Firewall or UFW (Linux).

## ⚡ What I Did

### 🪟 Windows Firewall Configuration
1. 🔓 Opened Windows Defender Firewall with Advanced Security
2. 📋 Listed existing inbound and outbound rules
3. 🚫 Created rule to block inbound traffic on port 23 (Telnet)
4. 🧪 Tested the blocking rule with connection attempts
5. ✅ Added rule to allow specific services if needed
6. 📸 Documented all steps with screenshots

### 🐧 Linux UFW Configuration (if applicable)
1. 📊 Checked UFW status: `sudo ufw status`
2. 🔛 Enabled UFW: `sudo ufw enable`
3. 🚫 Blocked Telnet port: `sudo ufw deny 23`
4. ✅ Allowed SSH port: `sudo ufw allow 22`
5. 📋 Listed rules: `sudo ufw status numbered`
6. 🗑️ Removed test rules: `sudo ufw delete [rule_number]`

## 📁 Files Included
- 📸 `screenshots/` - Configuration screenshots
- 📝 `firewall-rules.txt` - Documentation of applied rules
- 💻 `commands.txt` - List of commands used
- 📄 `README.md` - This file

## 🎓 Key Learning Points
- 🔄 Understanding inbound vs outbound traffic filtering
- ⚠️ Importance of blocking insecure protocols (Telnet)
- 🛠️ Firewall rule management and testing
- 🔒 Network security best practices

## ✅ Testing Results
- 🚫 Successfully blocked port 23 connections
- ✔️ Verified rules are working as expected
- 🔄 Restored original configuration after testing

## 🛠️ Tools Used
- 🛡️ Windows Defender Firewall / UFW
- 💻 Command Prompt / Terminal
- 🌐 Network testing tools (telnet, netstat)

---
*🎓 Completed as part of Cyber Security Internship Program*
