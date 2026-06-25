<!-- ===================== BANNER ===================== -->
<p align="center">
  <img src="assets/banner.png" width="100%" alt="Ankit Singh — Security Operations & Detection Engineering">
</p>

<h1 align="center">Ankit Singh</h1>
<h3 align="center">🛡️ SOC Analyst · 🎯 Threat Hunter · ⚙️ Detection Engineer</h3>

<p align="center">
  <em>Building end-to-end, AI-powered detection pipelines — from raw telemetry to automated SOAR response.</em>
</p>

<!-- ===================== TOP BADGES ===================== -->
<p align="center">
  <img src="https://img.shields.io/badge/Focus-Security%20Operations-blue?style=for-the-badge&logo=elastic&logoColor=white">
  <img src="https://img.shields.io/badge/Specialty-Detection%20Engineering-red?style=for-the-badge&logo=splunk&logoColor=white">
  <img src="https://img.shields.io/badge/Framework-MITRE%20ATT%26CK-E02401?style=for-the-badge&logo=mitre&logoColor=white">
  <img src="https://img.shields.io/badge/Interest-AI%20Security-8A2BE2?style=for-the-badge&logo=openai&logoColor=white">
</p>

<p align="center">
  <a href="https://linkedin.com/in/ankit-singh-1b0632265"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:ankisinsen152@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <img src="https://komarev.com/ghpvc/?username=ExelR8ight&style=flat-square&color=blue" alt="Profile views">
</p>

---

## 👤 Whoami

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

---

## 🚧 Currently Building / Coming Soon

I am actively researching and building in the intersection of **Artificial Intelligence** and **Offensive Security**.

| Project | Description | Status |
|---------|-------------|:---:|
| 💉 **LogPrompt Inject** | Research and frameworks demonstrating prompt injection attacks via malicious log ingestion. | <img src="https://img.shields.io/badge/Status-In_Development-yellow?style=flat-square"> |
| 🤖 **LLM-Assisted Alert Triage** | An automated SOC triage system using LLMs, explicitly designed and hardened to resist prompt injection from malicious logs. | <img src="https://img.shields.io/badge/Status-In_Development-yellow?style=flat-square"> |

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
