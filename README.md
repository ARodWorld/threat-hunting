Threat Hunting — Portfolio

This repository contains my hands-on hunting artifacts and detection rules.

Week 2025-09-20 — Sysmon baseline & basic hunts
- Objective: verify Sysmon logs for process creation, network connections and failed logons.
- Artifacts:
  - `week-2025-09-20/screenshots/` — Event Viewer screenshots (general + details).
  - `week-2025-09-20/evtx/` — exported .evtx events (can be opened in Windows Event Viewer).
  - `week-2025-09-20/proc_report.txt` — PowerShell query output for process creations.
  - `week-2025-09-20/failedlogin_report.txt` — failed login report.
- Detection: example Sigma rule in `/sigma-rules/detect_powershell_encodedcommand.yml`

Contact / Portfolio
- Notion: 
- LinkedIn:
