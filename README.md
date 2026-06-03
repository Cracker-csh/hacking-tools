<p align="center">
  <img src="assets/banner.png" alt="Hacking Tools Banner" width="100%" />
</p>

<h1 align="center">🛡️ Hacking Tools</h1>

<p align="center">
  <b><i>Learn Cybersecurity One Tool at a Time</i></b>
</p>

<p align="center">
  <a href="https://github.com/mitro/hacking-tools/stargazers">
    <img src="https://img.shields.io/github/stars/mitro/hacking-tools?style=for-the-badge&logo=github&logoColor=white&color=0d1117&labelColor=161b22" alt="Stars" />
  </a>
  <a href="https://github.com/mitro/hacking-tools/network/members">
    <img src="https://img.shields.io/github/forks/mitro/hacking-tools?style=for-the-badge&logo=git&logoColor=white&color=0d1117&labelColor=161b22" alt="Forks" />
  </a>
  <a href="https://github.com/mitro/hacking-tools/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/mitro/hacking-tools?style=for-the-badge&logo=opensourceinitiative&logoColor=white&color=0d1117&labelColor=161b22" alt="License" />
  </a>
  <a href="https://github.com/mitro/hacking-tools/commits/main">
    <img src="https://img.shields.io/github/last-commit/mitro/hacking-tools?style=for-the-badge&logo=git&logoColor=white&color=0d1117&labelColor=161b22" alt="Last Commit" />
  </a>
  <a href="https://github.com/mitro/hacking-tools">
    <img src="https://img.shields.io/github/repo-size/mitro/hacking-tools?style=for-the-badge&logo=databricks&logoColor=white&color=0d1117&labelColor=161b22" alt="Repo Size" />
  </a>
</p>

<p align="center">
  <a href="#-categories">Categories</a> •
  <a href="#-featured-tools">Featured Tools</a> •
  <a href="#-learning-roadmap">Roadmap</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-support">Support</a>
</p>

---

## 📋 Table of Contents

- [Repository Overview](#-repository-overview)
- [Categories](#-categories)
  - [Information Gathering](#-information-gathering)
  - [Web Security](#-web-security)
  - [OSINT](#-osint)
  - [Network Security](#-network-security)
  - [Digital Forensics](#-digital-forensics)
  - [Reverse Engineering](#-reverse-engineering)
  - [Cloud Security](#-cloud-security)
  - [Malware Analysis](#-malware-analysis)
  - [Miscellaneous](#-miscellaneous)
- [Featured Tools](#-featured-tools)
- [Learning Roadmap](#-learning-roadmap)
- [Daily Tool Updates](#-daily-tool-updates)
- [Contributing](#-contributing)
- [Support](#-support)

---

## 🔎 Repository Overview

> **A curated, open-source encyclopedia of cybersecurity tools — organized, documented, and built for learners, professionals, and bug bounty hunters alike.**

This repository is **not** just a list of links. Every tool documented here includes:

| What You Get | Description |
|:---|:---|
| 🧰 **Installation Guides** | Step-by-step setup for every major OS |
| 📖 **Usage Walkthroughs** | Real-world commands with explanations |
| 🎯 **Bug Bounty Use Cases** | Practical offensive scenarios |
| 🛡️ **Detection & Defense** | How blue teams spot and counter the tool |
| 🤖 **AI Learning Notes** | Key takeaways distilled for rapid learning |
| 🔄 **Alternatives** | Similar tools for cross-referencing |

Whether you're preparing for **OSCP**, hunting on **HackerOne**, or building a **SOC** — this repo has you covered.

---

## 📂 Categories

### 🔍 Information Gathering

> *Reconnaissance is the foundation of every engagement. Know your target before you strike.*

Tools for footprinting, enumeration, DNS analysis, subdomain discovery, and technology fingerprinting.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Nmap](tools/information-gathering/nmap.md) | Network discovery & security auditing | 📄 |
| [Amass](tools/information-gathering/amass.md) | Attack surface mapping & asset discovery | 📄 |
| [Subfinder](tools/information-gathering/subfinder.md) | Fast passive subdomain enumeration | 📄 |
| [Shodan](tools/information-gathering/shodan.md) | Internet-connected device search engine | 📄 |
| [Recon-ng](tools/information-gathering/recon-ng.md) | Full-featured web reconnaissance framework | 📄 |
| [theHarvester](tools/information-gathering/theharvester.md) | E-mails, subdomains, hosts, & names harvester | 📄 |
| [Masscan](tools/information-gathering/masscan.md) | Internet-scale port scanner | 📄 |
| [Censys](tools/information-gathering/censys.md) | Search engine for internet-connected devices | 📄 |
| [WhatWeb](tools/information-gathering/whatweb.md) | Next-gen web scanner & fingerprinter | 📄 |
| [DNSRecon](tools/information-gathering/dnsrecon.md) | DNS enumeration & reconnaissance | 📄 |

<details>
<summary>📌 <b>More Information Gathering Tools</b></summary>
<br>

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Fierce](tools/information-gathering/fierce.md) | DNS reconnaissance tool for locating non-contiguous IP space | 📄 |
| [Dmitry](tools/information-gathering/dmitry.md) | Deepmagic information gathering tool | 📄 |
| [Maltego](tools/information-gathering/maltego.md) | Interactive data mining & link analysis | 📄 |

</details>

---

### 🌐 Web Security

> *The web is the largest attack surface. Master it.*

Tools for web application testing, vulnerability scanning, SQL injection, XSS, directory fuzzing, and more.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Burp Suite](tools/web-security/burpsuite.md) | Integrated platform for web security testing | 📄 |
| [OWASP ZAP](tools/web-security/zap.md) | Open-source web app security scanner | 📄 |
| [SQLMap](tools/web-security/sqlmap.md) | Automatic SQL injection & database takeover | 📄 |
| [Nikto](tools/web-security/nikto.md) | Web server vulnerability scanner | 📄 |
| [Gobuster](tools/web-security/gobuster.md) | Directory/file & DNS busting tool | 📄 |
| [Ffuf](tools/web-security/ffuf.md) | Fast web fuzzer written in Go | 📄 |
| [Wfuzz](tools/web-security/wfuzz.md) | Web application brute-force & fuzzer | 📄 |
| [XSStrike](tools/web-security/xsstrike.md) | Advanced XSS detection suite | 📄 |
| [Nuclei](tools/web-security/nuclei.md) | Fast vulnerability scanner with templates | 📄 |
| [Dirsearch](tools/web-security/dirsearch.md) | Web path discovery tool | 📄 |

<details>
<summary>📌 <b>More Web Security Tools</b></summary>
<br>

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Commix](tools/web-security/commix.md) | Automated OS command injection exploitation | 📄 |
| [WPScan](tools/web-security/wpscan.md) | WordPress security scanner | 📄 |
| [Arjun](tools/web-security/arjun.md) | HTTP parameter discovery suite | 📄 |

</details>

---

### 🕵️ OSINT

> *Open-source intelligence — the art of finding what's publicly available but hidden in plain sight.*

Tools for social media investigation, geolocation, email tracing, image forensics, and metadata analysis.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Maltego](tools/osint/maltego.md) | Visual link analysis & data mining | 📄 |
| [SpiderFoot](tools/osint/spiderfoot.md) | Automated OSINT collection | 📄 |
| [Sherlock](tools/osint/sherlock.md) | Username search across social networks | 📄 |
| [Photon](tools/osint/photon.md) | Fast web crawler designed for OSINT | 📄 |
| [ExifTool](tools/osint/exiftool.md) | Read & write metadata in files | 📄 |
| [Metagoofil](tools/osint/metagoofil.md) | Metadata extractor from public documents | 📄 |
| [Twint](tools/osint/twint.md) | Advanced Twitter scraping & OSINT | 📄 |
| [Holehe](tools/osint/holehe.md) | Check if an email is registered on sites | 📄 |
| [GHunt](tools/osint/ghunt.md) | Google account investigation tool | 📄 |
| [Recon-ng](tools/osint/recon-ng.md) | Web reconnaissance framework | 📄 |

---

### 🌐 Network Security

> *Control the network, control everything.*

Tools for packet analysis, MITM attacks, wireless hacking, traffic manipulation, and protocol exploitation.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Wireshark](tools/network-security/wireshark.md) | Network protocol analyzer | 📄 |
| [Metasploit](tools/network-security/metasploit.md) | Penetration testing framework | 📄 |
| [Aircrack-ng](tools/network-security/aircrack-ng.md) | Wireless network security toolset | 📄 |
| [Ettercap](tools/network-security/ettercap.md) | Comprehensive MITM attack suite | 📄 |
| [Responder](tools/network-security/responder.md) | LLMNR, NBT-NS & MDNS poisoner | 📄 |
| [Bettercap](tools/network-security/bettercap.md) | Swiss army knife for network attacks | 📄 |
| [Hping3](tools/network-security/hping3.md) | Network tool for packet crafting | 📄 |
| [Netcat](tools/network-security/netcat.md) | TCP/UDP networking swiss army knife | 📄 |
| [Tcpdump](tools/network-security/tcpdump.md) | Command-line packet analyzer | 📄 |
| [Scapy](tools/network-security/scapy.md) | Packet manipulation library & tool | 📄 |

---

### 🔬 Digital Forensics

> *Every action leaves a trace. Learn to find it.*

Tools for disk imaging, memory analysis, timeline reconstruction, file recovery, and evidence acquisition.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Autopsy](tools/digital-forensics/autopsy.md) | Digital forensics platform | 📄 |
| [Volatility](tools/digital-forensics/volatility.md) | Advanced memory forensics framework | 📄 |
| [Sleuth Kit](tools/digital-forensics/sleuthkit.md) | File system & volume forensic analysis | 📄 |
| [FTK Imager](tools/digital-forensics/ftk-imager.md) | Forensic data imaging tool | 📄 |
| [Binwalk](tools/digital-forensics/binwalk.md) | Firmware analysis & extraction | 📄 |
| [Foremost](tools/digital-forensics/foremost.md) | File carving & recovery tool | 📄 |
| [Bulk Extractor](tools/digital-forensics/bulk-extractor.md) | High-performance digital forensics tool | 📄 |
| [YARA](tools/digital-forensics/yara.md) | Pattern matching for malware research | 📄 |
| [Plaso](tools/digital-forensics/plaso.md) | Super timeline creation engine | 📄 |
| [Hashcat](tools/digital-forensics/hashcat.md) | Advanced password recovery | 📄 |

---

### ⚙️ Reverse Engineering

> *Understand the machine. Tear it apart. Rebuild it.*

Tools for binary analysis, disassembly, decompilation, debugging, and exploit development.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Ghidra](tools/reverse-engineering/ghidra.md) | NSA's software reverse engineering suite | 📄 |
| [IDA Pro](tools/reverse-engineering/ida-pro.md) | Interactive disassembler & debugger | 📄 |
| [Radare2](tools/reverse-engineering/radare2.md) | UNIX-like reverse engineering framework | 📄 |
| [GDB](tools/reverse-engineering/gdb.md) | GNU project debugger | 📄 |
| [x64dbg](tools/reverse-engineering/x64dbg.md) | Open-source x64/x32 debugger for Windows | 📄 |
| [OllyDbg](tools/reverse-engineering/ollydbg.md) | 32-bit assembler-level debugger | 📄 |
| [Binary Ninja](tools/reverse-engineering/binary-ninja.md) | Reverse engineering platform | 📄 |
| [Frida](tools/reverse-engineering/frida.md) | Dynamic instrumentation toolkit | 📄 |
| [Angr](tools/reverse-engineering/angr.md) | Binary analysis platform (symbolic execution) | 📄 |
| [Capstone](tools/reverse-engineering/capstone.md) | Lightweight multi-arch disassembly framework | 📄 |

---

### ☁️ Cloud Security

> *The cloud is someone else's computer — and it needs to be secured.*

Tools for AWS/Azure/GCP security auditing, misconfiguration detection, container security, and IAM analysis.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [ScoutSuite](tools/cloud-security/scoutsuite.md) | Multi-cloud security auditing tool | 📄 |
| [Prowler](tools/cloud-security/prowler.md) | AWS & Azure security assessment | 📄 |
| [Pacu](tools/cloud-security/pacu.md) | AWS exploitation framework | 📄 |
| [CloudSploit](tools/cloud-security/cloudsploit.md) | Cloud security configuration monitoring | 📄 |
| [Trivy](tools/cloud-security/trivy.md) | Comprehensive security scanner for containers | 📄 |
| [kube-hunter](tools/cloud-security/kube-hunter.md) | Kubernetes penetration testing tool | 📄 |
| [Checkov](tools/cloud-security/checkov.md) | Static analysis for IaC security | 📄 |
| [CloudMapper](tools/cloud-security/cloudmapper.md) | AWS environment visualization & auditing | 📄 |
| [Falco](tools/cloud-security/falco.md) | Cloud-native runtime security | 📄 |
| [Steampipe](tools/cloud-security/steampipe.md) | Universal cloud API query interface | 📄 |

---

### 🦠 Malware Analysis

> *Know your enemy. Dissect the threat.*

Tools for static analysis, dynamic analysis, sandboxing, unpacking, and threat intelligence.

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [Cuckoo Sandbox](tools/malware-analysis/cuckoo.md) | Automated malware analysis system | 📄 |
| [YARA](tools/malware-analysis/yara.md) | Pattern matching for malware researchers | 📄 |
| [PE-bear](tools/malware-analysis/pe-bear.md) | Portable Executable reversing tool | 📄 |
| [Detect It Easy](tools/malware-analysis/die.md) | Packer/compiler/linker detection | 📄 |
| [FLOSS](tools/malware-analysis/floss.md) | FireEye Labs obfuscated string solver | 📄 |
| [Remnux](tools/malware-analysis/remnux.md) | Linux toolkit for reverse-engineering malware | 📄 |
| [Process Monitor](tools/malware-analysis/procmon.md) | Advanced Windows system monitoring | 📄 |
| [Pestudio](tools/malware-analysis/pestudio.md) | Static malware initial assessment | 📄 |
| [Any.Run](tools/malware-analysis/anyrun.md) | Interactive online malware sandbox | 📄 |
| [Strings](tools/malware-analysis/strings.md) | Extract printable strings from binaries | 📄 |

---

### 🧩 Miscellaneous

> *Essential utilities that don't fit one category but are indispensable in every toolkit.*

| Tool | Description | Docs |
|:-----|:-----------|:----:|
| [CyberChef](tools/miscellaneous/cyberchef.md) | The cyber swiss army knife (data ops) | 📄 |
| [John the Ripper](tools/miscellaneous/john.md) | Password cracker | 📄 |
| [Hydra](tools/miscellaneous/hydra.md) | Network logon brute-force tool | 📄 |
| [Hashcat](tools/miscellaneous/hashcat.md) | Advanced GPU-based password recovery | 📄 |
| [Impacket](tools/miscellaneous/impacket.md) | Collection of Python classes for network protocols | 📄 |
| [SecLists](tools/miscellaneous/seclists.md) | Security tester's companion wordlists | 📄 |
| [PayloadsAllTheThings](tools/miscellaneous/payloadsallthethings.md) | Useful payloads & bypass techniques | 📄 |
| [Proxychains](tools/miscellaneous/proxychains.md) | Redirect connections through proxy servers | 📄 |
| [Tor](tools/miscellaneous/tor.md) | Anonymous communication network | 📄 |
| [SearchSploit](tools/miscellaneous/searchsploit.md) | CLI search for Exploit-DB | 📄 |

---

## ⭐ Featured Tools

<table>
  <tr>
    <td align="center" width="150">
      <br>
      <b>🔍 Nmap</b>
      <br>
      <sub>Network Scanner</sub>
      <br>
      <a href="tools/information-gathering/nmap.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🌐 Burp Suite</b>
      <br>
      <sub>Web Proxy</sub>
      <br>
      <a href="tools/web-security/burpsuite.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>💉 SQLMap</b>
      <br>
      <sub>SQL Injection</sub>
      <br>
      <a href="tools/web-security/sqlmap.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🛡️ Metasploit</b>
      <br>
      <sub>Exploit Framework</sub>
      <br>
      <a href="tools/network-security/metasploit.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🔬 Ghidra</b>
      <br>
      <sub>Reverse Engineering</sub>
      <br>
      <a href="tools/reverse-engineering/ghidra.md">Learn →</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="150">
      <br>
      <b>📡 Wireshark</b>
      <br>
      <sub>Packet Analysis</sub>
      <br>
      <a href="tools/network-security/wireshark.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🕵️ Sherlock</b>
      <br>
      <sub>OSINT Usernames</sub>
      <br>
      <a href="tools/osint/sherlock.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🚀 Nuclei</b>
      <br>
      <sub>Vuln Scanner</sub>
      <br>
      <a href="tools/web-security/nuclei.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>☁️ Prowler</b>
      <br>
      <sub>Cloud Security</sub>
      <br>
      <a href="tools/cloud-security/prowler.md">Learn →</a>
    </td>
    <td align="center" width="150">
      <br>
      <b>🧠 Volatility</b>
      <br>
      <sub>Memory Forensics</sub>
      <br>
      <a href="tools/digital-forensics/volatility.md">Learn →</a>
    </td>
  </tr>
</table>

---

## 🗺️ Learning Roadmap

> Follow this path to go from beginner to advanced. Each phase builds on the last.

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   Phase 1 ─── FOUNDATIONS                                        ║
║   ├── 🖥️  Linux Fundamentals & CLI Mastery                      ║
║   ├── 🌐  Networking (TCP/IP, DNS, HTTP, TLS)                   ║
║   ├── 🐍  Scripting (Python / Bash)                              ║
║   └── 🔐  Security Concepts (CIA Triad, OWASP Top 10)           ║
║                          │                                       ║
║                          ▼                                       ║
║   Phase 2 ─── RECONNAISSANCE & OSINT                             ║
║   ├── 🔍  Nmap, Masscan, Shodan                                 ║
║   ├── 🌍  Amass, Subfinder, theHarvester                        ║
║   ├── 🕵️  Sherlock, SpiderFoot, Maltego                         ║
║   └── 📡  Wireshark, Tcpdump                                    ║
║                          │                                       ║
║                          ▼                                       ║
║   Phase 3 ─── WEB APPLICATION SECURITY                           ║
║   ├── 🔓  Burp Suite, OWASP ZAP                                 ║
║   ├── 💉  SQLMap, XSStrike, Commix                              ║
║   ├── 📂  Gobuster, Ffuf, Dirsearch                             ║
║   └── 🚀  Nuclei, Nikto, WPScan                                 ║
║                          │                                       ║
║                          ▼                                       ║
║   Phase 4 ─── EXPLOITATION & POST-EXPLOITATION                   ║
║   ├── 🛡️  Metasploit Framework                                  ║
║   ├── 🔑  Hashcat, John the Ripper, Hydra                       ║
║   ├── 🔗  Impacket, Responder, Bettercap                        ║
║   └── ⚔️  Custom Exploit Development                             ║
║                          │                                       ║
║                          ▼                                       ║
║   Phase 5 ─── ADVANCED SPECIALIZATION                            ║
║   ├── ⚙️  Ghidra, Radare2, Frida (Reverse Engineering)          ║
║   ├── 🦠  Cuckoo, YARA, Remnux (Malware Analysis)              ║
║   ├── ☁️  Prowler, ScoutSuite, Pacu (Cloud Security)            ║
║   └── 🔬  Volatility, Autopsy, Plaso (Digital Forensics)        ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

### 🎯 Certification Alignment

| Phase | Recommended Certifications |
|:------|:--------------------------|
| Phase 1–2 | CompTIA Security+, CEH |
| Phase 3 | eWPT, BSCP (Burp Suite Certified Practitioner) |
| Phase 4 | OSCP, CRTP |
| Phase 5 | GREM, GCFA, CCSP, OSED |

---

## 📅 Daily Tool Updates

> A new tool is documented every day. Track progress below.

<!--
  UPDATE THIS SECTION as you add new tools.
  Format: | Date | Tool | Category | Status |
-->

| Date | Tool | Category | Status |
|:-----|:-----|:---------|:------:|
| 2026-06-03 | Nmap | Information Gathering | ✅ |
| 2026-06-04 | Burp Suite | Web Security | 🔜 |
| 2026-06-05 | SQLMap | Web Security | 🔜 |
| 2026-06-06 | Sherlock | OSINT | 🔜 |
| 2026-06-07 | Wireshark | Network Security | 🔜 |
| 2026-06-08 | Metasploit | Network Security | 🔜 |
| 2026-06-09 | Ghidra | Reverse Engineering | 🔜 |

<p align="center">
  <i>✅ Complete &nbsp;│&nbsp; 🔜 Upcoming &nbsp;│&nbsp; 📝 In Progress</i>
</p>

---

## 🤝 Contributing

Contributions are what make the open-source community an incredible place to learn and grow. **All contributions are welcome!**

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b tool/your-tool-name
   ```
3. **Use the template** — copy [`templates/tool-template.md`](templates/tool-template.md) and fill it out
4. **Place your file** in the correct category folder under `tools/`
5. **Update** `README.md` to add your tool to the category table
6. **Commit** your changes
   ```bash
   git commit -m "docs: add [tool-name] to [category]"
   ```
7. **Push** and open a **Pull Request**

### Contribution Guidelines

| Rule | Description |
|:-----|:-----------|
| 📝 **Use the template** | Every tool page must follow [tool-template.md](templates/tool-template.md) |
| ✅ **Legal tools only** | Document tools for authorized security testing only |
| 🎯 **Quality over quantity** | Thorough documentation beats placeholder pages |
| 🔍 **Verify commands** | Test every command before documenting it |
| 📚 **Cite sources** | Link to official docs and references |

> **⚠️ Disclaimer:** This repository is for **educational and authorized security testing purposes only.** Unauthorized access to computer systems is illegal. Always obtain proper authorization before testing.

---

## 💖 Support

If this project helps your cybersecurity journey, consider supporting it:

<p align="center">
  <a href="https://github.com/mitro/hacking-tools/stargazers">
    <img src="https://img.shields.io/badge/⭐_Star_This_Repo-0d1117?style=for-the-badge&logo=github&logoColor=white" alt="Star This Repo" />
  </a>
  &nbsp;
  <a href="https://github.com/mitro/hacking-tools/fork">
    <img src="https://img.shields.io/badge/🍴_Fork_&_Contribute-0d1117?style=for-the-badge&logo=git&logoColor=white" alt="Fork & Contribute" />
  </a>
  &nbsp;
  <a href="https://github.com/mitro/hacking-tools/issues">
    <img src="https://img.shields.io/badge/🐛_Report_Issues-0d1117?style=for-the-badge&logo=github&logoColor=white" alt="Report Issues" />
  </a>
</p>

### 🌟 Share the Knowledge

```
If you find this useful, share it with someone who's learning cybersecurity.
Knowledge grows when shared. 🚀
```

---

<p align="center">
  <img src="https://img.shields.io/badge/Built_with-❤️_&_☕-0d1117?style=flat-square" alt="Built with Love" />
  <br><br>
  <b>Made for the cybersecurity community, by the cybersecurity community.</b>
  <br>
  <sub>© 2026 Hacking Tools • Educational Use Only • <a href="https://github.com/mitro/hacking-tools/blob/main/LICENSE">MIT License</a></sub>
  <br><br>
  <a href="#️-hacking-tools">⬆ Back to Top</a>
</p>
