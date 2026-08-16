# Dolgormaa Sansarsaikhan (Donna) 

**Computer Science @ University of Colorado Boulder · Class of 2028**  
Security Engineering · Secure Systems · Applied Research

---

## What I Work On 💼

I build and break systems at the intersection of cybersecurity and low-level computing. My work spans hardware security research, blue-team incident response tooling, and adversarial simulation, grounded in real competition and research experience rather than coursework alone.

Currently an **NSF-funded Undergraduate Researcher** investigating performance optimizations for disaggregated memory systems over CXL interconnects, and a **Software Engineering Sprintern at Google** (Break Through Tech, Summer 2026).

---

## Research 📓

### CAPULET - CXL Cache-Pooling Architecture
*NSF REU · Prof. Tamara Lehman's Research Group · University of Colorado Boulder · Summer 2026*

Contributing to CAPULET, a prototype cache-pooling architecture for CXL-based disaggregated memory systems. Work includes:

- Implemented a miss-rate threshold-driven remote fill policy, dynamically routing evicted cache blocks to underutilized remote nodes based on runtime access patterns
- Built an admission control mechanism (`accepting_remote`) that tracks remote cache capacity across hosts and redirects evictions when target nodes reach capacity, preventing cascading remote fill requests
- Implemented fairness-aware round-robin node selection to distribute remote cache load evenly across many-node CXL configurations
- Developed heterogeneous multi-trace workload infrastructure to evaluate the prototype under realistic, divergent per-node access patterns

*Potential publication in progress.*

---

## Software Engineering 🤖

### MSAi Manager
[MSAi-Manager](https://github.com/Alexz3221/MSAi-Manager) · Python / Google Vertex AI  
*Software Engineering Sprintern · Google (Break Through Tech) · Summer 2026*

An AI-powered tool that helps clients understand which recent Mandatory Service Agreement (MSA) updates affect the Google Cloud services they use, delivering personalized, plain-language summaries with scheduling to notify clients when new MSAs take effect on their distribution date.

My contributions:

- Built an MSA keyword-extraction component that parses updates and stores key information in structured JSON, enabling downstream matching of service changes to each client's cloud environment
- Developed an AI agent using Google Vertex AI to generate personalized update summaries, applying output optimization to improve response relevance and consistency
- Assessed the agent's resilience to direct and indirect prompt injection, probing how adversarial instructions, supplied directly in user prompts or embedded within ingested MSA content that could override intended behavior or manipulate generated output

---

## Cybersecurity Projects 💻

### 🛠️ Blue-Team IR Toolkit
[BlueTeam-IR-Toolkit](https://github.com/DolgormaaS/BlueTeam-IR-Toolkit) · PowerShell

Modular PowerShell-based incident response toolkit for Windows environments. Covers current system status, user activity forensics (logon/logoff/account creation via Security event log), Windows Defender and firewall status checks, and active network connection analysis.

### 🔍 Custom Python Tools
[Custom-Python-Tools-for-Cyber](https://github.com/DolgormaaS/Custom-Python-tools-for-Cyber) · Python

Includes multi-threaded TCP port scanner with socket-based concurrency, configurable scan ranges, timeout handling, and modular architecture designed for extension to service detection and banner grabbing. Working on implementing banner grabber. 

### 🧪 Virtualized Security Research Lab
VMware-hosted segregated network environment for offensive security practice and malware analysis. Conducted vulnerability assessments against intentional targets (Metasploitable) using Nmap for enumeration and Metasploit for exploitation. Windows sandbox used for development and stability testing of custom security tools.

---

## Competition Record 🏆

| Competition | Result | Year |
|---|---|---|
| Collegiate Cyber Defense Competition (CCDC) - Regional | **1st Place** | 2026 |
| National Cyber League (NCL) | **Top 5% Nationally** - 217th / 4,898 teams | 2024 |
| Cyber 9/12 Strategy Challenge - Washington D.C. | **Semi-Finalist** | 2025 |
| Cyber 9/12 Strategy Challenge - New York City | **Semi-Finalist · Most Creative Policy Response** | 2024 |

---

## Recognition 🌟

- **FS-ISAC Scholar** - $10,000 national merit scholarship and mentorship program, Financial Services Information Sharing & Analysis Center (2025–2026)
- **NSF REU Researcher** - Federally funded undergraduate research position (2026–Present)
- **Break Through Tech · Google Cohort** - Competitive Sprinternship selection (Summer 2026)

---

## Skills 🛠

**Languages:** C/C++, Python, PowerShell, Assembly (x86)  
**Security Tools:** Wireshark, Nmap, Metasploit  
**Systems:** Kali Linux, Windows Administration, Active Directory, IIS, VMware, Git  
**Security & Risk:** NIST CSF, OWASP Top 10, Vulnerability Assessment, Incident Response, Log Analysis, Access Control

---

## Currently Building 🔧


- **IR Toolkit** - expanding PowerShell forensics coverage with persistence checks, registry analysis, and threat hunting modules
- **Custom Python Tools** - implementing banner grabbing and service detection on top of the existing port scanner
- **Null Vector: Exposure** - a story-driven cybersecurity education RPG built in Python/pygame under Usagi Interactive

---

## Connect 🌐ˎˊ˗

[LinkedIn](https://www.linkedin.com/in/dolgormaasansarsaikhan/) · [GitHub](https://github.com/DolgormaaS)
