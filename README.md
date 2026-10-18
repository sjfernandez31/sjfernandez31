<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:003b1f,100:00FF41&height=230&section=header&text=STEVEN%20J.%20FERNANDEZ&fontSize=44&fontColor=00FF41&fontAlign=50&fontAlignY=38&animation=fadeIn&desc=IT%20Support%20%7C%20Cybersecurity%20%7C%20Blue%20Team%20Operations&descSize=17&descAlignY=60&descColor=c9d1d9" alt="Steven J. Fernandez banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1200&color=00FF41&center=true&vCenter=true&width=760&lines=Initializing+operator+profile...;Loading+credentials...+Security%2B+verified;Mounting+home+labs...+2+repos+online;Access+granted.;Protect+the+system.+Support+the+user.+Document+everything." alt="Typing SVG" />

<br/>

**`[ CompTIA A+ | Network+ | Security+ | CIOS | ITIL 4 | WGU B.S. Cybersecurity — In Progress ]`**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Steven%20Fernandez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stevenjfernandez31)
[![GitHub](https://img.shields.io/badge/GitHub-sjfernandez31-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sjfernandez31)
[![AegisOS](https://img.shields.io/badge/AegisOS-Live%20Platform-00FF41?style=for-the-badge&logo=vercel&logoColor=black)](https://aegis-os-orcin.vercel.app)
[![Resume](https://img.shields.io/badge/Resume-Download-C0562B?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/sjfernandez31/sjfernandez31/raw/main/IT%20Tech%20Resume.pdf)

</div>

---

## `〈 SYSTEM INFO 〉`

```
┌──(steven㉿fernandez)-[~]
└─$ neofetch

▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄  steven@fernandez
███████ ███████  ────────────────────────────────────────────────
███████ ███████  Role    : Entry-Level IT Support · Cybersecurity Student
 █████████████   Certs   : A+ · Net+ · Security+ · CIOS · ITIL 4
  ███████████    Degree  : B.S. Cybersecurity & IA, WGU (Dec 2027)
   █████████     Lab     : VMware · Kali · Windows Server 2022 · AD
    ▀█████▀      Langs   : English · Spanish
      ▀█▀        Status  : Open to work · NJ / Remote
```

```
┌──(steven㉿fernandez)-[~]
└─$ ./status.sh

  BLUE TEAM LAB    ██████░░░░   13 / 21 exercises complete
  IT SUPPORT LAB   ████████░░   10 / 12 labs complete

  CERTS EARNED     ✔ A+   ✔ Network+   ✔ Security+   ✔ CIOS   ✔ ITIL 4
  EDUCATION        ✔ A.S. (OCC, Summa Cum Laude, 3.907 GPA)   ▸ B.S. (WGU, in progress)
  NOW BUILDING     ▸ Digital forensics set (Autopsy, Volatility, Windows artifacts, dd)
```

**What sets me apart:**

- 🛡️ **Bilingual (EN/ES)**, able to support diverse user bases in two languages
- 🖥️ **Active home lab operator**, Windows Server 2022 AD environments and VMware, with documented labs across two repos
- ⚡ **AegisOS builder**, deployed a live 16-tool AI-powered cybersecurity platform (GPT-4o + Vercel), built while studying for Security+
- 📋 **Compliance-trained**, PCI DSS, ServiceNow ticketing, and VoIP support at ACD Direct
- 🔐 **Blue Team mindset**, Nmap scanning, Hydra brute-force defense, Wireshark PCAP analysis, Wazuh SIEM, SigmaHQ detection rules, and forensics with Autopsy
- 📦 **CDL-A background**, DOT, ELD, and FMCSR compliance translates directly into process discipline

---

## `〈 LAB ARCHITECTURE 〉`

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0d1117','primaryTextColor':'#00FF41','primaryBorderColor':'#00FF41','lineColor':'#00FF41','secondaryColor':'#161b22','tertiaryColor':'#0d1117','clusterBkg':'#0d1117','clusterBorder':'#00FF41'}}}%%
flowchart LR
    subgraph HOST["🖥️ Windows 11 Host · VMware Workstation Pro 26H1"]
        direction LR
        K["🐉 Kali Linux 2026.1<br/><b>ATTACKER</b><br/>192.168.10.101"]
        S["🏢 Windows Server 2022<br/><b>DEFENDER · Domain Controller</b><br/>support.local · 192.168.10.20"]
        C["💻 Windows 10 Pro Client<br/><b>ITClient</b><br/>IT Support Lab"]
        K <-->|"labnetwork · isolated LAN segment · no internet"| S
        S -.->|"domain joined"| C
    end
```

---

## `〈 CAREER PATH 〉`

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0d1117','primaryTextColor':'#c9d1d9','primaryBorderColor':'#00FF41','lineColor':'#00FF41'}}}%%
flowchart LR
    A["🚛 CDL-A Driver<br/>10 yrs logistics"] --> B["📜 A+ · Net+ · CIOS<br/>ITIL 4"]
    B --> C["🎓 A.S. Computer Science<br/>Ocean County College"]
    C --> D["🔐 Security+<br/>Aug 2026"]
    D --> E["🖥️ IT Support / Help Desk<br/><b>targeting now</b>"]
    E --> F["🛡️ SOC / Security Analyst"]
    F --> G["☁️ Cloud Security Engineer<br/><b>long term</b>"]

    classDef done fill:#0d1117,stroke:#00FF41,color:#00FF41,stroke-width:2px;
    classDef now fill:#003b1f,stroke:#00FF41,color:#ffffff,stroke-width:3px;
    classDef next fill:#0d1117,stroke:#8b949e,color:#8b949e,stroke-dasharray: 5 5;
    class A,B,C,D done;
    class E now;
    class F,G next;
```

---

## `〈 MISSION FILES — LIVE PROJECTS 〉`

### 🟢 AEGIS OS — AI CYBERSECURITY PLATFORM
> ⚡ *A live 16-tool AI-powered cybersecurity platform, recognized by Handshake's official LinkedIn*

A live web application powered by GPT-4o with tools covering threat analysis, log parsing, CVE lookup, phishing detection, network recon, and more. Built as a Handshake project using AI-assisted development with OpenAI Codex CLI and deployed on Vercel. I built the tools around the concepts I was studying, so it doubled as hands-on prep for my Security+ exam.

`GPT-4o` `OpenAI API` `Vercel` `JavaScript` `Prompt Engineering` `Cybersecurity`

[![View Live](https://img.shields.io/badge/▶_LIVE_DEMO-aegis--os--orcin.vercel.app-00FF41?style=for-the-badge&logo=vercel&logoColor=black)](https://aegis-os-orcin.vercel.app)
[![View Repo](https://img.shields.io/badge/▶_VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sjfernandez31/AegisOS)

---

### 🔵 BLUE TEAM HOME LAB
> ⚡ *Defender-side detection, analysis, and response, built to simulate real SOC workflows*

Structured blue team exercises in an isolated VMware environment with a Kali Linux attacker and a Windows Server 2022 defender. 13 exercises complete, each documented as a professional technical report. A digital forensics set (Autopsy, Volatility, Windows artifacts, dd) and a security assessment set are next.

`Nmap` `Hydra` `Wireshark` `Wazuh` `SigmaHQ` `Autopsy` `Windows Event Logs` `VMware Workstation` `Incident Response`

<details>
<summary><b>📂 View completed exercises (13)</b></summary>

<br/>

| # | Exercise | Status |
|---|----------|--------|
| 01 | Lab Setup, Environment Configuration | ✅ |
| 02 | Nmap Network Scan | ✅ |
| 03 | Hydra Brute Force Attack | ✅ |
| 04 | Wireshark Traffic Analysis | ✅ |
| 05 | Active Directory Attack and Defend | ✅ |
| 06 | Home SIEM with Wazuh | ✅ |
| 07 | SigmaHQ Detection Rules | ✅ |
| 08 | Honeypot Deployment and Analysis | ✅ |
| 09 | PCAP Analysis | ✅ |
| 10 | Incident Response Playbook | ✅ |
| 11 | Phishing Email Analysis | ✅ |
| 12 | Vulnerability Scan and Report | ✅ |
| 17 | Digital Forensics Capstone | ✅ |

</details>

[![View Repo](https://img.shields.io/badge/▶_VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sjfernandez31/Blue-Team-Home-Lab)

---

### 🟡 IT SUPPORT HOME LAB — ACTIVE DIRECTORY & WINDOWS SERVER
> ⚡ *A full enterprise-style AD environment built from scratch and documented as technical manuals*

Windows Server 2022 as a domain controller (`support.local`) with a Windows 10 Pro client, and every lab documented as a technical manual. 10 labs complete covering Active Directory, DNS and DHCP, Group Policy, osTicket ticketing, Event Viewer, and password resets. Backup and Restore and Printer Deployment labs are next.

`Windows Server 2022` `Active Directory` `VMware Workstation Pro` `Group Policy` `DNS` `DHCP` `osTicket` `PowerShell`

[![View Repo](https://img.shields.io/badge/▶_VIEW_REPOSITORY-181717?style=for-the-badge&logo=github)](https://github.com/sjfernandez31/it-support-home-lab)

---

## `〈 TECH ARSENAL 〉`

<div align="center">

<img src="https://skillicons.dev/icons?i=windows,linux,kali,powershell,bash,python,js,azure,vercel,github,git,vscode&theme=dark" alt="Tech icons" />

</div>

<details>
<summary><b>🔧 Full tool list</b></summary>

<br/>

**🔒 Security & Defense**

![Nmap](https://img.shields.io/badge/Nmap-00FF41?style=flat-square&logoColor=black)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-FF0000?style=flat-square&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logoColor=white)
![SigmaHQ](https://img.shields.io/badge/SigmaHQ-4A5568?style=flat-square&logoColor=white)
![Autopsy](https://img.shields.io/badge/Autopsy-2D3748?style=flat-square&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C0562B?style=flat-square&logoColor=white)
![Windows Defender](https://img.shields.io/badge/Windows%20Defender-0078D4?style=flat-square&logo=windows&logoColor=white)
![Policy Analyzer](https://img.shields.io/badge/Policy%20Analyzer-FF6B35?style=flat-square&logoColor=white)

**🖥️ Infrastructure & OS**

![Windows Server](https://img.shields.io/badge/Windows%20Server%202022-0078D4?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active%20Directory-003399?style=flat-square&logoColor=white)
![VMware](https://img.shields.io/badge/VMware%20Workstation-607078?style=flat-square&logo=vmware&logoColor=white)
![Windows 10](https://img.shields.io/badge/Windows%2010-0078D4?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**🎫 Ticketing & ITSM**

![ServiceNow](https://img.shields.io/badge/ServiceNow-00C389?style=flat-square&logo=servicenow&logoColor=white)
![osTicket](https://img.shields.io/badge/osTicket-1F6FB2?style=flat-square&logoColor=white)
![ITIL 4](https://img.shields.io/badge/ITIL%204-6B2D8B?style=flat-square&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)

**💻 Languages & Scripting**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**☁️ Cloud & AI**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

</details>

---

## `〈 CREDENTIALS & CLEARANCES 〉`

<div align="center">

![A+](https://img.shields.io/badge/A%2B-CERTIFIED-FF0000?style=for-the-badge&logoColor=white)
![Network+](https://img.shields.io/badge/Network%2B-CERTIFIED-FF0000?style=for-the-badge&logoColor=white)
![Security+](https://img.shields.io/badge/Security%2B-CERTIFIED-FF0000?style=for-the-badge&logoColor=white)
![CIOS](https://img.shields.io/badge/CIOS-CERTIFIED-FF0000?style=for-the-badge&logoColor=white)
![ITIL 4](https://img.shields.io/badge/ITIL%204%20Foundation-CERTIFIED-6B2D8B?style=for-the-badge&logoColor=white)

![WGU](https://img.shields.io/badge/B.S.%20Cybersecurity-WGU%20%7C%20Dec%202027-003366?style=for-the-badge&logoColor=white)
![OCC](https://img.shields.io/badge/A.S.%20General%20Studies%20(CS)-OCC%20%7C%202026%20%7C%20Summa%20Cum%20Laude%20%7C%203.907%20GPA-006633?style=for-the-badge&logoColor=white)

</div>

---

## `〈 OPERATIONAL HISTORY 〉`

```
🟢  AI PROMPT TRAINER — Handshake (Contract)
    2025 – Present
    Training AI models via structured prompt evaluation and feedback pipelines.

🔵  CUSTOMER SUPPORT & COMPLIANCE SPECIALIST — ACD Direct (Contract)
    Jul 2025 – Jun 2026
    ServiceNow ticketing · PCI DSS compliance · VoIP support · Microsoft 365

🟡  LOGISTICS & COMPLIANCE OPERATOR — Penske Logistics / Cardinal Logistics
    Jan 2015 – Dec 2025
    DOT · ELD · FMCSR compliance · SLA-driven ops · technical documentation

🎓  B.S. Cybersecurity & Information Assurance — WGU (Expected Dec 2027)
🎓  A.S. General Studies (CS Concentration) — Ocean County College (2026) — Summa Cum Laude | 3.907 GPA
```

---

## `〈 FUTURE MISSION QUEUE 〉`

```
╔═ OPERATION: NEXT LEVEL ═══════════════════════════════════════
║
║  🟢  Blue Team Ex. 13-16    Digital forensics set
║  🔵  Blue Team Ex. 18-21    Security assessment and reviews
║  🟡  IT Support Lab         Backup/Restore, Printer Deployment
║  🔵  WGU B.S. Cybersecurity Expected Dec 2027
║  🟡  CySA+ / CEH            Mid-term cert roadmap
║  🟢  Land IT Support Role   NJ in-person or remote
║
╚═══════════════════════════════════════════════════════════════
```

---

## `〈 LIVE STATS DASHBOARD 〉`

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=sjfernandez31&theme=terminal&hide_border=true&background=0d1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&dates=00FF41&sideLabels=00FF41&sideNums=00FF41&stroke=00FF41)](https://git.io/streak-stats)

<img height="170" src="https://github-readme-stats.vercel.app/api?username=sjfernandez31&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&icon_color=00FF41&text_color=c9d1d9" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sjfernandez31&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FF41&text_color=c9d1d9" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sjfernandez31&bg_color=0d1117&color=00FF41&line=00FF41&point=FFFFFF&area=true&area_color=00FF41&hide_border=true" alt="Contribution activity graph" />

</div>

---

## `〈 MISSION STATEMENT 〉`

> *"I came from a decade behind the wheel, where one missed inspection could end my career or a life. That discipline is what I bring to IT. Every ticket matters. Every system matters. Every user matters. I'm not here to pass certs, I'm here to build things that work and protect the people who depend on them."*

---

## `〈 ESTABLISH CONNECTION 〉`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stevenjfernandez31)
[![AegisOS](https://img.shields.io/badge/Try%20AegisOS%20Live-00FF41?style=for-the-badge&logo=vercel&logoColor=black)](https://aegis-os-orcin.vercel.app)
[![GitHub](https://img.shields.io/badge/Explore%20My%20Repos-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sjfernandez31)

<br/>

![Visitor Count](https://komarev.com/ghpvc/?username=sjfernandez31&color=00FF41&style=flat-square&label=PROFILE+VIEWS)

<br/>

<sub><code>[ STATUS: ACTIVE OPERATOR — BUILDING IN PUBLIC — OPEN TO OPPORTUNITIES ]</code></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:003b1f,100:00FF41&height=120&section=footer" alt="footer" />

</div>
