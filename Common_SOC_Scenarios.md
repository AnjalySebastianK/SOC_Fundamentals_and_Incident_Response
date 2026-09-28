# Common SOC Scenarios

## 1. Malware Incidents
Malware incidents involve malicious software infiltrating systems.  
Examples:
- Viruses, worms, trojans, ransomware.  
- Indicators: unusual file modifications, suspicious processes, outbound connections to command‑and‑control servers.  

SOC Response:
- Detect via EDR/SIEM alerts.  
- Isolate infected endpoints.  
- Collect forensic evidence (hashes, file paths, registry changes).  
- Escalate for eradication and patching.  

---

## 2. Phishing Incidents
Phishing incidents exploit human trust to steal credentials or deliver malware.  
Examples:
- Emails with malicious links or attachments.  
- Fake login pages mimicking legitimate services.  

SOC Response:
- Identify suspicious email headers, domains, or attachments.  
- Block sender domains and URLs.  
- Investigate compromised accounts.  
- Educate users and update detection rules.  

---

## 3. Account Compromise
Account compromise occurs when attackers gain unauthorized access to user accounts.  
Examples:
- Stolen credentials via phishing.  
- Brute‑force or credential stuffing attacks.  

SOC Response:
- Detect abnormal login patterns (time, location, device).  
- Force password resets and revoke sessions.  
- Escalate if privileged accounts are affected.  
- Investigate lateral movement attempts.  

---

## 4. Suspicious Logins
Suspicious logins are early warning signs of potential compromise.  
Indicators:
- Multiple failed login attempts.  
- Logins from unusual geolocations or impossible travel scenarios.  
- Access outside normal working hours.  

SOC Response:
- Validate against user behavior baselines.  
- Correlate with other alerts (e.g., malware detection).  
- Escalate if linked to critical systems.  
- Document and monitor for recurrence.  

---

## 5. Insider Threat Indicators
Insider threats involve malicious or negligent actions by employees or contractors.  
Examples:
- Unauthorized data access or exfiltration.  
- Privilege abuse.  
- Bypassing security controls.  

SOC Response:
- Monitor for unusual file transfers, USB usage, or database queries.  
- Investigate access logs for anomalies.  
- Escalate to HR/legal if intentional misuse is suspected.  
- Apply least‑privilege and continuous monitoring.  

---

## Quick Summary
- **Malware** → Detect, isolate, eradicate.  
- **Phishing** → Block, investigate, educate.  
- **Account Compromise** → Reset credentials, investigate scope.  
- **Suspicious Logins** → Validate anomalies, escalate if critical.  
- **Insider Threats** → Monitor misuse, escalate to HR/legal.  

SOC analysts must adapt workflows to each scenario, balancing **technical response** with **business impact awareness**.
