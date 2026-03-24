# SOC Analyst Log Analysis Simulation

![Status](https://img.shields.io/badge/Status-Active%20Development-blue)
![Focus](https://img.shields.io/badge/Focus-SOC%20Analysis-green)
![Level](https://img.shields.io/badge/Level-Entry%20Level-blueviolet)

---

## Overview

This project simulates a **Security Operations Center (SOC) analyst workflow** using sample log data.  
It demonstrates the ability to:

- Detect suspicious activity  
- Categorize and prioritize security events  
- Document findings and proposed mitigation actions  
- Apply incident response principles in a structured, professional manner  

All analysis is performed using **browser-accessible tools** (Markdown, Excel, Google Sheets) — no terminal or live systems are required.

---

## Project Objectives

The objectives of this simulation project are:

- Understand how logs are analyzed for threat detection  
- Identify anomalous patterns and potential attacks  
- Demonstrate incident triage and documentation skills  
- Apply SOC best practices in a portfolio-ready format  

---

## Sample Event Log Analysis

| Timestamp           | Source IP       | Destination IP | Event Type            | Description                               | Severity | Notes / Action |
|--------------------|----------------|----------------|--------------------|-------------------------------------------|----------|----------------|
| 2026-03-23 08:12:45 | 192.168.1.101  | 10.0.0.5       | Failed Login        | 5 consecutive failed login attempts      | Medium   | Monitor for brute-force, consider account lockout |
| 2026-03-23 09:03:21 | 203.0.113.50   | 10.0.0.8       | Suspicious Access   | Access attempt from external IP          | High     | Block IP, alert security team |
| 2026-03-23 10:45:12 | 192.168.1.150  | 10.0.0.10      | Malware Detection   | File flagged as potentially malicious    | High     | Isolate endpoint, initiate scan |
| 2026-03-23 11:22:34 | 192.168.1.120  | 10.0.0.5       | Policy Violation    | Unauthorized USB device connected        | Medium   | Investigate user activity, enforce policy |
| 2026-03-23 12:05:56 | 198.51.100.12  | 10.0.0.9       | Port Scan Detection | Multiple ports scanned in short timeframe | High     | Block IP, log incident, monitor network |

> Note: All IPs and events are **simulated for learning purposes**.

---

## Incident Response Documentation Example

**Incident ID:** 2026-03-SOC-001  
**Detected:** 2026-03-23 09:03  
**Event Type:** Suspicious External Access  
**Affected System:** Internal Web Server (10.0.0.8)  
**Description:** An external IP (203.0.113.50) attempted access to the internal web server using invalid credentials multiple times.  
**Initial Action:** Block IP at firewall, log incident in tracking sheet  
**Follow-up:** Monitor for further attempts, review security policies  
**Resolution:** No breach occurred, alert sent to SOC manager, ongoing monitoring established  

---

## Skills Demonstrated

- Log analysis and pattern recognition  
- Event triage and severity categorization  
- Structured incident documentation  
- Familiarity with SOC workflows and reporting  
- Awareness of common attacks: brute force, port scanning, malware detection  

---

## Future Improvements

- Integrate larger sample log sets for more complex analysis  
- Include simulated correlation rules for alert prioritization  
- Add automated log parsing templates (Python or Excel macros)  
- Expand to include SIEM-style dashboards using browser tools  
- Introduce detailed threat intelligence context for each event
