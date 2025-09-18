# FUTURE_CS_02

# 🛡️ Task 2 - SOC Incident Response Report  

This project is part of my **Cybersecurity Internship at Future Interns**.  
The goal was to simulate **Multiple Security Alerts Detected Through Splunk SIEM** using Splunk and log analysis.  

---

## 🔍 Task Overview
- **Analyzed system logs** (`SOC_Task2_Sample_Logs.txt`) using **Splunk SIEM**.  
- Identified suspicious activities such as **failed logins, malware detections, and external IP attacks**.  
- Classified incidents by severity and drafted an **Incident Response Report**.  

---

## 🛠️ Tools & Environment
- **Splunk SIEM (Free Trial)** – Log monitoring and analysis  
- **Kali Linux** – Environment  
- **grep** (manual log filtering)  
- **Sample SOC Logs** – Provided for analysis  

---

## 🔎 Key Findings
1. **Malware Detection Events**  
   - Trojan, Rootkit, Spyware, Worm, Ransomware detected  
   - Users involved: **bob, alice, eve, charlie, david**  

2. **Failed Login Attempts**  
   - Multiple failed logins from suspicious IPs  
   - Possible **brute-force attacks**  

3. **Suspicious External IP**  
   - IP **203.0.113.77** flagged multiple times  
   - Appears to be the main attacker  

4. **User Bob’s Compromise**  
   - `user=bob` had multiple malware detections and suspicious activities  

---

## 🎯 Risk Assessment
- 🔴 **High Risk** – Ransomware, Rootkit infections  
- 🟠 **Medium Risk** – Failed logins (brute-force attempts)  
- 🔴 **High Risk** – Repeated attacks from external IP `203.0.113.77`  

---

## 🛡️ Recommendations
✔ Isolate infected systems immediately  
✔ Block malicious IPs (esp. `203.0.113.77`)  
✔ Reset user credentials (Bob, Alice, Eve, Charlie, David)  
✔ Enforce MFA + account lockout policies  
✔ Conduct forensic investigation on compromised hosts  

---

## ✅ Outcome
This task provided **hands-on SOC experience**:  
- Log analysis using Splunk  
- Threat detection & triage  
- Writing a professional **Incident Response Report**  
- Simulating real-world SOC analyst workflow  

---

## 📝 Author
**Kumari Tulsi**  
CIN ID: FIT/SEP25/CS3691 
