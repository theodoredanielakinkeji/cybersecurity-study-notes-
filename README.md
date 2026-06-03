# 📚 Cybersecurity Study Notes

> Personal study notes and key takeaways from cybersecurity courses completed via
> Cisco Networking Academy and Alison Academy.
> Documenting my learning journey toward CompTIA Security+ and beyond.

---

## 🗂️ Table of Contents

1. [What is Cybersecurity?](#1-what-is-cybersecurity)
2. [Types of Threats & Attacks](#2-types-of-threats--attacks)
3. [Networking Basics](#3-networking-basics)
4. [Cyber Law & Ethics](#4-cyber-law--ethics)
5. [Security Best Practices](#5-security-best-practices)
6. [Key Terms Glossary](#6-key-terms-glossary)
7. [Certifications Roadmap](#7-certifications-roadmap)

---

## 1. What is Cybersecurity?

Cybersecurity is the practice of protecting systems, networks, and programs from digital attacks. These attacks are usually aimed at:
- Accessing, changing, or destroying sensitive information
- Extorting money from users
- Interrupting normal business operations

### The CIA Triad (Core Principles)
| Principle | Meaning |
|-----------|---------|
| **C**onfidentiality | Only authorised users can access data |
| **I**ntegrity | Data is accurate and has not been tampered with |
| **A**vailability | Systems and data are accessible when needed |

---

## 2. Types of Threats & Attacks

### 🦠 Malware
Malicious software designed to damage or gain unauthorised access to systems.
- **Virus** — attaches to files and spreads when files are shared
- **Worm** — self-replicates across networks without user action
- **Trojan** — disguises itself as legitimate software
- **Ransomware** — encrypts files and demands payment for decryption
- **Spyware** — secretly monitors user activity

### 🎣 Social Engineering
Manipulating people into revealing confidential information.
- **Phishing** — fraudulent emails impersonating trusted sources
- **Spear Phishing** — targeted phishing at specific individuals
- **Vishing** — voice/phone-based phishing
- **Pretexting** — creating a fabricated scenario to extract info

### 🔐 Password Attacks
- **Brute Force** — trying all possible password combinations
- **Dictionary Attack** — trying common words and passwords
- **Credential Stuffing** — using leaked username/password pairs

### 🌐 Network Attacks
- **Man-in-the-Middle (MitM)** — intercepting communication between two parties
- **DoS/DDoS** — overwhelming a system to make it unavailable
- **SQL Injection** — inserting malicious code into database queries
- **DNS Spoofing** — redirecting domain lookups to malicious sites

---

## 3. Networking Basics

### Key Concepts
| Term | Definition |
|------|-----------|
| **IP Address** | Unique identifier for a device on a network |
| **MAC Address** | Hardware identifier for a network interface |
| **DNS** | Translates domain names to IP addresses |
| **DHCP** | Automatically assigns IP addresses to devices |
| **Firewall** | Filters incoming and outgoing network traffic |
| **VPN** | Encrypted tunnel for secure remote connections |
| **LAN** | Local Area Network — devices connected within a building |
| **WAN** | Wide Area Network — connects multiple LANs over distance |

### OSI Model (7 Layers)
```
7. Application   → HTTP, FTP, DNS, SMTP
6. Presentation  → Encryption, Compression
5. Session       → Session management
4. Transport     → TCP, UDP
3. Network       → IP, Routing
2. Data Link     → MAC Address, Switches
1. Physical      → Cables, Hardware
```

### Common Ports to Know
| Port | Protocol | Use |
|------|----------|-----|
| 22 | SSH | Secure remote login |
| 23 | Telnet | Unsecure remote login |
| 25 | SMTP | Email sending |
| 53 | DNS | Domain name resolution |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |
| 3389 | RDP | Remote Desktop Protocol |

---

## 4. Cyber Law & Ethics

### Key Legal Concepts
- **Computer Misuse Act** — criminalises unauthorised access to computer systems
- **Data Protection Laws** — govern how personal data is collected, stored, and used (e.g. NDPR in Nigeria, GDPR in Europe)
- **Intellectual Property Law** — protects software, digital content, and innovations
- **Cybercrime Act (Nigeria)** — the Cybercrimes (Prohibition, Prevention, etc.) Act 2015

### Ethical Hacking Principles
- Always obtain **written authorisation** before testing
- Only test within the **agreed scope**
- **Report all findings** to the organisation honestly
- Never access systems beyond what is permitted
- Protect the **confidentiality** of findings

---

## 5. Security Best Practices

### For Individuals
- ✅ Use strong, unique passwords for every account
- ✅ Enable Multi-Factor Authentication (MFA)
- ✅ Keep software and OS updated
- ✅ Be cautious of unexpected emails and links
- ✅ Back up important data regularly
- ✅ Use a VPN on public Wi-Fi

### For Organisations
- ✅ Implement least privilege access control
- ✅ Conduct regular security awareness training
- ✅ Maintain an incident response plan
- ✅ Perform regular vulnerability assessments
- ✅ Monitor network traffic with IDS/IPS tools
- ✅ Encrypt sensitive data at rest and in transit

---

## 6. Key Terms Glossary

| Term | Definition |
|------|-----------|
| **Vulnerability** | A weakness in a system that can be exploited |
| **Exploit** | Code or technique used to take advantage of a vulnerability |
| **Threat Actor** | Person or group responsible for a cyberattack |
| **Zero-Day** | A vulnerability unknown to the vendor with no patch available |
| **Patch** | Software update that fixes a security vulnerability |
| **SOC** | Security Operations Centre — team monitoring for threats |
| **SIEM** | Security Information and Event Management system |
| **IOC** | Indicator of Compromise — evidence a breach has occurred |
| **Penetration Testing** | Authorised simulated attack to find vulnerabilities |
| **Encryption** | Converting data into unreadable format without a key |
| **Authentication** | Verifying the identity of a user or system |
| **Authorisation** | Granting permissions to an authenticated user |

---

## 7. Certifications Roadmap

```
CURRENT LEVEL
     │
     ├── ✅ Cisco: Introduction to Cybersecurity
     ├── ✅ Cisco: Networking Basics
     ├── ✅ Alison: Cyber Law, Awareness, Threat Prevention
     │
NEXT STEPS
     │
     ├── 🔄 Cisco: Ethical Hacking
     ├── 🔄 CompTIA A+ Core 1 (220-1201)
     ├── ⏳ CompTIA A+ Core 2 (220-1202)
     ├── ⏳ CompTIA Network+ (N10-009)
     └── ⏳ CompTIA Security+ (SY0-701) ← 🎯 Primary Goal
```

---

*Notes compiled by: Daniel Theodore Akinkeji*
*Sources: Cisco Networking Academy, Alison Academy*
