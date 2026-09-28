# Security Events & Incidents

## 1. Events vs Alerts
- **Event** → Any activity happening in a system (normal or abnormal).  
  Examples: user login, file creation, process start, network connection.  
  Events are raw data points — not all are security‑relevant.

- **Alert** → A notification generated when an event/log matches a detection rule or suspicious pattern.  
  Examples: multiple failed logins, malware execution detected, SQL injection attempt.  
  Alerts demand analyst attention but may include false positives.

---

## 2. Alerts vs Incidents
- **Alert** → Suspicious activity flagged by monitoring tools.  
  - May or may not represent a real attack.  
  - Requires triage and validation.  

- **Incident** → A confirmed security breach or malicious activity.  
  - Validated by analysts through investigation.  
  - Requires containment, eradication, and recovery.  

Alerts are “possible problems.” Incidents are “proven problems.”

---

## 3. Incident Severity Levels
Incidents are classified by severity to guide response urgency:

- **Low Severity**  
  - Minimal impact, limited scope.  
  - Example: single failed login attempt.  

- **Medium Severity**  
  - Potential risk, requires monitoring.  
  - Example: malware detected but blocked.  

- **High Severity**  
  - Significant impact on critical systems.  
  - Example: unauthorized access to sensitive database.  

- **Critical Severity**  
  - Major breach, business disruption, or regulatory violation.  
  - Example: ransomware outbreak, large‑scale data exfiltration.  

---

## 4. Security Incident Classification
Incidents are categorized to streamline response:

- **Malware Infection** → Virus, trojan, ransomware.  
- **Unauthorized Access** → Compromised accounts, privilege escalation.  
- **Data Breach** → Confidential data exfiltration or exposure.  
- **Denial of Service (DoS/DDoS)** → Service disruption via traffic overload.  
- **Phishing/Social Engineering** → Credential theft via deception.  
- **Policy Violation** → Misuse of systems, non‑compliance with security rules.  

Classification ensures the right playbook is applied.

---

## 5. Incident Prioritization
SOC analysts prioritize incidents based on:

- **Severity** → How damaging the incident could be.  
- **Asset Criticality** → Importance of the affected system (e.g., payment gateway vs. test server).  
- **Threat Context** → Whether the vulnerability is actively exploited in the wild.  
- **Business Impact** → Potential financial, reputational, or regulatory consequences.  
- **Time Sensitivity** → How quickly the incident must be contained.  

Prioritization ensures resources are focused on the most dangerous threats first.

---

## Quick Summary
- **Event = raw activity.**  
- **Alert = suspicious activity flagged.**  
- **Incident = confirmed attack.**  
- **Severity levels = Low → Critical.**  
- **Classification = Malware, Access, Breach, DoS, Phishing, Policy.**  
- **Prioritization = Severity + Asset + Context + Impact.**

SOC analysts must **filter events → validate alerts → confirm incidents → prioritize response** to protect the organization effectively.
