# 🛡️ World-Class Security Mastery Roadmap

> From zero to quantum security pioneer — every topic, resource, what it teaches, and how it builds toward mastery.

**8 Phases · 0–8+ Years · Classical + Cloud + AI + Quantum · 41 Topics · 140+ Resources**

---

## Table of Contents

- [Phase 0 — Mindset & Learning System](#phase-0--mindset--learning-system)
- [Phase 1 — Core Technical Foundations](#phase-1--core-technical-foundations)
- [Phase 2 — Offensive Security — Red Team](#phase-2--offensive-security--red-team)
- [Phase 3 — Defensive Security — Blue Team](#phase-3--defensive-security--blue-team)
- [Phase 4 — Cloud Security Mastery](#phase-4--cloud-security-mastery)
- [Phase 5 — AI Security Mastery](#phase-5--ai-security-mastery)
- [Phase 6 — Advanced Specialisations & CISSP](#phase-6--advanced-specialisations--cissp)
- [Phase 7 — Quantum Security — The Frontier](#phase-7--quantum-security--the-frontier)
- [Phase 8 — Emerging Tech & World-Class Status](#phase-8--emerging-tech--world-class-status)

---

## Phase 0 — Mindset & Learning System

**Timeline:** Month 0–1 · **Category:** Foundation · **Topics:** 3

> Build the foundation before touching any technical content. The learning system you build in month 1 determines how fast you grow in every phase after.

> ℹ️ **Note:** This phase is not optional. Security professionals who skip this spend twice as long learning half as much. Build your system first.

### Learning Infrastructure

---

#### 1. Growth Mindset & Learning Science

| | |
|---|---|
| **Difficulty** | ⭐ Beginner |
| **Time** | Week 1 |
| **Salary** | N/A — foundational habit |
| **Tools** | `Anki` · `Obsidian` · `Notion` |

Understand how memory and skill acquisition actually work. Apply spaced repetition, active recall, the Feynman technique, and interleaved practice from day one.

**What you will be able to do:**
- Build a daily learning habit (minimum 1 hour)
- Set up Anki for spaced repetition
- Use Obsidian to link ideas and build a second brain
- Apply Feynman technique: teach what you learn to test understanding

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Anki spaced repetition app](https://apps.ankiweb.net) | Free flashcard app based on the SM-2 spaced repetition algorithm. How to retain commands, port numbers, CVE patterns, protocol details, and cert exam content without forgetting. Use it for every technical fact you want to keep — ports, cipher suites, ATT&CK technique IDs. |
| 🆓 FREE | [Obsidian — knowledge management](https://obsidian.md) | A free local-first note app that links ideas like a wiki. How to build a personal knowledge base that grows with your career. Link attack techniques to defences, protocols to their vulnerabilities, tools to their use cases. |
| 🆓 FREE | [Make It Stick — learning science summary](https://www.retrievalpractice.org/make-it-stick) | Summary of the book on the science of learning. Why re-reading and highlighting fail. Why testing yourself, spacing practice, and interleaving topics works. Apply this to every cert study session. |
| 🆓 FREE | [Ali Abdaal — active recall study method (YouTube)](https://www.youtube.com/watch?v=ukLnPbIffxE) | Evidence-based study technique explanation. How to study smarter — closing the book and recalling from memory, using past papers, spaced repetition scheduling. Critical for Security+, OSCP, CISSP prep. |

---

#### 2. Touch Typing & Terminal Fluency

| | |
|---|---|
| **Difficulty** | ⭐ Beginner |
| **Time** | Week 1–4 |
| **Salary** | N/A — foundational speed |
| **Tools** | `bash` · `vim` · `tmux` · `zsh` |

You will live in terminals for your entire career. Slow typing breaks your flow and costs hours every week. 60+ WPM minimum. Learn bash, vim basics, tmux.

**What you will be able to do:**
- Reach 60+ WPM touch typing speed
- Navigate Linux filesystem blindly
- Use vim for basic file editing on any server
- Use tmux for multi-pane terminal sessions

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Keybr.com — adaptive typing trainer](https://www.keybr.com) | Adaptive touch typing trainer that focuses on your weakest keys. 20 minutes per day for 4–6 weeks gets most people to 60 WPM. This speed difference is enormous over a career — 30 WPM vs 80 WPM means you do twice as much in the same time. |
| 🆓 FREE | [OverTheWire: Bandit (25 levels)](https://overthewire.org/wargames/bandit/) | A beginner-friendly Linux wargame accessed entirely via SSH. Real Linux command usage — file navigation, permissions, pipes, grep, base64, netcat, git, SSH keys — by solving actual puzzles. |
| 🆓 FREE | [Vim Adventures — learn vim by playing](https://vim-adventures.com) | A browser game that teaches vim through gameplay. Vim movement (hjkl), editing commands (ci", dd, yy), and navigation. Every Linux server on earth has vim. |
| 🆓 FREE | [tmux cheatsheet & guide](https://tmuxcheatsheet.com) | Reference for the terminal multiplexer tmux. How to split your terminal into panes, create windows, and keep sessions alive even when you disconnect. |

---

#### 3. Technical English & Documentation Reading

| | |
|---|---|
| **Difficulty** | ⭐ Beginner |
| **Time** | Ongoing |
| **Salary** | N/A — foundational communication |
| **Opens roles** | Technical writer (bonus) |
| **Tools** | `RFC Editor` · `Google Scholar` · `ArXiv` |

Every RFC, CVE, security advisory, research paper, and top resource is in English. Your reading speed and comprehension directly cap your learning speed.

**What you will be able to do:**
- Read and understand RFCs and technical specifications
- Follow security advisories and CVE descriptions
- Read academic security papers
- Write clear incident reports and documentation

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [RFC 793 — TCP specification](https://www.rfc-editor.org/rfc/rfc793) | The original TCP protocol specification from 1981. How to read dry technical specifications — the skill that lets you understand any protocol, standard, or specification your career requires. |
| 🆓 FREE | [CVE Details — vulnerability database](https://www.cvedetails.com) | Structured database of public CVEs with CVSS scores, affected versions, and links to advisories. How to read and interpret vulnerability disclosures — CVSS vector strings, affected components, exploit availability. |

---

## Phase 1 — Core Technical Foundations

**Timeline:** Months 1–8 · **Category:** Classical · **Topics:** 6

> The non-negotiable foundation. Everything in phases 2–8 builds on this. Do not rush or skip. Complete Security+ before moving on.

> ℹ️ **Note:** Target: Security+ certified by month 6–8. Everything else in this phase feeds into that exam and into real job readiness.

### Networking & Operating Systems

---

#### 4. Networking Fundamentals

| | |
|---|---|
| **Difficulty** | ⭐ Beginner |
| **Time** | 2–3 months |
| **Salary** | PKR 80–150k/mo (entry networking) |
| **Opens roles** | Network technician · Junior SOC analyst · Help desk |
| **Tools** | `Wireshark` · `Nmap` · `Cisco Packet Tracer` · `GNS3` |

OSI model (all 7 layers), TCP/IP stack, subnetting and CIDR notation, DNS resolution, DHCP, ARP, routing protocols (BGP, OSPF), VLANs, NAT, firewall concepts, packet analysis. You cannot secure what you do not understand.

**What you will be able to do:**
- Subnet any IP range mentally
- Read and interpret Wireshark packet captures
- Explain how DNS works from query to response
- Understand TCP 3-way handshake and why it matters for security
- Configure basic firewall rules
- Understand VLANs and why they matter for network segmentation

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Professor Messer Network+ (N10-008) — full free course](https://www.professormesser.com/network-plus/n10-008/n10-008-video/n10-008-training-course/) | Complete free Network+ video course. Every networking concept needed for security — subnetting with practice problems, all routing protocols, wireless standards, network troubleshooting methodology. |
| 🆓 FREE | [TryHackMe — Pre-Security path](https://tryhackme.com/path/outline/presecurity) | Guided hands-on learning path for absolute beginners. Networking basics, Linux fundamentals, web fundamentals — all with real virtual machines in your browser. |
| 🆓 FREE | [Cisco Networking Academy — CCNAv7: Introduction to Networks](https://www.netacad.com/courses/networking/ccna-introduction-networks) | Free official Cisco networking course with labs in Packet Tracer. Network models, Ethernet, IP addressing, routing fundamentals, transport layer protocols. |
| 🆓 FREE | [Wireshark University — free training](https://www.wiresharktraining.com/free/) | Free Wireshark training from Laura Chappell. How to capture and analyse network traffic, identify protocol anomalies, find evidence of attacks in packet captures. |
| 🎓 CERT | [CompTIA Network+](https://www.comptia.org/certifications/network) | Vendor-neutral networking certification. Exam fee ~$350. Opens entry IT/networking jobs. Highly valuable for building solid foundations. |

---

#### 5. Linux Administration

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 2–3 months |
| **Salary** | PKR 90–160k/mo (Linux sysadmin) |
| **Opens roles** | Linux administrator · Junior DevOps · SOC analyst |
| **Tools** | `bash` · `vim` · `ssh` · `grep` · `awk` · `sed` · `systemd` |

File system hierarchy, users and groups, permissions (chmod/chown/ACLs), processes and signals, systemd/cron, bash scripting, package management (apt/yum), SSH configuration, log files (/var/log/), basic networking commands. Every server, cloud instance, and container runs Linux.

**What you will be able to do:**
- Navigate and manage the Linux filesystem without GUI
- Write bash scripts to automate repetitive tasks
- Configure SSH securely (key auth, disable password auth, change port)
- Read and parse system logs to identify issues
- Manage users, groups, and file permissions correctly
- Use cron for scheduled tasks
- Compile software from source

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [The Linux Command Line — free book by William Shotts](https://linuxcommand.org/tlcl.php) | The definitive 540-page guide to bash and the Linux command line — free PDF. Everything from basic file operations to advanced shell scripting, pipelines, regular expressions, and process management. |
| 🆓 FREE | [Linux Journey — interactive lessons](https://linuxjourney.com) | Free interactive website teaching Linux from absolute zero with quizzes. Grasshopper → Journeyman → Networking Nomad tracks. |
| 🆓 FREE | [OverTheWire: Bandit (levels 0–33)](https://overthewire.org/wargames/bandit/) | Linux skills wargame — 34 levels of SSH challenges. Each level teaches a specific command or concept. |
| 🆓 FREE | [TryHackMe — Linux Fundamentals 1, 2, 3](https://tryhackme.com/module/linux-fundamentals) | Three-part guided Linux course with embedded VMs. Filesystem navigation, text editors, permissions, processes, network commands, automation. |
| 💰 PAID | [Linux Bible — Christopher Negus (book)](https://www.wiley.com/en-us/Linux+Bible%2C+10th+Edition-p-9781119578888) | The most comprehensive Linux administration book. 1000+ pages. Use as a reference throughout your career. |

---

#### 6. Windows & Active Directory

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 2 months |
| **Salary** | PKR 100–180k/mo (Windows admin) |
| **Opens roles** | Windows administrator · Junior pen-tester · SOC analyst L1 |
| **Tools** | `PowerShell` · `Active Directory Users and Computers` · `Group Policy Management` · `Event Viewer` |

Active Directory Domain Services, organisational units, Group Policy Objects, Kerberos authentication, NTLM, PowerShell scripting, registry, Windows event logs, LDAP queries, SYSVOL. 90% of enterprise environments run Windows.

**What you will be able to do:**
- Set up and manage a basic Active Directory domain
- Write PowerShell scripts for automation and security tasks
- Read and query Windows Event Logs for security events
- Understand Kerberos ticket flow and why it matters for attacks
- Query AD with LDAP and tools like BloodHound
- Configure and apply Group Policy Objects

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [TryHackMe — Active Directory Basics](https://tryhackme.com/room/winadbasics) | Guided room explaining Active Directory from scratch. What AD is, how users/groups/OUs/GPOs work, forest and domain trusts, Kerberos basics. |
| 🆓 FREE | [Microsoft Learn — Active Directory Domain Services](https://learn.microsoft.com/en-us/training/paths/active-directory-domain-services/) | Official free Microsoft training on AD DS. How to install, configure, and manage Active Directory. |
| 🆓 FREE | [Microsoft Learn — PowerShell fundamentals](https://learn.microsoft.com/en-us/training/paths/powershell/) | Official Microsoft PowerShell course — free. PowerShell syntax, cmdlets, pipeline, modules, remoting, Active Directory queries. |
| 💰 PAID | [TCM Security — Practical Ethical Hacking course](https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course) | The best affordable comprehensive ethical hacking course (~$30). Active Directory attacks from scratch — LLMNR poisoning, BloodHound, Kerberoasting, Pass-the-Hash, Golden Tickets. |

### Security Foundations & First Certification

---

#### 7. Cryptography Fundamentals

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 6–8 weeks |
| **Salary** | Prerequisite — no direct salary |
| **Opens roles** | Security engineer · Cryptography analyst · PKI administrator |
| **Tools** | `OpenSSL` · `GnuPG` · `CyberChef` |

Symmetric encryption (AES-128/256), asymmetric encryption (RSA, ECC, Diffie-Hellman), hashing (MD5 weakness, SHA-256, bcrypt/Argon2), MAC and HMAC, digital signatures, PKI (CAs, CSRs, certificates), TLS/SSL handshake, certificate transparency. Cryptography is the foundation of all security.

**What you will be able to do:**
- Explain AES-256 CBC vs GCM and when to use each
- Understand why RSA works and what breaks it (factoring)
- Implement TLS certificate chain validation
- Generate and verify digital signatures
- Explain why MD5 is broken and what replaces it
- Understand key exchange protocols (ECDHE, etc.)

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Crypto101 — free 247-page book](https://crypto101.io) | A complete cryptography textbook — free PDF. From XOR ciphers to RSA, built from first principles with no mathematics degree required. |
| 🆓 FREE | [CryptoHack — interactive challenges](https://cryptohack.org) | Learn cryptography by breaking it — 200+ interactive challenges. ECB penguin attack, RSA padding, hash length extension, CBC padding oracle, ECDSA nonce reuse. |
| 🆓 FREE | [Khan Academy — Cryptography course](https://www.khanacademy.org/computing/computer-science/cryptography) | Free video course on cryptography with exercises. Caesar cipher → frequency analysis → Vigenère → RSA. |
| 💰 PAID | [Serious Cryptography — Jean-Philippe Aumasson](https://nostarch.com/seriouscrypto) | The professional cryptography reference. AES internals, public-key cryptography, hash functions, TLS deep dive, authenticated encryption, post-quantum overview. |

---

#### 8. CompTIA Security+ (SY0-701)

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 3–4 months study + exam |
| **Salary** | PKR 120–220k/mo after cert |
| **Opens roles** | SOC analyst L1 · IT security specialist · Junior pen-tester · Help desk security |
| **Tools** | `Anki (for exam prep)` · `ExamCompass` |

Your first major certification. 7 domains: threats/attacks/vulnerabilities, architecture, implementation, identity management, network security, operations and IR, governance/risk/compliance. Required by US DoD for all government IT workers.

**What you will be able to do:**
- Understand all major attack types and mitigations
- Explain PKI, cryptography, and certificate management
- Describe identity federation, SSO, MFA implementations
- Know incident response phases and procedures
- Understand risk management frameworks and compliance
- Pass the exam (90 questions, 90 minutes, 750/900 required)

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Professor Messer — SY0-701 full free course](https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-training-course/) | Complete free Security+ course — 170+ videos. Every exam domain systematically. Short 5–15 minute videos. |
| 🆓 FREE | [ExamCompass — free practice tests by domain](https://www.examcompass.com/comptia-security-plus-practice-test) | Free Security+ practice questions organised by exam domain. Identify weak domains, practice speed under exam conditions. |
| 💰 PAID | [Mike Chapple & David Seidl — Security+ Study Guide 9th Ed](https://www.wiley.com/en-us/CompTIA+Security%2B+Study+Guide%2C+9th+Edition-p-9781119736622) | The most popular Security+ textbook (~$45). Deep explanations of every concept with 1000+ practice questions. |
| 🎓 CERT | [CompTIA Security+ SY0-701 exam](https://www.comptia.org/certifications/security) | Globally recognised baseline security certification. Exam fee ~$380. Required by US DoD 8570. Valid for 3 years. |

---

#### 9. Python for Security

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 2–3 months |
| **Salary** | Adds 20–40% to any security salary |
| **Opens roles** | Security engineer · Automation engineer · Threat analyst |
| **Tools** | `Python 3` · `requests` · `scapy` · `pwntools` · `paramiko` |

Python scripting, file I/O, socket programming, the requests library for HTTP, subprocess for running tools, regex for log parsing, JSON handling, argparse for CLI tools. Write your own security tools. Automate repetitive tasks.

**What you will be able to do:**
- Write a port scanner from scratch using sockets
- Parse and analyse log files with regex and pandas
- Make authenticated API calls and parse JSON responses
- Build a simple web scraper for OSINT
- Automate repetitive security tasks
- Understand how Metasploit modules are structured

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Automate the Boring Stuff with Python — free online book](https://automatetheboringstuff.com) | Free Python book focused on practical automation — the most read Python book in the world. Files and folders, regex, web scraping, working with spreadsheets and PDFs, scheduling tasks. |
| 🆓 FREE | [TCM Security — Python for Hackers (YouTube, free)](https://www.youtube.com/watch?v=egg-GoT5iVk) | Free 6-hour Python security scripting course. Build a port scanner, SSH brute-forcer, directory scanner, password cracker — each explained line by line. |
| 💰 PAID | [Black Hat Python 2nd Edition — No Starch Press](https://nostarch.com/black-hat-python2E) | The definitive Python security programming book (~$40). Network sniffers, raw socket programming, trojans, keyloggers, process injection, sandbox detection. |

---

## Phase 2 — Offensive Security — Red Team

**Timeline:** Year 1–2 · **Category:** Offensive · **Topics:** 4

> Learn to think and act like an attacker. Understand every exploitation technique at a deep technical level before specialising in defence or architecture.

> ⚠️ **Important:** Always practice in legal environments only — your own lab, TryHackMe, HackTheBox, or with explicit written permission. Unauthorised access is a criminal offence in every country.

### Web Application Security

---

#### 10. Web Application Security (OWASP Top 10)

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 3–4 months |
| **Salary** | PKR 200–400k/mo (AppSec engineer) |
| **Opens roles** | AppSec engineer · Web pen-tester · Bug bounty hunter · SOC L2 |
| **Tools** | `Burp Suite` · `OWASP ZAP` · `sqlmap` · `ffuf` · `Nikto` · `DVWA` · `WebGoat` |

SQL injection, Cross-Site Scripting (reflected, stored, DOM), CSRF, IDOR, SSRF, XXE, insecure deserialization, broken authentication, security misconfiguration, CORS issues. Burp Suite Professional mastery.

**What you will be able to do:**
- Exploit all 10 OWASP vulnerability classes in a lab
- Use Burp Suite Repeater to manually test endpoints
- Write a working SQL injection payload for UNION-based extraction
- Bypass CSRF protections
- Find and exploit IDOR vulnerabilities
- Identify and exploit SSRF to reach internal services

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [PortSwigger Web Security Academy](https://portswigger.net/web-security) | The best free web security course in the world — 200+ guided labs, 100% free. Every vulnerability class with theory then immediate exploitation. Do ALL labs. |
| 🆓 FREE | [OWASP Top 10 official documentation](https://owasp.org/www-project-top-ten/) | The authoritative list of the 10 most critical web security risks. Attack scenarios, real-world impact, prevention for each vulnerability. |
| 🆓 FREE | [DVWA — Damn Vulnerable Web Application](https://dvwa.co.uk) | A PHP/MySQL web application deliberately made insecure. Practice each attack at Low/Medium/High difficulty. Source code is visible. |
| 🎓 CERT | [Burp Suite Certified Practitioner (BSCP)](https://portswigger.net/web-security/certification) | Premium web application security certification. 4-hour practical exam on real applications. |

### Network Penetration Testing

---

#### 11. Network Penetration Testing Methodology

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 4–6 months |
| **Salary** | PKR 250–500k/mo (pen-tester) |
| **Opens roles** | Penetration tester · Red team analyst · Vulnerability assessor · Security consultant |
| **Tools** | `Nmap` · `Metasploit` · `Mimikatz` · `BloodHound` · `Impacket` · `CrackMapExec` · `Cobalt Strike` |

Full pen-test lifecycle: pre-engagement, reconnaissance, enumeration, vulnerability analysis, exploitation, post-exploitation, lateral movement, reporting. PTES and OSSTMM methodologies.

**What you will be able to do:**
- Complete a full internal network pen-test from initial access to domain admin
- Write a professional pen-test report with CVSS scores and remediation steps
- Use Metasploit modules and understand what they do at the packet level
- Perform OSINT reconnaissance without touching the target
- Enumerate SMB, LDAP, DNS, RPC services
- Establish persistence and lateral movement

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [TryHackMe — Jr Penetration Tester path](https://tryhackme.com/path/outline/jrpenetrationtester) | Structured guided path from beginner to junior pen-tester. Full methodology — recon, scanning, exploitation, post-exploitation, web attacks, reporting. |
| 💰 PAID | [TCM Security — Practical Ethical Hacking](https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course) | Best affordable pen-test course (~$30). Complete methodology with a built lab. AD attacks, web attacks, wireless attacks, report writing. |
| 💰 PAID | [HackTheBox Academy — Penetration Tester path](https://academy.hackthebox.com/path/preview/penetration-tester) | Deep technical pen-test curriculum (~$14/month). Higher technical depth than TCM. |
| 🎓 CERT | [OSCP — Offensive Security Certified Professional](https://www.offsec.com/courses/pen-200/) | The gold standard penetration testing certification. 24-hour practical exam on real machines — no multiple choice. Required for senior pen-test and red team roles. |

---

#### 12. Active Directory Attacks

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 2–3 months |
| **Salary** | PKR 300–600k/mo (red team specialist) |
| **Opens roles** | Red team operator · AD security specialist · Senior pen-tester |
| **Tools** | `BloodHound` · `Mimikatz` · `Impacket` · `Rubeus` · `CrackMapExec` · `PowerView` |

LLMNR/NBT-NS poisoning, SMB relay attacks, BloodHound attack path analysis, Kerberoasting, AS-REP roasting, Pass-the-Hash, Pass-the-Ticket, Overpass-the-Hash, Golden Ticket, Silver Ticket, DCSync, domain trust abuse.

**What you will be able to do:**
- Map complete AD attack path from low-privilege user to Domain Admin
- Perform and detect Kerberoasting at the packet level
- Extract NTDS.dit and crack hashes offline
- Create and use a Golden Ticket for persistence
- Enumerate AD with BloodHound and identify shortest attack paths
- Abuse domain trusts to pivot between domains

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [BloodHound — free AD attack path tool](https://github.com/BloodHoundAD/BloodHound) | Graph-based AD attack path finder. Run SharpHound collector, load data, query shortest paths to Domain Admin, identify Kerberoastable accounts. |
| 🆓 FREE | [TryHackMe — Attacking Kerberos room](https://tryhackme.com/room/attackingkerberos) | Guided room on Kerberos attacks. Kerberoasting, AS-REP roasting, Pass-the-Ticket, Golden/Silver Ticket creation at the protocol level. |
| 💰 PAID | [TCM Security — Practical AD Attacks course](https://academy.tcm-sec.com/p/practical-active-directory-pentesting) | Dedicated AD attack course with its own lab environment. Every AD attack vector methodically. |

---

#### 13. Buffer Overflows & Exploit Development

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 2–3 months |
| **Salary** | Significant premium for exploit dev skills |
| **Opens roles** | Exploit developer · Vulnerability researcher · Red team operator |
| **Tools** | `Immunity Debugger` · `x64dbg` · `Mona.py` · `msfvenom` · `pwntools` · `GDB-peda` |

Stack-based buffer overflows, finding the offset, controlling EIP, bad character identification, shellcode generation, SEH-based overflows, x86 assembly reading. Required for OSCP and senior red team.

**What you will be able to do:**
- Write a working buffer overflow exploit for a custom vulnerable application
- Find buffer overflow offsets using cyclic patterns
- Generate custom shellcode with msfvenom
- Identify bad characters that break shellcode
- Understand x86 assembly enough to read disassembly
- Handle SEH-based overflows

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [TryHackMe — Buffer Overflow Prep room](https://tryhackme.com/room/bufferoverflowprep) | Step-by-step buffer overflow methodology for OSCP — 10 practice targets. Exact OSCP methodology. |
| 🆓 FREE | [TCM Security — Buffer Overflows Made Easy (YouTube)](https://www.youtube.com/watch?v=qSnPayW6VMQ) | Free 2-hour buffer overflow tutorial. Complete walkthrough of a Windows 32-bit buffer overflow from scratch. |
| 🆓 FREE | [Exploit.education — Protostar challenges](https://exploit.education/protostar/) | Progressive binary exploitation challenges — Stack0 through Stack7, format strings, heap. |

---

#### 14. Malware Analysis & Reverse Engineering

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 3–4 months |
| **Salary** | PKR 300–600k/mo (malware analyst) |
| **Opens roles** | Malware analyst · Threat intelligence analyst · Incident responder · AV/EDR researcher |
| **Tools** | `Ghidra` · `x64dbg` · `ANY.RUN` · `VirusTotal` · `YARA` · `PE Studio` · `Cutter` |

Static analysis, dynamic analysis, sandbox analysis, x86 assembly reading, Ghidra decompiler, YARA rule writing, malware family identification.

**What you will be able to do:**
- Perform full static analysis of a PE executable
- Identify malware families by their behavioural signatures
- Write YARA rules to detect specific malware samples
- Use Ghidra to decompile and understand unknown binaries
- Sandbox an unknown file safely and interpret results
- Understand common persistence mechanisms

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Malware Unicorn — free analysis workshops](https://malwareunicorn.org/workshops.html) | Hands-on malware analysis workshops. RE101 (intro to RE with real samples), PE101 (PE format deep dive). |
| 🆓 FREE | [Ghidra — NSA open-source RE tool](https://ghidra-sre.org) | Professional-grade reverse engineering suite from the NSA — free. Disassembly, decompilation, cross-references, scripting. |
| 🆓 FREE | [ANY.RUN — interactive online sandbox](https://any.run) | Cloud sandbox where you watch malware execute live in a VM — free tier available. |
| 💰 PAID | [Practical Malware Analysis — Sikorski & Honig](https://nostarch.com/malware) | The definitive malware analysis textbook — 800 pages, 20 chapters. Lab exercises with real malware. |
| 🎓 CERT | [GREM — GIAC Reverse Engineering Malware](https://www.giac.org/certifications/reverse-engineering-malware-grem/) | The top malware analysis certification. Required by government agencies and financial institutions. |

---

## Phase 3 — Defensive Security — Blue Team

**Timeline:** Year 1–3 · **Category:** Defensive · **Topics:** 4

> Learn to detect, investigate, and respond to the attacks you learned in Phase 2. Do this concurrently with Phase 2 — the best security engineers understand both sides.

### SOC Operations & Detection

---

#### 15. SIEM & Log Analysis

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 3–4 months |
| **Salary** | PKR 150–300k/mo (SOC analyst L2) |
| **Opens roles** | SOC analyst L1/L2 · Threat hunter · SIEM engineer · Detection engineer |
| **Tools** | `Splunk` · `Elastic/ELK Stack` · `Microsoft Sentinel` · `Sysmon` · `Graylog` · `QRadar` |

Splunk SPL queries, Elastic Stack (ELK) with Kibana, Microsoft Sentinel KQL, log ingestion and parsing, correlation rules, alert tuning, dashboard building, threat hunting workflows.

**What you will be able to do:**
- Write Splunk SPL queries to hunt for specific attack patterns
- Build correlation rules that detect multi-stage attacks
- Tune alerts to reduce false positives below 10%
- Create dashboards for SOC metrics and incident tracking
- Identify attacker TTPs from log data alone
- Configure Sysmon for high-fidelity Windows logging

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Splunk Free Training — Splunk Fundamentals 1](https://www.splunk.com/en_us/training/free-courses.html) | Official free Splunk course. Search language (SPL), reports and dashboards, alerts, lookups. |
| 🆓 FREE | [TryHackMe — SOC Level 1 path](https://tryhackme.com/path/outline/soclevel1) | Complete junior SOC analyst curriculum. Pyramid of Pain, Cyber Kill Chain, phishing analysis, Splunk, network log analysis. |
| 🆓 FREE | [Microsoft Sentinel Ninja training (L100–L400)](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/become-a-microsoft-sentinel-ninja-the-complete-level-400/ba-p/1246310) | Free multi-level Sentinel training. Deployment, KQL query writing, detection rules, workbooks, SOAR playbooks. |
| 🎓 CERT | [Splunk Core Certified User](https://www.splunk.com/en_us/training/certification-track/splunk-core-certified-user.html) | Entry-level Splunk certification. Quick and affordable. First cert for SOC roles. |

---

#### 16. Digital Forensics & Incident Response

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 3–4 months |
| **Salary** | PKR 200–400k/mo (IR analyst) |
| **Opens roles** | Incident responder · Digital forensic analyst · DFIR consultant · Threat hunter |
| **Tools** | `Volatility3` · `FTK Imager` · `Autopsy` · `KAPE` · `Velociraptor` · `TheHive` |

Incident response lifecycle, evidence collection and preservation, disk imaging, memory forensics, timeline analysis, network forensics, chain of custody, IR report writing.

**What you will be able to do:**
- Acquire a forensically sound disk image
- Extract running processes and network connections from a memory dump
- Build a timeline of attacker activity from multiple log sources
- Write a clear IR report with root cause analysis
- Perform malware triage during an active incident
- Understand evidence handling and chain of custody

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Volatility Foundation — memory forensics framework](https://volatilityfoundation.org) | Industry-standard open-source memory forensics tool. Extract processes, network connections, registry hives, injected code from RAM dumps. |
| 🆓 FREE | [Blue Team Labs Online — free DFIR challenges](https://blueteamlabs.online) | Free gamified blue-team challenges with real forensic evidence files. |
| 🆓 FREE | [SANS DFIR blog and free posters](https://www.sans.org/blog/digital-forensics-and-incident-response/) | Free resources from the top DFIR training provider. Methodology, evidence acquisition, Windows forensics artefacts. |
| 🎓 CERT | [BTL1 — Blue Team Level 1](https://www.securityblue.team/why-btl1) | A practical 24-hour incident response certification. |

### Threat Intelligence & GRC

---

#### 17. Threat Intelligence & MITRE ATT&CK

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 200–380k/mo (threat analyst) |
| **Opens roles** | Threat intelligence analyst · Detection engineer · SOC L2/L3 · CISO advisor |
| **Tools** | `MITRE ATT&CK Navigator` · `MISP` · `OpenCTI` · `YARA` · `Sigma` · `VirusTotal` |

MITRE ATT&CK framework, threat actor profiling, IOC/IOA hunting, YARA rules, Sigma rules, intelligence lifecycle, threat feeds, diamond model, kill chain analysis.

**What you will be able to do:**
- Map any attack to MITRE ATT&CK techniques
- Write YARA rules to detect specific malware families
- Write Sigma rules that convert to multiple SIEM platforms
- Profile a threat actor from public reporting
- Build a threat intelligence feed for your organisation
- Use ATT&CK Navigator to build detection coverage heatmaps

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [MITRE ATT&CK framework](https://attack.mitre.org) | Complete encyclopedia of adversary tactics and techniques — free. 14 tactics, 200+ techniques mapped to real threat actors. |
| 🆓 FREE | [Sigma rules GitHub project](https://github.com/SigmaHQ/sigma) | Generic detection rule format that converts to Splunk, Elastic, Sentinel, QRadar, and 20+ other SIEMs. |
| 💰 PAID | [Applied Network Security Monitoring — Bejtlich](https://www.elsevier.com/books/applied-network-security-monitoring/bejtlich/978-0-12-417208-1) | The Network Security Monitoring bible. How to build detection infrastructure from scratch. |

---

#### 18. GRC — Governance, Risk & Compliance

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 2–3 months |
| **Salary** | PKR 150–350k/mo (GRC analyst) |
| **Opens roles** | GRC analyst · Compliance manager · Risk analyst · IT auditor · vCISO |
| **Tools** | `NIST CSF` · `ISO 27001` · `OpenRMF` · `ServiceNow GRC` |

ISO 27001:2022, NIST CSF 2.0, NIST SP 800-53, PCI-DSS v4.0, GDPR, HIPAA, SOC 2 Type II. Risk registers, FAIR model, audit methodology, BCP/DR planning, security policy writing.

**What you will be able to do:**
- Conduct a gap analysis against ISO 27001
- Build and maintain a risk register with CVSS and business impact
- Write information security policies that meet compliance requirements
- Understand what a SOC 2 Type II audit involves
- Implement NIST CSF across an organisation
- Understand GDPR data protection obligations

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) | The most widely used security framework globally — free. 6 functions with implementation tiers and profiles. |
| 🆓 FREE | [ISO 27001 implementation guide](https://www.itgovernance.co.uk/iso27001) | Free practical guide. The 93 Annex A controls, gap analysis methodology, audit preparation. |
| 🎓 CERT | [CISA — Certified Information Systems Auditor](https://www.isaca.org/credentialing/cisa) | The premier IS audit certification from ISACA. Required at many banks, healthcare, and consulting firms. |

---

## Phase 4 — Cloud Security Mastery

**Timeline:** Year 2–4 · **Category:** Cloud · **Topics:** 4

> The highest volume of security jobs today are cloud security roles. Cloud misconfiguration is the #1 cause of data breaches.

### Cloud Foundations to Security Specialist

---

#### 19. Cloud Architecture & Shared Responsibility

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 1–2 months |
| **Salary** | PKR 120–200k/mo (cloud foundations) |
| **Opens roles** | Cloud support engineer · Junior cloud architect |
| **Tools** | `AWS Console` · `Azure Portal` · `GCP Console` · `Terraform` |

IaaS/PaaS/SaaS service models, shared responsibility matrix, multi-cloud concepts, cloud-native vs lift-and-shift architecture, availability zones, regions, edge locations.

**What you will be able to do:**
- Explain exactly what the customer vs cloud provider is responsible for in each service model
- Design multi-AZ architectures for high availability
- Identify security implications of different cloud service models
- Understand cloud cost management and billing anomaly detection

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [AWS Cloud Practitioner Essentials (free)](https://explore.skillbuilder.aws/learn/course/external/view/elearning/134/aws-cloud-practitioner-essentials) | Official free AWS foundations course — 6 hours. AWS global infrastructure, core services, shared responsibility model. |
| 🎓 CERT | [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) | Entry-level AWS certification. Exam fee ~$100. |

---

#### 20. Cloud IAM & Zero Trust Architecture

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 200–380k/mo (IAM architect) |
| **Opens roles** | IAM engineer · Cloud security engineer · Zero trust architect |
| **Tools** | `AWS IAM Access Analyzer` · `AWS Config` · `Entra ID` · `HashiCorp Vault` |

AWS IAM policies, Entra ID, managed identities, service accounts, OAuth 2.0 / OIDC / SAML federation, MFA enforcement, Zero Trust Architecture (NIST SP 800-207).

**What you will be able to do:**
- Write least-privilege IAM policies from scratch
- Implement service-to-service authentication without long-lived keys
- Federate identity with SAML/OIDC to a third-party IdP
- Design a Zero Trust network architecture
- Audit existing IAM configurations for over-permission
- Implement MFA enforcement across an organisation

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [AWS IAM Workshop — hands-on labs](https://catalog.workshops.aws/general-immersionday/en-US/foundational/iam) | Official AWS IAM hands-on workshop — free. Writing/testing policies, IAM Access Analyzer. |
| 🆓 FREE | [NIST SP 800-207 — Zero Trust Architecture](https://csrc.nist.gov/publications/detail/sp/800-207/final) | The definitive Zero Trust Architecture specification from NIST. Seven tenets of ZTA, deployment models. |

---

#### 21. DevSecOps & CI/CD Pipeline Security

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 3–4 months |
| **Salary** | PKR 280–500k/mo (DevSecOps engineer) |
| **Opens roles** | DevSecOps engineer · Platform security engineer · AppSec engineer |
| **Tools** | `Semgrep` · `Trivy` · `Gitleaks` · `Checkov` · `Snyk` · `GitHub Actions` · `cosign` |

Shift-left security, SAST, DAST, SCA, secrets scanning, container image scanning, IaC scanning, supply chain security (SBOM, Sigstore/cosign), CI/CD pipeline hardening.

**What you will be able to do:**
- Integrate SAST into a GitHub Actions pipeline
- Scan container images for CVEs before deployment
- Detect hardcoded secrets in git history
- Build SBOM for any containerised application
- Scan Terraform/CloudFormation for misconfigurations
- Implement branch protection and code signing

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/) | Complete framework for integrating security into every DevOps stage — free. |
| 🆓 FREE | [Semgrep — open-source SAST](https://semgrep.dev) | Pattern-based static analysis tool — free and open source. 3000+ community rules. |
| 🆓 FREE | [Trivy — container and IaC scanner](https://aquasecurity.github.io/trivy/) | The most popular open-source container security scanner. |
| 💰 PAID | [Practical DevSecOps — full certification course](https://www.practical-devsecops.com) | Hands-on DevSecOps course with a real pipeline lab environment. |

---

#### 22. CCSP — Certified Cloud Security Professional

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 12–18 months |
| **Salary** | PKR 400–800k/mo (cloud security architect) |
| **Opens roles** | Cloud security architect · Cloud CISO · Cloud security consultant · Principal security engineer |
| **Tools** | All major cloud consoles · CSPM tools · CASB solutions |

6 domains: cloud concepts, data security, platform security, application security, operations, legal/risk/compliance. The most globally recognised cloud security professional certification.

**What you will be able to do:**
- Design secure cloud architecture across all major providers
- Implement cloud data security including encryption key management
- Assess and manage cloud-specific risks and threats
- Understand multi-jurisdiction compliance for cloud deployments
- Lead cloud security operations
- Achieve CCSP certification (requires 5yr IT + 3yr security + 1yr cloud experience)

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [(ISC)² CCSP free student workbook](https://www.isc2.org/certifications/ccsp/ccsp-student-workbook) | Official free study materials. Domain outlines, key concept summaries, sample questions. |
| 💰 PAID | [CCSP All-in-One Exam Guide — Ben Carter](https://www.mheducation.com/highered/product/ccsp-certified-cloud-security-professional-all-one-exam-guide-third-edition-carter/M9781260565997.html) | The most comprehensive CCSP study book — 700 pages. |
| 🎓 CERT | [CCSP certification](https://www.isc2.org/certifications/ccsp) | The globally recognised cloud security professional certification. |
| 🎓 CERT | [AWS Security Specialty (SCS-C02)](https://aws.amazon.com/certification/certified-security-specialty/) | AWS's deep security certification. GuardDuty, Security Hub, Macie, WAF, Shield Advanced, CloudTrail analytics. |

---

## Phase 5 — AI Security Mastery

**Timeline:** Year 3–5 · **Category:** AI Security · **Topics:** 6

> AI security is the fastest-growing and highest-paying security niche of 2025–2030. Almost nobody has formal expertise yet.

> ⚠️ **Important:** Prerequisites: solid Python programming, basic understanding of how APIs work, familiarity with web application security. You do not need a machine learning PhD — but you need to understand how AI systems are built to secure them.

### AI & ML Foundations for Security

---

#### 23. Machine Learning Fundamentals for Security

| | |
|---|---|
| **Difficulty** | ⭐⭐ Moderate |
| **Time** | 2–3 months |
| **Salary** | Strong foundation for AI security premium |
| **Opens roles** | AI security engineer · ML security researcher |
| **Tools** | `Python` · `HuggingFace Transformers` · `OpenAI API` · `LangChain` |

Supervised and unsupervised learning, neural network architecture, transformer models, LLM training and fine-tuning, inference pipeline, embeddings, vector databases, RAG architecture.

**What you will be able to do:**
- Explain how transformers and attention work at a conceptual level
- Understand the LLM training pipeline from data to deployment
- Know how RAG systems work and their security implications
- Understand embeddings and why they can leak information
- Read and understand AI system architecture diagrams
- Identify the attack surface of an LLM-powered application

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Andrej Karpathy — Neural Networks: Zero to Hero (YouTube)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) | Build GPT from scratch in Python. Backpropagation, language models, attention, full transformer architecture. |
| 🆓 FREE | [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai) | Top-down practical ML course — free. Image classification, NLP, tabular data, diffusion models in 8 weeks. |
| 🆓 FREE | [Kaggle Learn — ML courses](https://www.kaggle.com/learn) | Short hands-on ML courses with notebooks — free. Intro ML, intermediate ML, feature engineering, NLP, deep learning. |

### LLM Vulnerabilities & Attacks

---

#### 24. OWASP LLM Top 10 — Complete Deep Dive

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 300–600k/mo (LLM security engineer) |
| **Opens roles** | AI red-teamer · LLM security engineer · AI application security analyst |
| **Tools** | `Garak` · `PyRIT` · `LLM-Guard` · `Burp Suite + AI extensions` |

LLM01 Prompt Injection, LLM02 Insecure Output Handling, LLM03 Training Data Poisoning, LLM04 Model DoS, LLM05 Supply Chain Vulnerabilities, LLM06 Sensitive Information Disclosure, LLM07 Insecure Plugin Design, LLM08 Excessive Agency, LLM09 Overreliance, LLM10 Model Theft.

**What you will be able to do:**
- Exploit all 10 OWASP LLM vulnerability classes in a lab
- Demonstrate indirect prompt injection through a poisoned document
- Show how excessive agency enables lateral movement in agentic systems
- Identify and test all LLM attack surfaces in a given application
- Write a security assessment report for an LLM application

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [OWASP LLM Top 10 official guide](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | The security community standard reference for LLM vulnerabilities. |
| 🆓 FREE | [MITRE ATLAS — AI threat framework](https://atlas.mitre.org) | ATT&CK for AI/ML systems — adversary tactics mapped to machine learning. |
| 🆓 FREE | [Johann Rehberger's blog — prompt injection research](https://embracethered.com/blog/) | The best practical research on prompt injection and LLM exploitation. |
| 🆓 FREE | [Lakera — Gandalf prompt injection challenge](https://gandalf.lakera.ai) | Learn prompt injection by playing a game — 10 progressively harder defences. |

---

#### 25. Adversarial ML Attacks

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 2–3 months |
| **Salary** | PKR 400–800k/mo (adversarial ML researcher) |
| **Opens roles** | ML security researcher · AI red-teamer · Adversarial ML engineer |
| **Tools** | `Adversarial Robustness Toolbox` · `CleverHans` · `Foolbox` · `TextAttack` |

Evasion attacks (FGSM, PGD, C&W, AutoAttack), data poisoning, model inversion, membership inference, model stealing, backdoor/trojan attacks. Defences: adversarial training, certified robustness.

**What you will be able to do:**
- Implement FGSM evasion attack against an image classifier
- Perform model inversion to extract training data from a model
- Detect and mitigate data poisoning in a training pipeline
- Evaluate a model's robustness against adversarial examples
- Identify backdoor behaviour in a pre-trained model
- Apply adversarial training as a defence

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Adversarial Robustness Toolbox (ART) — IBM Research](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | Python library with 100+ attacks and defences — free. The standard tool for adversarial ML research. |
| 🆓 FREE | [Original FGSM paper — Goodfellow et al.](https://arxiv.org/abs/1412.6572) | The seminal adversarial examples paper. 8 pages. Core intuition for all adversarial ML. |
| 💰 PAID | [Practical Machine Learning Security (O'Reilly)](https://www.oreilly.com/library/view/practical-machine-learning/9781492073048/) | The professional ML security book — bridges ML engineering and security engineering. |

---

#### 26. LLM Red-Teaming & AI Pentesting

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 400–800k/mo (AI red-teamer) |
| **Opens roles** | AI red-teamer · LLM pen-tester · AI security consultant |
| **Tools** | `Garak` · `PyRIT` · `Promptmap` · `Burp Suite` · `Custom Python scripts` |

Direct and indirect prompt injection, jailbreaking techniques, context window attacks, RAG poisoning, multi-turn manipulation, tool/function call exploitation, multi-modal attacks, agentic system exploitation.

**What you will be able to do:**
- Perform a structured red-team assessment of an LLM application
- Document findings in a professional AI security assessment report
- Test all injection vectors: direct, indirect, multi-turn, multi-modal
- Exploit excessive agency in an agentic AI system
- Test RAG pipeline for data poisoning vulnerabilities
- Use Garak and PyRIT for automated LLM security testing

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Garak — LLM vulnerability scanner](https://github.com/leondz/garak) | Automated LLM red-teaming tool — 100+ vulnerability probes. Generates structured reports. |
| 🆓 FREE | [PyRIT — Microsoft's Python Red Team tool](https://github.com/Azure/PyRIT) | Microsoft's enterprise LLM red-teaming framework. Multi-turn conversations, scoring engines. |
| 🆓 FREE | [Simon Willison — Prompt injection attacks blog](https://simonwillison.net/2023/Apr/14/worst-that-could-happen/) | Why indirect injection through email, web pages, documents is dangerous for agentic systems. |

### LLM Defence & AI Governance

---

#### 27. LLM Hardening, Guardrails & MLSecOps

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 350–700k/mo (AI security engineer) |
| **Opens roles** | AI security engineer · MLSecOps engineer · LLM platform security |
| **Tools** | `LLM-Guard` · `NeMo Guardrails` · `Lakera Guard` · `ModelScan` · `PromptArmor` |

Input/output filtering, semantic similarity defence, content classifiers, system prompt hardening, sandboxing agentic systems, securing the ML supply chain, model registry security.

**What you will be able to do:**
- Deploy LLM-Guard in a production LLM application
- Configure NeMo Guardrails to restrict LLM conversation scope
- Scan model files for embedded malware with ModelScan
- Design a secure LLM application architecture with defence in depth
- Implement output validation to prevent insecure output handling
- Build a threat model for an agentic AI system

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [LLM-Guard — Protect AI](https://github.com/protectai/llm-guard) | Production LLM security layer with 20+ scanners — free. Prompt injection detection, PII anonymisation, toxicity filtering. |
| 🆓 FREE | [NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Conversation flow control for LLMs — free. Define guardrails in YAML. |
| 🆓 FREE | [ModelScan — Protect AI](https://github.com/protectai/modelscan) | Security scanner for ML model files — free. Scan pickle, PyTorch, TensorFlow model files for embedded malware. |

---

#### 28. AI Governance, Safety & Regulatory Compliance

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | 2–3 months |
| **Salary** | PKR 350–700k/mo (AI governance specialist) |
| **Opens roles** | AI compliance officer · AI safety engineer · AI risk analyst · AI governance lead |
| **Tools** | `SHAP` · `LIME` · `Fairlearn` · `IBM AI Fairness 360` · `Google What-If Tool` |

NIST AI RMF, EU AI Act, ISO 42001, model cards, bias auditing, explainability (SHAP, LIME), red-team reports.

**What you will be able to do:**
- Apply NIST AI RMF to an AI system deployment
- Determine if a system falls under EU AI Act high-risk category
- Write a model card for a deployed ML model
- Perform bias audit on a classification model
- Generate SHAP explanations for model predictions
- Write an AI red-team assessment report

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [NIST AI Risk Management Framework](https://www.nist.gov/system/files/documents/2023/01/26/AI%20RMF%201.0.pdf) | The US government's AI risk framework — free 64-page document. 4 core functions (Govern, Map, Measure, Manage). |
| 🆓 FREE | [EU AI Act — full text and explanations](https://artificialintelligenceact.eu) | The EU AI Act with article-by-article explanation. Risk categories, compliance requirements, penalties. |
| 🆓 FREE | [SHAP — SHapley Additive exPlanations library](https://shap.readthedocs.io) | The standard ML explainability library. Explain any ML model's predictions. Required for many regulated AI deployments. |

---

## Phase 6 — Advanced Specialisations & CISSP

**Timeline:** Year 4–6 · **Category:** Advanced · **Topics:** 3

> This is where you separate from the senior tier and move toward architect, principal, or leadership roles. CISSP is the gateway to CISO and director-level positions.

### Elite Specialisations

---

#### 29. Vulnerability Research & 0-Day Discovery

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 6–12 months |
| **Salary** | $200k–$2M+ (elite VR — includes bounties) |
| **Opens roles** | Vulnerability researcher · 0-day analyst · Bug bounty hunter · Exploit broker · Red team lead |
| **Tools** | `AFL++` · `libFuzzer` · `angr` · `Ghidra` · `BinDiff` · `sanitizers (ASAN/MSAN)` |

Coverage-guided fuzzing, symbolic execution, source code auditing, patch diffing, CVE discovery and responsible disclosure, exploit reliability and weaponisation, bug bounty at scale.

**What you will be able to do:**
- Fuzz a real-world application and find a crash
- Audit C/C++ source code for memory safety issues
- Perform patch diffing to find n-day vulnerabilities
- Submit a bug bounty report that earns a payout
- Write a CVE advisory and work through responsible disclosure
- Understand exploit reliability and stabilisation techniques

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [AFL++ — state-of-the-art fuzzer](https://github.com/AFLplusplus/AFLplusplus) | The leading coverage-guided fuzzer — free. Configure fuzzing campaigns, triage crashes, use AddressSanitizer. |
| 🆓 FREE | [LiveOverflow — binary exploitation YouTube](https://www.youtube.com/@LiveOverflow) | 10 years of vulnerability research and exploitation content. Real CVE analysis, CTF exploitation, kernel and browser security. |
| 🆓 FREE | [Google Project Zero blog](https://googleprojectzero.blogspot.com) | Technical write-ups of real 0-day vulnerabilities from Google's elite research team. |

---

#### 30. Cloud Security Architecture

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 3–4 months |
| **Salary** | PKR 600k–1.2M/mo (cloud security architect) |
| **Opens roles** | Cloud security architect · Principal security engineer · Enterprise security architect · Freelance vCISO |
| **Tools** | `AWS Well-Architected Tool` · `Azure Security Benchmark` · `Wiz` · `Orca Security` · `Prisma Cloud` |

Enterprise zero-trust network design, SASE architecture, CASB deployment, CNAPP platform evaluation, encryption key management strategy (HSMs), multi-cloud security strategy, cloud IR playbooks, security architecture reviews.

**What you will be able to do:**
- Design an enterprise zero-trust architecture for a 5000-person organisation
- Evaluate and select CNAPP/CSPM tools against requirements
- Define an encryption key management strategy
- Write a cloud security architecture decision record
- Lead a security architecture review for a major new cloud deployment
- Build cloud incident response runbooks

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [AWS Architecture Center — security reference architectures](https://aws.amazon.com/architecture/) | Official AWS architecture patterns — free. Multi-account strategies, network segmentation patterns. |
| 🆓 FREE | [AWS Well-Architected Framework — Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) | AWS's opinionated guide to secure cloud architecture — free. Identity, detection, infrastructure protection, data protection, IR. |

### CISSP — The Gold Standard

---

#### 31. CISSP — Certified Information Security Professional

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 12–24 months study |
| **Salary** | PKR 500k–1.2M/mo after CISSP (management track) |
| **Opens roles** | CISO · Security director · GRC director · Security architect · vCISO consultant |
| **Tools** | All security domains — management-level synthesis |

8 domains: Security and Risk Management, Asset Security, Security Architecture and Engineering, Communication and Network Security, Identity and Access Management, Security Assessment and Testing, Security Operations, Software Development Security. The most respected security cert in the world. Requires 5 years relevant experience.

**What you will be able to do:**
- Demonstrate mastery across all 8 CISSP domains
- Think from a management and risk perspective, not just technical
- Pass the CAT exam — 125–175 questions
- Open CISO, Security Director, VP Security roles
- Earn the single largest salary jump from any single certification

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Prabh Nair — CISSP Memory Palace (YouTube)](https://www.youtube.com/watch?v=_nyZhYnCNLA) | Free CISSP exam prep using memory techniques. All 8 domains with memory anchors. 500k+ views. |
| 🆓 FREE | [Larry Greenblatt — CISSP free lectures (YouTube)](https://www.youtube.com/c/ITMasterClass) | Free deep-dive CISSP lectures across all domains. Real understanding, not memorisation. |
| 💰 PAID | [CISSP All-in-One Exam Guide — Harris & Maymi (9th Ed)](https://www.mheducation.com/highered/product/cissp-all-one-exam-guide-ninth-edition-harris-maymi/M9781260467215.html) | The most comprehensive CISSP study book — 1400+ pages, 1000+ practice questions. |
| 🎓 CERT | [CISSP certification — (ISC)²](https://www.isc2.org/certifications/cissp) | The most respected security certification in the world. Average global salary: $135k+. Prereq: 5yr experience in 2+ domains. |

---

## Phase 7 — Quantum Security — The Frontier

**Timeline:** Year 5–8 · **Category:** Quantum · **Topics:** 4

> Quantum computing threatens the foundations of modern cryptography. RSA-2048 and ECC-256 — which protect virtually all internet traffic — will be broken by a sufficiently powerful quantum computer running Shor's algorithm. The transition to post-quantum cryptography is the largest cryptographic migration in history.

> ⚠️ **Important:** STOP. Start quantum ONLY after: CISSP or CCSP earned, classical cryptography mastered at implementation level, Python solid, and linear algebra comfortable. The 2030 CISA deadline is your target.

### Mathematical Prerequisites

---

#### 32. Linear Algebra & Quantum Mechanics Foundations

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 3–4 months |
| **Salary** | Prerequisite for quantum security specialist |
| **Opens roles** | Quantum security researcher · Quantum cryptographer |
| **Tools** | `Qiskit` · `IBM Quantum` · `Cirq` · `PennyLane` |

Vector spaces, linear transformations, eigenvalues, tensor products, complex vector spaces, Dirac bra-ket notation, quantum mechanics postulates, quantum gates, quantum circuits.

**What you will be able to do:**
- Represent quantum states as vectors in Hilbert space
- Apply quantum gates (Hadamard, CNOT, Toffoli) as matrix operations
- Understand superposition and entanglement mathematically
- Read and write quantum circuits in Qiskit
- Explain measurement postulate and why it destroys superposition
- Compute tensor products for multi-qubit systems

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [3Blue1Brown — Essence of Linear Algebra (YouTube)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | The most beautiful visual introduction to linear algebra. 15 videos. Watch before touching Qiskit. |
| 🆓 FREE | [IBM Qiskit Textbook — Quantum Computing](https://qiskit.org/learn) | IBM's comprehensive free quantum computing textbook with runnable code on real hardware. |
| 🆓 FREE | [MIT OpenCourseWare — 8.04 Quantum Physics I](https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/) | Full MIT quantum mechanics course — free. Focus on chapters 1–4 for quantum computing relevance. |
| 💰 PAID | [Quantum Computing: An Applied Approach — Jack Hidary](https://www.springer.com/gp/book/9783030239213) | The best bridge between quantum computing and practical implementation. Real code in Qiskit, Cirq, TensorFlow Quantum. |

### Post-Quantum Cryptography

---

#### 33. Post-Quantum Cryptography Standards

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 4–6 months |
| **Salary** | $150k–$350k/yr (global — quantum crypto specialist) |
| **Opens roles** | Post-quantum cryptographer · Quantum security engineer · Cryptography architect · Standards contributor |
| **Tools** | `Open Quantum Safe (liboqs)` · `PyCryptodome` · `Botan` · `BouncyCastle PQC` |

Why RSA and ECC break under Shor's algorithm. NIST PQC winners: CRYSTALS-Kyber (FIPS 203), CRYSTALS-Dilithium (FIPS 204), FALCON (FIPS 206), SPHINCS+ (FIPS 205). Lattice-based cryptography, hash-based signatures, code-based cryptography.

**What you will be able to do:**
- Explain why Shor's algorithm breaks RSA and ECC
- Understand the mathematical foundation of lattice-based cryptography (LWE)
- Implement Kyber key exchange using liboqs
- Implement Dilithium signatures using liboqs
- Compare security levels and performance of NIST PQC algorithms
- Evaluate which PQC algorithms fit different use cases

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [NIST Post-Quantum Cryptography project](https://csrc.nist.gov/projects/post-quantum-cryptography) | Complete NIST PQC standardisation project. Algorithm specifications for Kyber, Dilithium, FALCON, SPHINCS+. |
| 🆓 FREE | [Open Quantum Safe — liboqs library](https://openquantumsafe.org) | Production-ready PQC implementations in C with Python/Go/Java/Rust bindings — free. OQS-OpenSSL enables PQC in TLS. |
| 🆓 FREE | [Bernstein & Lange — PQCrypto course (YouTube)](https://www.youtube.com/playlist?list=PLhkFiVnO0gE--fJBJ7kfW3rCv8sMuIFQf) | University-level PQC course from the researchers who designed the algorithms. |

---

#### 34. Shor's & Grover's Algorithms

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 2–3 months |
| **Salary** | Core knowledge for quantum security specialist |
| **Opens roles** | Quantum security architect · Crypto migration lead |
| **Tools** | `IBM Quantum` · `Qiskit` · `Quirk` |

Shor's algorithm — quantum period finding, quantum Fourier transform, why it factors large integers efficiently. Grover's algorithm — quadratic speedup, implications for symmetric key length (AES-128 → effective 64-bit). Threat model for cryptographic migration timelines.

**What you will be able to do:**
- Trace through Shor's algorithm step by step
- Explain why Grover's algorithm means AES-128 needs replacement
- Run a simplified Shor's algorithm on IBM Quantum hardware
- Calculate T-count and qubit requirements for cryptographically relevant Shor's
- Advise on key size recommendations for post-quantum security margins
- Build a quantum threat timeline for an organisation

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [IBM Quantum Learning — Shor's algorithm tutorial](https://learning.quantum.ibm.com/tutorial/shors-algorithm) | Interactive walkthrough with real quantum circuits — run on IBM hardware. |
| 🆓 FREE | [Scott Aaronson — Quantum Computing Since Democritus](https://www.scottaaronson.com/qclec.pdf) | Lecture notes from the field's best communicator — free PDF. Complexity theory, quantum algorithms, cryptography implications. |

---

#### 35. Cryptographic Migration Strategy

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 3–4 months |
| **Salary** | PKR 500k–1.5M/mo (quantum security architect) |
| **Opens roles** | Quantum security architect · Crypto migration lead · CISO (quantum-ready) · Government security advisor |
| **Tools** | `OpenSSL 3.x + OQS provider` · `Cryptosense Analyzer` · `IBM Crypto Discovery` |

Crypto agility design, discovering RSA/ECC usage across an enterprise, hybrid classical+PQC deployment (X25519+Kyber768), TLS 1.3 + PQC cipher suites, CISA quantum readiness guidance, NSA CNSA 2.0 requirements (2030 deadline).

**What you will be able to do:**
- Inventory all cryptographic usage in an enterprise system
- Prioritise migration based on data sensitivity and exposure
- Deploy a hybrid classical+PQC TLS configuration
- Write a quantum readiness assessment report
- Build a 5-year cryptographic migration roadmap
- Present quantum risk to executive and board audiences

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [CISA Post-Quantum Cryptography Initiative](https://www.cisa.gov/quantum) | US government roadmap for the quantum transition. Official timeline (migrate by 2030). |
| 🆓 FREE | [NSA CNSA 2.0 algorithm requirements (PDF)](https://media.defense.gov/2022/Sep/07/2003071834/-1/-1/0/CSA_CNSA_2.0_ALGORITHMS_.PDF) | NSA's official algorithm transition requirements — 1-page PDF. CRYSTALS-Kyber, Dilithium, SPHINCS+, AES-256, SHA-384. |
| 🆓 FREE | [NIST IR 8547 — Migration to PQC guidance](https://csrc.nist.gov/pubs/ir/8547/ipd) | Technical guidance on how to migrate — discover crypto usage, prioritise systems, hybrid deployment. |
| 🎓 CERT | [IBM Quantum Developer Certification](https://www.ibm.com/training/certification/ibm-certified-associate-developer-quantum-computation-using-qiskit-v0-2x-C0010300) | Currently the main quantum computing certification. Write quantum programs in Qiskit, run on real hardware. |

### Quantum Cryptographic Protocols

---

#### 36. Quantum Key Distribution (QKD)

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 2–3 months |
| **Salary** | Specialist niche — government/banking premium |
| **Opens roles** | Quantum network engineer · QKD specialist · Quantum security researcher |
| **Tools** | `SimulaQron` · `NetSquid` · `Qiskit` · `ETSI QKD standards` |

BB84 protocol, E91 entanglement-based QKD, quantum repeaters, QKD network architectures, QKD vs PQC trade-offs, practical deployment limitations (distance, cost, authentication problem).

**What you will be able to do:**
- Explain BB84 protocol step by step including security proof
- Simulate a QKD session with eavesdropping detection
- Evaluate when QKD is preferable to PQC
- Understand quantum repeaters and their role in long-distance QKD
- Identify practical limitations of current QKD deployments
- Design a QKD network for a high-security use case

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [IBM Quantum Learning platform](https://learning.quantum.ibm.com) | Free quantum computing education with access to real IBM quantum hardware. |
| 🆓 FREE | [SimulaQron — quantum network simulator](https://simulaqron.org) | Simulate quantum networks and QKD protocols without real hardware — free. Implement BB84, test eavesdropping detection. |
| 🆓 FREE | [ETSI QKD standards](https://www.etsi.org/technologies/quantum-key-distribution) | Industry standards for QKD deployment. Deployment requirements, integration with classical networks, security assumptions. |

---

## Phase 8 — Emerging Tech & World-Class Status

**Timeline:** Year 5+ · **Category:** Emerging · **Topics:** 5

> This phase separates good senior practitioners from globally recognised world-class experts. Publishing original research, speaking at top conferences, discovering real vulnerabilities, and building things that change the field.

> ✅ **Achievement:** By this phase you have enough depth to specialise in one of these emerging areas and become one of the world's leading experts within 2–3 years. The field is young enough that true mastery is achievable in your lifetime.

### Emerging Security Domains

---

#### 37. Blockchain & Smart Contract Security

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 4–6 months |
| **Salary** | $200–$500/hr (smart contract auditor) |
| **Opens roles** | Smart contract auditor · DeFi security researcher · Blockchain security engineer |
| **Tools** | `Slither` · `Echidna` · `Foundry` · `Hardhat` · `MythX` · `Certora` |

Solidity vulnerability classes (reentrancy, integer overflow, access control, tx.origin, delegatecall, front-running, flash loans), DeFi protocol attack surface, MEV, audit methodology, contest platforms (Code4rena, Sherlock).

**What you will be able to do:**
- Audit a Solidity smart contract for all major vulnerability classes
- Exploit a reentrancy vulnerability in a test environment
- Write a professional smart contract audit report
- Use Slither for automated vulnerability detection
- Submit a finding to a competitive audit contest
- Understand DeFi cross-protocol attack surfaces

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Ethernaut — OpenZeppelin CTF](https://ethernaut.openzeppelin.com) | Smart contract security CTF — 25+ levels of vulnerable contracts. Covers reentrancy, delegatecall, storage slot collisions, flash loans. |
| 🆓 FREE | [Slither — Trail of Bits static analyser](https://github.com/crytic/slither) | The most popular Solidity static analyser. 80+ vulnerability classes detected automatically. |
| 💰 PAID | [Cyfrin Updraft — Smart Contract Auditing course](https://updraft.cyfrin.io) | Professional smart contract auditing curriculum — 200+ hours. Complete methodology with real case studies. |

---

#### 38. IoT & Embedded Systems Security

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 4–6 months |
| **Salary** | PKR 350–700k/mo (IoT/OT security) |
| **Opens roles** | IoT security engineer · OT security specialist · Embedded security researcher · Hardware security analyst |
| **Tools** | `binwalk` · `Ghidra` · `OpenOCD` · `HackRF` · `JTAG debuggers` · `Wireshark` |

Firmware extraction and analysis, UART/JTAG debugging, SPI/I2C bus analysis, RF analysis (SDR), bootloader bypass, RTOS security, automotive security (CAN bus), medical device security, ICS/SCADA/OT.

**What you will be able to do:**
- Extract and analyse firmware from an IoT device
- Establish a UART shell on an embedded device
- Identify hardcoded credentials in firmware
- Capture and decode CAN bus traffic
- Perform a basic hardware security assessment
- Understand FDA medical device cybersecurity requirements

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [Binwalk — firmware extraction and analysis](https://github.com/ReFirmLabs/binwalk) | The first tool every firmware analyst uses. Extract file systems, find embedded keys and passwords. |
| 🆓 FREE | [OWASP IoT Attack Surface Areas](https://owasp.org/www-project-internet-of-things/) | OWASP's IoT security framework. Structured methodology for IoT security assessments. |
| 💰 PAID | [The Hardware Hacking Handbook — No Starch](https://nostarch.com/hardwarehacking) | The definitive hardware security reference. UART, JTAG, SPI/I2C, fault injection, side-channel analysis. |

---

#### 39. Agentic AI Security

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Expert |
| **Time** | 3–4 months |
| **Salary** | PKR 500k–1.5M/mo (agentic AI security — extremely rare) |
| **Opens roles** | Agentic AI security engineer · AI systems security researcher · AI red team lead |
| **Tools** | `LangChain` · `LangGraph` · `AutoGPT` · `AgentDojo` · `PyRIT` |

Multi-agent system architectures, LLM orchestration frameworks, tool-use exploitation, memory and context manipulation, privilege escalation in agent systems, multi-hop prompt injection, computer-use agent attacks, agentic security design patterns.

**What you will be able to do:**
- Map the attack surface of a multi-agent AI system
- Demonstrate privilege escalation through agent tool misuse
- Exploit indirect prompt injection in an agent that uses web search
- Design secure agentic system architecture with minimal-privilege tools
- Write a threat model for a production agentic AI deployment
- Implement monitoring and anomaly detection for agent behaviour

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [AgentDojo — AI agent security benchmark](https://github.com/ethz-spylab/agentdojo) | First structured security benchmark for AI agents — from ETH Zurich. Real attack scenarios against agent behaviour. |
| 🆓 FREE | [Simon Willison — Prompt injection in agentic systems](https://simonwillison.net/2023/Apr/14/worst-that-could-happen/) | Clearest analysis of why prompt injection is existentially dangerous for agentic systems. |
| 🆓 FREE | [LangChain security documentation](https://python.langchain.com/docs/security) | Official LangChain security guidance. Prompt injection in chains, tool call exploitation, output parser attacks. |

---

#### 40. Zero-Knowledge Proofs & Privacy Tech

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐⭐ Pioneer |
| **Time** | 4–6 months |
| **Salary** | $250k–$500k/yr (global — ZK security specialist) |
| **Opens roles** | ZK security auditor · Privacy engineer · Cryptography researcher · ZK protocol developer |
| **Tools** | `Circom` · `SnarkJS` · `RISC Zero` · `Aztec` · `StarkNet tools` |

ZK-SNARKs (Groth16, PLONK), ZK-STARKs (FRI protocol), ZK circuit writing, homomorphic encryption, secure multi-party computation, differential privacy, privacy-preserving ML.

**What you will be able to do:**
- Write and compile a basic ZK circuit in Circom
- Explain the difference between SNARKs and STARKs
- Identify vulnerabilities in ZK circuit implementations
- Understand when to use FHE vs MPC vs ZK proofs
- Audit a ZK application for common implementation errors
- Contribute to an open-source ZK project

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [ZKProof community resources](https://zkproof.org/resources/) | The ZK standardisation community's reference materials. Introductory overview papers. |
| 🆓 FREE | [Vitalik Buterin — STARKs explained](https://vitalik.ca/general/2018/07/21/starks_part_3.html) | The best explanation of ZK-STARKs by Ethereum's creator. Polynomial commitments, FRI protocol. |
| 🆓 FREE | [Circom — ZK circuit language documentation](https://docs.circom.io) | Full documentation and tutorials for the Circom ZK DSL. Write constraints, compile, generate and verify proofs. |

### Publishing, Research & Global Recognition

---

#### 41. Security Research, Publishing & World-Class Recognition

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Hard |
| **Time** | Ongoing |
| **Salary** | Opens $300k+/yr consulting and speaking opportunities |
| **Opens roles** | Security researcher · Conference speaker · Security author · Bug bounty hunter · Security consultant |
| **Tools** | `HackerOne` · `Bugcrowd` · `GitHub` · `Twitter/X` · `personal blog` |

CVE discovery and responsible disclosure, writing technical blog posts, conference talk proposals (DEF CON, Black Hat, BSides, USENIX), academic paper structure, bug bounty at scale, building public reputation.

**What you will be able to do:**
- Publish at least one original technical security blog post per month
- Submit a CVE through responsible disclosure
- Earn a bug bounty payout (start with any amount)
- Submit a talk proposal to a BSides conference
- Build a public GitHub profile with original security tools
- Be known by name in at least one security community

**Resources:**

| Type | Resource | What It Teaches |
|------|----------|-----------------|
| 🆓 FREE | [HackerOne — bug bounty platform](https://www.hackerone.com) | The world's largest bug bounty platform. Find real vulnerabilities in production systems for cash. Top hackers earn over $1M/year. |
| 🆓 FREE | [DEF CON — Call for Papers (CFP)](https://defcon.org/html/links/dc-cfp.html) | How to submit a talk to the world's most famous hacker conference. Start with BSides, work up to DEF CON. |
| 🆓 FREE | [Google Scholar — security research papers](https://scholar.google.com) | Free academic search engine. Follow top researchers from CMU, MIT, Stanford, ETH Zurich, Google Project Zero. |
| 🆓 FREE | [arXiv.org — security and cryptography preprints](https://arxiv.org/list/cs.CR/recent) | Free preprint server. New research before conference publication. Stay at the frontier. |

---

## Summary

| Phase | Focus | Timeline | Key Cert |
|-------|-------|----------|----------|
| 0 | Mindset & Learning System | Month 0–1 | — |
| 1 | Core Technical Foundations | Months 1–8 | **Security+** |
| 2 | Offensive Security — Red Team | Year 1–2 | **OSCP** |
| 3 | Defensive Security — Blue Team | Year 1–3 | **BTL1** |
| 4 | Cloud Security Mastery | Year 2–4 | **CCSP / AWS Security** |
| 5 | AI Security Mastery | Year 3–5 | — (emerging) |
| 6 | Advanced Specialisations | Year 4–6 | **CISSP** |
| 7 | Quantum Security | Year 5–8 | **IBM Quantum Dev** |
| 8 | Emerging Tech & World-Class | Year 5+ | CVEs + Conference talks |

---

*From zero to quantum security pioneer. The shortest path is the one you actually walk.*
