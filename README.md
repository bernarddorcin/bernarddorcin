<!-- Header banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:123a5a,100:1f6feb&height=190&section=header&text=Bernard%20Dorcin&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Cybersecurity%20Engineer%20%E2%80%A2%20Splunk%20%E2%80%A2%20Microsoft%20Sentinel%20%E2%80%A2%20GRC&descSize=17&descAlignY=58" alt="Bernard Dorcin - Cybersecurity Engineer" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=2EA043&center=true&vCenter=true&width=640&lines=Triaging+15%2C000%2B+security+events+a+day+in+Splunk;Writing+detections+in+SPL+and+KQL;GRC+in+healthcare%3A+HIPAA+%E2%80%A2+NIST+800-53+%E2%80%A2+CSF+2.0;Open+to+SIEM%2C+SOC+and+GRC+roles+%E2%80%94+FTE+or+contract" alt="Typing summary"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bernard-dorcin/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
  <a href="https://github.com/bernarddorcin/security-labs"><img src="https://img.shields.io/badge/Security_Labs-View_Repo-2EA043?style=for-the-badge&logo=github&logoColor=white" alt="Security Labs"/></a>
  <img src="https://img.shields.io/badge/Status-Open_to_Work-F2A900?style=for-the-badge" alt="Open to work"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Splunk-Core_Certified_Power_User-000000?style=flat-square&logo=splunk&logoColor=white" alt="Splunk Core Certified Power User"/>
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=flat-square" alt="CompTIA Security+"/>
  <img src="https://img.shields.io/badge/Microsoft-AZ--900-0078D4?style=flat-square" alt="Microsoft AZ-900"/>
  <img src="https://img.shields.io/badge/Microsoft-SC--300_(in_progress)-5E5E5E?style=flat-square" alt="SC-300 in progress"/>
</p>

---

## 👋 About me

I'm a **Cybersecurity Engineer** who lives in the SIEM. Today I triage **15,000+ security events a day in Splunk across 12 client environments**, and I've done **GRC work in healthcare** (HIPAA, NIST 800-53). Before security I worked in identity and network engineering, cloud IAM, and software development at **JPMorgan Chase**.

<table>
  <tr>
    <td width="50%" valign="top">

**🔎 What I do**
- Alert triage and incident handling in Splunk
- Detection engineering in SPL and KQL
- Risk assessments, control testing, access reviews
- Windows, Linux and identity log analysis

</td>
    <td width="50%" valign="top">

**🎯 What I'm looking for**
- Splunk / SIEM engineer or analyst
- SOC analyst (Microsoft Sentinel / Defender XDR)
- GRC / security risk analyst
- Remote or Miami hybrid · full-time or contract

</td>
  </tr>
</table>

---

## 🔐 Featured project: [12 Weeks of Security Labs](https://github.com/bernarddorcin/security-labs)

Hands-on detections built in my own lab and documented the way I'd document work on the job: **setup → detection logic → evidence → triage notes → tuning**.

| # | Lab | What it shows | Status |
| :-: | --- | --- | :-: |
| 01 | [Splunk home SIEM](https://github.com/bernarddorcin/security-labs/tree/main/01-splunk-home-siem) | Universal Forwarder, Sysmon, Windows + Linux logs, 4 detections, alerts, triage dashboard | ![In progress](https://img.shields.io/badge/-In_progress-F2A900?style=flat-square) |
| 02 | [Microsoft Sentinel + Defender XDR](https://github.com/bernarddorcin/security-labs/tree/main/02-sentinel-defender) | Analytics rules, KQL hunting, incident response | ![Planned](https://img.shields.io/badge/-Planned-6E7681?style=flat-square) |
| 03 | [GRC package](https://github.com/bernarddorcin/security-labs/tree/main/03-grc-package) | HIPAA risk assessment, vendor review, risk register | ![Planned](https://img.shields.io/badge/-Planned-6E7681?style=flat-square) |
| 04 | [Same attack, two SIEMs](https://github.com/bernarddorcin/security-labs/tree/main/04-two-siems-capstone) | Splunk vs Sentinel side by side + automation | ![Planned](https://img.shields.io/badge/-Planned-6E7681?style=flat-square) |

<details>
<summary><b>🛡️ Detections written so far (click to expand)</b></summary>
<br/>

| ID | Detection | MITRE ATT&CK | Data source |
| --- | --- | --- | --- |
| LC-001 | Brute force / password spray | T1110.001, T1110.003 | Windows Security 4625 |
| LC-002 | Encoded / download-cradle PowerShell | T1059.001, T1027 | Sysmon Event 1 |
| LC-003 | New local administrator | T1136.001, T1098 | Windows Security 4720, 4732 |
| LC-004 | SSH brute force (Linux) | T1110.001 | /var/log/auth.log |

Every detection is written in **both SPL and KQL**: see the [detections folder](https://github.com/bernarddorcin/security-labs/tree/main/01-splunk-home-siem/detections).

</details>

---

## 🧰 Toolkit

**SIEM & detection**<br/>
<img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white"/>
<img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/KQL-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SPL-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Sysmon-3C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-C41E3A?style=for-the-badge"/>

**Response & GRC**<br/>
<img src="https://img.shields.io/badge/Defender_XDR-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white"/>
<img src="https://img.shields.io/badge/HIPAA-1F6FEB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NIST_800--53_%7C_CSF_2.0-1F6FEB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SOC_2_%7C_ISO_27001-1F6FEB?style=for-the-badge"/>

**Identity, cloud & infrastructure**<br/>
<img src="https://img.shields.io/badge/Entra_ID-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AWS_IAM-232F3E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Windows_Server-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white"/>
<img src="https://img.shields.io/badge/Palo_Alto-FA582D?style=for-the-badge&logo=paloaltonetworks&logoColor=white"/>

**Scripting & data**<br/>
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge"/>

---

## 🛠️ Earlier projects: infrastructure & data

<details>
<summary><b>🖥️ Windows Server & VMware (3 projects)</b></summary>
<br/>

- [VMware Pro 17 & Windows Server 2025 installation and configuration](https://github.com/bernarddorcin/VMWare_and_WindowServer2025_Installation)
- [Server hostname, Remote Desktop and static IP configuration](https://github.com/bernarddorcin/UpdateServerIP_toStaticIP_ChangeHostname_EnableRemoteConnection)
- [File server creation & mapping a shared folder to the local host](https://github.com/bernarddorcin?tab=repositories)

</details>

<details>
<summary><b>🗄️ SQL Server (3 projects)</b></summary>
<br/>

- [SQL Server Management Studio installation](https://github.com/bernarddorcin/SMSS_Installation)
- [Database creation and data population](https://github.com/bernarddorcin/DB_Creation_Population)
- [Database backup and restore](https://github.com/bernarddorcin/DB_Backup_Restore)

</details>

---

## 📈 Currently

- 🔨 **Building:** Lab 01, the Splunk home SIEM (Windows Server 2025 + Ubuntu Server 24.04)
- 📚 **Studying:** Microsoft SC-300, Microsoft Sentinel, Defender XDR, Linux
- 🎥 **Coming soon:** recorded walkthroughs of each lab

---

<p align="center">
  <b>Hiring for SIEM, SOC or GRC? Let's talk.</b><br/><br/>
  <a href="https://www.linkedin.com/in/bernard-dorcin/"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,50:123a5a,100:0d1117&height=100&section=footer" width="100%" alt=""/>
</p>
