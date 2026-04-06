# SOC Analyst Labs

This repository contains hands-on SOC analysis exercises including incident investigations, log analysis, and threat detection scenarios.

---

## 🔍 Lab 1: Brute Force Attack Investigation

### Objective
Identify and analyze repeated failed login attempts.

### Tools Used
- Splunk (lab environment)
- Windows Event Logs

### Steps
1. Reviewed login event logs
2. Identified multiple failed login attempts from a single IP
3. Checked time intervals and user account activity

### Findings
Detected repeated login failures consistent with a brute force attempt.

### Conclusion
Escalated as a potential security incident and recommended account lockout policies.

---

## 🔍 Lab 2: Suspicious Login Activity

### Objective
Detect unusual login behavior.

### Tools Used
- Log analysis tools
- Lab-based SIEM

### Steps
1. Reviewed login timestamps
2. Identified login attempts outside normal hours
3. Investigated source IP

### Findings
Unusual login behavior detected from unfamiliar location.

### Conclusion
Flagged for further investigation and potential account compromise.
