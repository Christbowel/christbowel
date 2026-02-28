<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=christbowel&fontSize=70&fontColor=00d4ff&animation=fadeIn&fontAlignY=38&desc=Security%20Researcher%20%7C%20CVE%20Hunter%20%7C%20TU%20Darmstadt&descAlignY=60&descColor=8b949e"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Offensive+Security+%26+Vulnerability+Research;3+CVEs+Discovered+%7C+4+Hall+of+Fames;Top+15%2F454+%E2%80%94+Bugcrowd+Black+Hat+CTF+2024;Breaking+Things+to+Make+Them+Stronger)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-christbowel-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/christbowel)
[![Website](https://img.shields.io/badge/Website-christbowel.com-00d4ff?style=for-the-badge&logo=googlechrome&logoColor=white)](https://christbowel.com/about)
[![HackerOne](https://img.shields.io/badge/HackerOne-christbowel-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/christbowel)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-christbowel-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/christbowel)

[![TryHackMe](https://img.shields.io/badge/TryHackMe-chrisbowel-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/chrisbowel)
[![Root-Me](https://img.shields.io/badge/Root--Me-christbowel-2E2E2E?style=for-the-badge&logo=linux&logoColor=white)](https://www.root-me.org/christbowel)
[![Profile Views](https://komarev.com/ghpvc/?username=christbowel&style=for-the-badge&color=00d4ff&label=PROFILE+VIEWS)](https://github.com/christbowel)

</div>

---

## `whoami`

```
┌──(christbowel㉿kali)-[~]
└─$ cat about.txt

  Name     : Christ Bowel Bouchuen
  Age      : 19
  Location : Darmstadt, Germany
  Uni      : TU Darmstadt — B.Sc. Computer Science
  Focus    : Offensive Security | Vulnerability Research | Bug Bounty

  CVEs Discovered  : 3
  Hall of Fames    : 4 (🇺🇸 California · 🇺🇸 BIA · 🇦🇺 RMIT · 🌍 Mars VDP)
  CTF Best Rank    : Top 15/454 — Bugcrowd Black Hat USA CTF 2024
  Status           : Open for Werkstudent (Pentest / Vuln Research · Darmstadt/Frankfurt)
```

---

## 🔴 CVEs Discovered

<table>
<tr>
<td width="50%">

### CVE-2024-29643 - Croogo CMS v3.0.2
**Host Header Injection → RCE**

Exploitable Host Header Injection in the `feed.rss` component allows injection of arbitrary PHP code via a malicious HTTP `Host` header - leading to **full system compromise**.

[![NVD](https://img.shields.io/badge/NVD-CVE--2024--29643-red?style=flat-square)](https://nvd.nist.gov/vuln/detail/CVE-2024-29643)

</td>
<td width="50%">

### CVE-2026-25050 - Vendure 
**Authentication Timing Attack → Username Enumeration**

Timing side-channel in the authentication flow enabling remote username enumeration - discovered and responsibly disclosed.

`Authentication Bypass` · `Timing Attack` · `Username Enum`

[![NVD](https://img.shields.io/badge/NVD-CVE--2025--25050-red?style=flat-square)](https://github.com/advisories/GHSA-6f65-4fv2-wwch)

</td>
</tr>
</table>

---

## 🔵 CVE Contributions & Community Work

| CVE | Target | Contribution |
|-----|--------|-------------|
| [CVE-2023-25136](https://nvd.nist.gov/vuln/detail/CVE-2023-25136) | OpenSSH 9.1 | Python mass scanner + exploit framework — widely adopted by the community |
| [CVE-2024-25600](https://nvd.nist.gov/vuln/detail/CVE-2024-25600) | WordPress Bricks Builder | Official **Nuclei template** (2 versions) merged by ProjectDiscovery |

---

## 🏆 Hall of Fame

<div align="center">

| Organization | Finding | Year |
|---|---|---|
| 🏛️ **State of California** · via Bugcrowd | SQL Injection → RCE → `NT AUTHORITY\SYSTEM` | 2024 |
| 🏛️ **Bureau of Indian Affairs (BIA)** | Multiple critical vulnerabilities on federal systems | 2023 |
| 🌍 **Mars Vulnerability Disclosure Program** | IDOR + Client Information Disclosure + Client-Side Validation Bypass | 2025 |
| 🎓 **RMIT University** · Australia | Responsible disclosure | 2023 |

</div>

---

## ⚒️ Projects

<table>
<tr>
<td width="50%">

### 🔥 [Infiltrator](https://github.com/christbowel/infiltrator)
**Red Team Input Monitoring Framework** · `Go`

Stealthy input surveillance tool for security research. Captures keystrokes, clipboard data, screenshots, and system info — exfiltrates securely via Telegram bot.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

</td>
<td width="50%">

### 🔑 [CipherBuster](https://github.com/Christbowel/CipherBuster)
**RSA Exploitation Framework** · `Python`

Analyzes and exploits weak RSA keys via factorization attacks and weak key detection. Built for CTFs and real-world pentest scenarios.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### 🛡️ RedTeamer
**Offensive Simulation Toolkit**

Payload generators, privilege escalation helpers, persistence techniques — full adversary simulation framework.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</td>
<td width="50%">

### 🔵 BlueTeamer
**Defensive Analysis Companion**

Log analysis, anomaly detection, and automated detection rule generation. The defensive counterpart to RedTeamer.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

---

## 🧰 Skills & Arsenal

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Tools**

![BurpSuite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=portswigger&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-00D4FF?style=for-the-badge&logo=go&logoColor=black)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=for-the-badge&logo=nsa&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Domains**

`Web Security` · `API Penetration Testing` · `Active Directory` · `Network Security`
`Exploit Development` · `Reverse Engineering` · `Cryptanalysis` · `Bug Bounty` · `CTFs`

---

## 📜 Certifications

| Certification | Issuer | Date |
|---|---|---|
| usd Hacking Night – Ethical Hacking Skills | usd AG | Nov. 2025 |
| Certified AppSec Practitioner (CAP) | The SecOps Group | Feb. 2023 |
| API Security Penetration Testing | APIsec University | Jan. 2024 |
| CompTIA PenTest+ Learning Path | TryHackMe | Apr. 2023 |
| AZ-500: Securing Data & Applications | Microsoft | Apr. 2023 |

> 🥇 **1st Place** — usd Hacking Night CTF, Nov. 2025

---

## 📊 Stats

<div align="center">

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=christbowel&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00d4ff&fire=00d4ff&currStreakLabel=00d4ff)](https://git.io/streak-stats)

<br/>

### 📈 Activity Graph

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=christbowel&theme=react-dark&hide_border=true&bg_color=0d1117&color=00d4ff&line=00d4ff&point=ffffff&area=true&area_color=00d4ff)](https://github.com/ashutosh00710/github-readme-activity-graph)

<br/>

---

## ♟️ Chess move of the day

<div align="center">

[![Chess.com](https://img.shields.io/badge/Chess.com-christbowel-769656?style=for-the-badge&logo=chess.com&logoColor=white)](https://www.chess.com/member/christbowel)

> *Schach Club · TU Darmstadt* ♟️

</div>

---

## 💬 Quote

<div align="center">

[![Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=The+quieter+you+become%2C+the+more+you+can+hear&author=Kali+Linux)](https://github.com/piyushsuthar/github-readme-quotes)

</div>

---

## 🌍 Langues

<div align="center">

| 🇫🇷 Français | 🇩🇪 Deutsch | 🇬🇧 English |
|:---:|:---:|:---:|
| Langue maternelle | C1 Fließend | Fluent |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer"/>

*"Security is not a product, but a process."*

</div>
