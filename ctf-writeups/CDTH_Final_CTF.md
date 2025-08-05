# CDTH Final CTF – GuideM (2025)

As part of the final assessment for the *Cyber Defense & Threat Hunting (CDTH)* course by GuideM, I participated in a practical CTF focused on real-world detection, investigation, and reporting.

---

## 🎯 Objective

To identify suspicious behavior in system logs, map activities to MITRE ATT&CK techniques, and construct a timeline of the attacker’s actions.

---

## 🔍 What I Did

- Parsed logs for suspicious Event IDs (e.g., 4688, 4104)
- Detected PowerShell execution from unusual directories
- Found encoded commands and LOLBins (e.g., certutil, Invoke-WebRequest)
- Cross-referenced activities with MITRE ATT&CK (T1059.001, T1047, etc.)
- Built an incident timeline and wrote a detailed findings report

---

## 🧠 Tools Used

- Windows Event Viewer
- PowerShell
- ELK Stack
- MITRE ATT&CK Navigator
- Notion (for notes + report)

---

## 📘 Key Learnings

- Developed a strong methodology for log-based threat detection
- Understood how adversaries use native tools for stealth
- Practiced turning raw data into actionable incident response insights

*Note: Due to course integrity, no flags or exact answers are shared.*
