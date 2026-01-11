[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

# The Inner Workings of Offensive Security

A comprehensive 210-page field guide bridging **red team** and **blue team** 
perspectives on Windows exploitation, attack detection, and defensive strategy.

## 📥 Download

**[⬇️ Download the Complete Guide (PDF)](https://github.com/ofekderi/The-Inner-Workings-of-Offensive-Security/raw/main/The-Inner-Workings-of-Offensive-Security.pdf)**

Or browse directly: [View on GitHub](https://github.com/ofekderi/The-Inner-Workings-of-Offensive-Security/blob/main/The-Inner-Workings-of-Offensive-Security.pdf)

---

## 📋 What's Inside

### Fundamentals
- Windows authentication mechanisms (NTLM, Kerberos, CBA)
- Active Directory security architecture
- AAA principles (Authentication, Authorization, Auditing)
- Attack frameworks (MITRE ATT&CK, Cyber Kill Chain)

### Initial Attack Phase
- Passive & active reconnaissance tools
- OSINT frameworks (Shodan, Maltego, Subfinder, Sherlock)
- Network scanning (Nmap, Masscan)

### Credential Extraction
- Mimikatz modules & techniques
- LSASS memory dumping
- Kerberos ticket extraction
- Pass-the-Hash & Overpass-the-Hash attacks
- LOLBAS & LOLDrivers exploitation

### Privilege Escalation
- Service account abuse
- Token impersonation (Incognito)
- Potato exploits (PrintSpoofer, GodPotato, JuicyPotato)
- COM object hijacking
- LSASS protection bypass techniques

### Lateral Movement
- PsExec & Impacket lateral exploitation
- WinRM & PowerShell remoting
- RDP session hijacking
- SMB relay attacks (Responder + ntlmrelayx)
- SSH tunneling for pivoting
- Azure Hybrid Worker abuse
- PetitPotam coercion attacks

### Domain Controller Attacks
- BloodHound path analysis
- Kerberoasting & TGS cracking
- Golden Ticket generation
- DCSync credential extraction
- DCShadow rogue DC injection
- ADCS abuse (ESC1, ESC8)
- Skeleton Key attacks
- Zero Logon (CVE-2020-1472)

### Persistence Mechanisms
- Registry Run Keys
- Scheduled Tasks
- Service creation
- WMI Event Subscriptions (fileless)
- COM object hijacking

### C2 Infrastructure
- Cobalt Strike setup & operations
- Armitage/Metasploit integration
- Sliver C2 (modern open-source alternative)
- Beacon generation & evasion
- Information stealers (Raccoon, RedLine, Lumma)

### Operational Security (OPSEC)
- C2 obfuscation techniques
- Domain fronting & CDN abuse
- DNS tunneling (dnscat2)
- Cloud-based payload hosting
- Beacon hygiene & sleep masks
- AMSI & ETW bypass
- Log tampering & clearing
- Living-off-the-Cloud tactics

### Forensic Artifacts Reference Table ⭐
**The core differentiator of this guide:**
- 20+ attack techniques mapped to Windows Event IDs
- Network indicators & behavioral anomalies
- Memory artifacts & registry modifications
- High-fidelity detection rules (7045, 4662, 1102)
- Quick lookup for SOC analysts & threat hunters

### Real-World Attack Scenarios
- C2 attack scenario with blue team detection
- Armitage/Metasploit simultaneous exploitation
- Capstone: "The Friday Afternoon Breach" (complete kill chain)

### Web Application Attacks
- SQL Injection (blind, time-based, UNION-based)
- Cross-Site Scripting (XSS)
- Command Injection
- Remote File Inclusion (RFI)
- File Upload vulnerabilities

---

## 👥 Who Should Read This?

✅ **Red Teamers** - Understand the noise you generate; plan OPSEC accordingly  
✅ **Blue Teamers** - Hunt Windows attacks; understand detection opportunities  
✅ **Security Architects** - Design detection strategies; prioritize monitoring  
✅ **Penetration Testers** - Deep technical reference for Windows exploitation  
✅ **Threat Hunters** - Map techniques to forensic artifacts & Event IDs  
✅ **SOC Analysts** - Build detections around high-fidelity indicators  
✅ **Incident Responders** - Understand attack mechanics for investigations  
✅ **Students** - Learn Windows security from fundamentals to advanced attacks  

---

## 📊 Key Features

- **210 pages** of comprehensive technical content
- **20+ major attack techniques** with detailed walkthroughs
- **8 forensic artifacts tables** mapping attacks to Event IDs
- **50+ real command examples** with actual tool syntax
- **Balanced perspective** - Every attack includes blue team detection
- **Real-world scenarios** - Not theoretical, tested in practice
- **Professional reference material** - Designed for repeated consultation

---

## 🎯 Structure

The guide follows the **complete attack lifecycle**:
1. Reconnaissance
2. Credential Extraction
3. Privilege Escalation
4. Lateral Movement
5. C2 Establishment
6. Domain Compromise
7. Persistence
8. Operational Security
9. Forensic Artifacts Reference
10. Real-World Capstone Scenario

Each section includes:
- **Technical depth** - How and why attacks work
- **Practical examples** - Real tool commands
- **Blue team perspective** - What defenders see
- **Detection opportunities** - Event IDs & behavioral indicators

---

## 📖 How to Use This Guide

**For Learning:**
- Start from the beginning if new to Windows security
- Each section builds on previous knowledge
- Use the forensic artifacts table to understand detection

**For Reference:**
- Jump to specific techniques (Table of Contents on page 3)
- Use forensic artifacts table to find technique by Event ID
- Cross-reference red team actions with blue team indicators

**For Red Teaming:**
- Execute attacks while monitoring forensic artifacts table
- Plan OPSEC based on what gets logged
- Reference capstone scenario for real-world context

**For Blue Team/Detection:**
- Start with forensic artifacts tables (pages 199-207)
- Build alerts around high-fidelity Event IDs
- Baseline normal activity for each technique

---

## 📝 License

This guide is released under **CC BY-SA 4.0** (Creative Commons Attribution-ShareAlike 4.0 International)

**You are free to:**
- ✅ Download and read
- ✅ Share with others (must attribute)
- ✅ Adapt and create derivative works (must share under same license)

**You must:**
- ✅ Attribute the original author (Ofek Deri, 2026)
- ✅ Link back to this repository

**You cannot:**
- ❌ Remove attribution
- ❌ Use for commercial purposes without permission

---

## ⚖️ Legal Disclaimer

This guide is provided for **educational and informational purposes only**. All materials presented are publicly available information. The techniques described are intended to help security professionals strengthen their defenses.

**You are responsible for ensuring you:**
- ✅ Use this material ethically
- ✅ Only test in authorized environments
- ✅ Comply with all applicable laws and regulations

Unauthorized access to computer systems is illegal.

---

## 🔗 Connect

- **GitHub:** [@ofekderi](https://github.com/ofekderi)
- **LinkedIn:** [Ofek Deri](https://www.linkedin.com/in/ofek-deri-aa176424b/)

---

## 📈 Version History

- **v1.0** (Jan 4, 2026) - Initial release with complete content, forensic artifacts table, and capstone scenario
- **v1.1** (Jan 11, 2026) - Revised "Other Open-Source Alternatives" section, minor text corrections.
---

## 🙏 Acknowledgments

Written by **Ofek Deri** as a comprehensive field guide bridging red team and blue team cybersecurity perspectives.

"The field guide I wish I had when I started." - Ofek Deri

---

**Questions or feedback?** Open an issue on GitHub or reach out on LinkedIn.
