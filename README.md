<!-- ============ ANIMATED WAVE HEADER ============ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1021,50:1a2a6c,100:8A2BE2&height=230&section=header&text=Ankit%20Singh&fontColor=ffffff&fontSize=62&fontAlignY=36&desc=SOC%20Analyst%20|%20Threat%20Hunter%20|%20Detection%20Engineer&descAlignY=58&descSize=18&animation=fadeIn"/>

<!-- ============ TYPING SUBTITLE ============ -->
<p align="center">
  <a href="https://github.com/ExelR8ight">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8A2BE2&center=true&vCenter=true&width=820&lines=Telemetry+%E2%86%92+Detection-as-Code+%E2%86%92+ML+Triage+%E2%86%92+SOAR;Building+end-to-end+AI-powered+SOC+pipelines;MITRE+ATT%26CK+mapped+%7C+Atomic+Red+Team+validated;Hunting+APT29+%26+FIN7+tradecraft+in+the+lab;Securing+LLM+agents+against+prompt+injection" alt="Typing SVG" />
  </a>
</p>

<!-- ============ NEON CYBER LINE ============ -->
<img width="100%" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="cyber line"/>

<!-- ============ BADGES + SOCIALS ============ -->
<p align="center">
  <img src="https://img.shields.io/badge/Focus-Security%20Operations-blue?style=for-the-badge&logo=elastic&logoColor=white">
  <img src="https://img.shields.io/badge/Specialty-Detection%20Engineering-red?style=for-the-badge&logo=splunk&logoColor=white">
  <img src="https://img.shields.io/badge/Framework-MITRE%20ATT%26CK-E02401?style=for-the-badge&logo=mitre&logoColor=white">
  <img src="https://img.shields.io/badge/Research-AI%20Security-8A2BE2?style=for-the-badge&logo=openai&logoColor=white">
</p>
<p align="center">
  <a href="https://linkedin.com/in/ankit-singh-1b0632265"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:ankisinsen152@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <img src="https://komarev.com/ghpvc/?username=ExelR8ight&style=flat-square&color=8A2BE2&label=Profile+Views">
  <img src="https://img.shields.io/github/followers/ExelR8ight?style=flat-square&color=8A2BE2&label=Followers">
</p>

<!-- ============ LIVE DEV QUOTE (changes every reload) ============ -->
<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote"/>
</p>

<img width="100%" src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif">

## 👤 Whoami

<img align="right" width="300" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" alt="hacker terminal mascot"/>
I am a cybersecurity professional specializing in **Security Operations (SOC)**, **Threat Detection**, and **Incident Response**. I focus on moving beyond traditional, noisy signature-based alerts by building robust, end-to-end detection pipelines that leverage behavioral analytics and automation to drastically reduce alert fatigue.

> *"Security isn't just about detecting everything; it's about detecting what matters and automating the rest."*

---

## 🛠️ Technical Stack & Tools

| **Category** | **Technologies & Frameworks** |
|:---:|:---|
| 📡 **SIEM & Log Management** | `Splunk Enterprise`, `Splunk HEC`, `Elastic (ELK) Stack` |
| 🛡️ **Endpoint & Network Telemetry** | `Sysmon (SwiftOnSecurity)`, `Suricata IDS`, `Windows Event Logs` |
| 🎯 **Threat Detection & Intelligence** | `MITRE ATT&CK`, `Sigma Rules`, `Atomic Red Team`, `YARA` |
| ⚙️ **Automation & SOAR** | `TheHive`, `Python`, `PowerShell`, `Bash` |
| 🧠 **Data Analysis & ML** | `Scikit-Learn (Isolation Forest)`, `Pandas`, `NumPy` |

---

## 🏆 Featured Portfolio Projects

### 🧠 [CogniSOC: End-to-End AI-Powered SOC Architecture](https://github.com/ExelR8ight/CogniSOC)
<img src="https://img.shields.io/badge/Status-Live-success?style=flat-square"> <img src="https://img.shields.io/badge/Tech-Splunk_|_Python_|_TheHive-black?style=flat-square">

My flagship project. A complete, production-ready SOC pipeline built from scratch to solve alert fatigue. 
- **The Challenge:** Traditional rule-based SIEMs generate too much noise.
- **The Solution:** An unsupervised **Isolation Forest** ML model that scores behavioral anomalies, routes them through a 6-rule MITRE ATT&CK correlation engine, and automatically escalates high-fidelity incidents to TheHive (SOAR).
- **The Result:** Achieved an **88% Precision** rate and **reduced alert volume by 75%** during a 100-hour live traffic simulation.

