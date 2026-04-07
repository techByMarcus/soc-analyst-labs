# SOC Analyst Labs

This repository contains hands-on SOC (Security Operations Center) investigations focused on real-world attack scenarios, log analysis, and threat detection.

---

## 🔍 Lab 1: Brute Force Attack Investigation

### 🎯 Objective
Identify and analyze repeated failed login attempts to detect potential brute force activity.

### 🛠 Tools Used
- Splunk (lab environment)
- Windows Event Logs

### 🧪 Scenario
A high volume of failed login attempts was observed within a short period. The goal was to determine whether the activity represented a brute force attack.

### 🔎 Investigation Steps
- Reviewed authentication logs for failed login events  
- Identified repeated login attempts from a single IP address  
- Correlated timestamps to identify attack patterns  
- Analyzed affected user accounts  

### 🚨 Findings
- Multiple failed login attempts detected  
- Activity originated from a single IP address  
- Pattern consistent with brute force behavior  

### 🛡 Response / Mitigation
- Recommend blocking the source IP address  
- Implement account lockout policies  
- Enable multi-factor authentication (MFA)  

### 📌 Skills Demonstrated
- Log analysis  
- Threat detection  
- Incident investigation  
- SIEM usage (Splunk)  

---

## 🔍 Lab 2: Suspicious Login Activity

### 🎯 Objective
Detect and analyze unusual login behavior that may indicate unauthorized access.

### 🛠 Tools Used
- SIEM (lab environment)
- Log analysis tools

### 🧪 Scenario
Login activity was detected outside of normal operating hours. The objective was to determine whether the activity was legitimate or potentially malicious.

### 🔎 Investigation Steps
- Reviewed login timestamps and user activity  
- Identified logins occurring outside normal hours  
- Investigated source IP address and location  
- Compared activity against baseline user behavior  

### 🚨 Findings
- Login attempts occurred at unusual times  
- Access originated from an unfamiliar location  
- Activity inconsistent with normal user behavior  

### 🛡 Response / Mitigation
- Recommend verifying user activity  
- Enforce MFA  
- Monitor account for further suspicious behavior  

### 📌 Skills Demonstrated
- Behavioral analysis  
- Threat detection  
- Log correlation  
- Incident triage  

---

