# Threat Hunting — Portfolio

This repository contains my hands-on hunting artifacts and detection rules.  
Artifacts are organized by **week → day → evidence**.

---

## Week of 2025-09-15
### 2025-09-20 — Sysmon baseline & basic hunts

**Objective**  
Verify Sysmon logs for process creation, network connections and failed logons.

**Artifacts**  
- 📸 [Screenshots](week-2025-09-15/2025-09-20/screenshots/) — Event Viewer (general + details)  
- 📂 [EVTX](week-2025-09-15/2025-09-20/evtx/) — exported events (open in Windows Event Viewer)  
- 📄 [proc_report.txt](week-2025-09-15/2025-09-20/proc_report.txt) — PowerShell query output for process creation  
- 📄 [failedlogin_report.txt](week-2025-09-15/2025-09-20/failedlogin_report.txt) — failed login report  

**Detection**  
- [Sigma Rule — Detect PowerShell EncodedCommand](sigma-rules/detect_powershell_encodedcommand.yml)

---

## Sigma Rules
- [Detect PowerShell EncodedCommand](sigma-rules/detect_powershell_encodedcommand.yml)

---

## Contact / Portfolio
- 💼 [LinkedIn](https://www.linkedin.com/in/a-craash/)  
- 📂 GitHub: this repository (regularly updated)  