<details>
<summary><b>View Architecture Flowchart</b></summary>

```mermaid
graph LR
    A[Sysmon & Suricata] -->|Universal Forwarder| B[Splunk Indexer]
    B -->|REST API| C[Isolation Forest ML Engine]
    C -->|Anomaly Scoring| D{Correlation Engine}
    D -->|Low Severity| E[Drop / Suppress]
    D -->|High Severity| F[TheHive SOAR API]
    F --> G[Analyst Triage]
```

</details>

### 🛡️ [ATT&CK-Mapped Detection Library](https://github.com/ExelR8ight/ATT-CK-Detection-Library)
<img src="https://img.shields.io/badge/Status-Live-success?style=flat-square"> <img src="https://img.shields.io/badge/Tech-Sigma_|_Atomic_Red_Team-blue?style=flat-square">

A version-controlled "Detection-as-Code" repository demonstrating true detection engineering maturity. 
- Contains **13 highly tuned Sigma rules** spanning 6 MITRE ATT&CK tactics.
- Fully translated to **Splunk SPL** and **Elastic DSL**.
- Validated via **Atomic Red Team** execution.
- **Business Value:** Features rigorous "False-Positive Tuning" notes (e.g., tuning out SCCM or vulnerability scanners) to show real-world operational maturity and noise reduction.

### 🔍 [Threat Hunting & Incident Investigation Lab](https://github.com/ExelR8ight/Threat-Hunting-Lab)
<img src="https://img.shields.io/badge/Status-Live-success?style=flat-square"> <img src="https://img.shields.io/badge/Tech-IR_Playbooks_|_Splunk-orange?style=flat-square">

A collection of 7 structured, end-to-end incident investigations mimicking real-world APT tradecraft (like **APT29** and **FIN7**).
- Covers PowerShell Empire C2, Data Exfiltration, Lateral Movement via PsExec, and Credential Dumping via LSASS.
- Includes structured Incident Response playbooks, extracted IOCs, and proactive threat hunting hypotheses.

### 💉 [LogPrompt-Inject: LLM SOC Triage Vulnerabilities](https://github.com/ExelR8ight/LogPrompt-Inject)
<img src="https://img.shields.io/badge/Status-Under_Review-yellow?style=flat-square"> <img src="https://img.shields.io/badge/Venue-ACM_AISec-00529B?style=flat-square"> <img src="https://img.shields.io/badge/Tech-Python_|_Ollama-blue?style=flat-square">

My latest AI-Security research project, currently **Under Review at ACM AISec @ CCS**.
- **The Research:** A systematic evaluation of indirect prompt injection attacks against LLM-powered SOC triage engines via malicious log telemetry (e.g. Sysmon `CommandLine`, Suricata `http_user_agent`).
- **The Findings:** Discovered *Defense Portability Failure* and *Defense Backfire* across 6 open-weight models and 3 frontier API models, proving that defenses which secure one model often worsen another under identical conditions.
- **The Value:** Demonstrates advanced capability in AI Security (AppSec), LLM threat modeling, and rigorous empirical research methodology.

### 🤖 [LLM-Assisted SOC Alert Triage (Injection-Hardened)](https://github.com/ExelR8ight/LLM-Assisted-Alert-Triage)
<img src="https://img.shields.io/badge/Status-Live-success?style=flat-square"> <img src="https://img.shields.io/badge/Tech-Python_|_Ollama-blue?style=flat-square">

An automated AI triage copilot that uses local LLMs to classify raw Sysmon/Suricata alerts, expressly built to resist prompt injection.
- **The Engine:** Ingests raw telemetry and outputs a strict JSON triage summary (Severity, MITRE ATT&CK Mapping, and Next Steps).
- **The Security Layer:** Applies the findings from my LogPrompt-Inject research in practice. It intercepts incoming logs, applies Spotlighting (data-marking), and enforces rigorous schema validation to neutralize injected malicious instructions before the LLM processes them.
- **The Value:** Proves I can not only find vulnerabilities in agentic AI systems, but I can architect and engineer the programmatic solutions to secure them.

---

## 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/ExelR8ight">
    <img src="https://github-readme-stats.vercel.app/api?username=ExelR8ight&show_icons=true&theme=tokyonight&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="GitHub Stats" width="48%"/>
  </a>
  <a href="https://github.com/ExelR8ight">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=ExelR8ight&theme=tokyonight&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9" alt="GitHub Streak" width="48%"/>
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ExelR8ight&layout=compact&theme=tokyonight&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages"/>
</p>
</p>
