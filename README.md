#  Phishing Attack Detection and Social Engineering Analysis

This lab is a hands-on cybersecurity project where I analyzed 10 real-world email samples to identify phishing attempts, social engineering tactics, and security threats. I evaluated each email using a structured security checklist, documented with detailed findings, and assigned a risk level and final verdict.

---

## About This Lab/Project

This Lab/project simulates the role of a **help-desk security analyst** responsible for reviewing suspicious emails reported by employees. The goal was to develop practical skills in:

- Identifying phishing indicators and social engineering techniques
- Analyzing sender domains, email headers, and message content
- Recognizing common scam patterns such as advance-fee fraud, brand impersonation, and government impersonation
- Documenting security findings

---

## Quick Navigation

| File / Folder | Description |
|------|-------------|
| [**`01-Email-Analysis/`**](./01-Email-Analysis/) | Folder containing all 10 individual email analysis files |
| [**`02-Images/`**](./02-Images/) | Folder containing all email screenshots referenced in the analysis |
| [**`01-Lab-Objectives.md`**](01-Lab-Objectives.md) | Lab goals and evaluation checklist |
| [**`02-Phishing-Indicators-Summary.md`**](02-Phishing-Indicators-Summary.md) | Full summary of all 10 examples with verdicts and indicator tables |
| [**`03-Security-Recommendations.md`**](03-Security-Recommendations.md) | Security best practices and lessons learned |
| [**`04-Phishing-Email-Analysis-Raw-Documentation`**](04-Phishing-Email-Analysis-Raw-Documentation.md) | Original raw documentation and notes used throughout the lab |

### Email Analysis Examples

| Example | Type | Verdict |
|---------|------|---------|
| [**`Example 01 – Trusted Dropbox`**](./01-Email-Analysis/Example-01-Trusted-Dropbox.md) | File Sharing Notification | ✅ Legitimate |
| [**`Example 02 – Lottery Scam`**](./01-Email-Analysis/Example-02-Lottery-Scam.md) | Advance-Fee / Fake Reward | 🚨 Phishing |
| [**`Example 03 – Booking Confirmation`**](./01-Email-Analysis/Example-03-Booking-Confirmation.md) | Service Confirmation Email | ✅ Legitimate |
| [**`Example 04 – Extortion Email`**](./01-Email-Analysis/Example-04-Extortion-Email.md) | Blackmail / Extortion | 🚨 Phishing |
| [**`Example 05 – Fake Payment Advice`**](./01-Email-Analysis/Example-05-Fake-Payment-Advice.md) | Bank Impersonation | 🚨 Phishing |
| [**`Example 06 – Malicious HTML Attachment`**](./01-Email-Analysis/Example-06-Malicious-HTML-Attachment.md) | Malicious Attachment | 🚨 Phishing |
| [**`Example 07 – Military Inheritance Scam`**](./01-Email-Analysis/Example-07-Military-Inheritance-Scam.md) | Authority Impersonation / 419 Scam | 🚨 Phishing |
| [**`Example 08 – Fake FDIC Update`**](./01-Email-Analysis/Example-08-Fake-FDIC-Security-Update.md) | Government Impersonation | 🚨 Phishing |
| [**`Example 09 – Advance-Fee Scam`**](/01-Email-Analysis/Example-09-International-Bank-Draft-Scam.md) | Identity Deception / 419 Scam | 🚨 Phishing |
| [**`Example 10 – Fake Norton Renewal`**](./01-Email-Analysis/Example-10-Fake-Norton-Renewal.md) | Brand Impersonation / Vishing Setup | 🚨 Phishing |

---

## Methodology

Each email was analyzed using the following evaluation checklist:

- Does the message ask for sensitive information?
- Is the sender's name consistent with the email address?
- Does the domain match the organization being represented?
- Are there spelling errors, poor grammar, or inconsistent formatting?
- Does the message force the user to a webpage or request a download?
- Are there unexpected attachments or suspicious links?
- Does the message request money or personal details?
- Is urgency or emotional manipulation being used?

Each example was then assigned one of the following verdicts:

- ✅ **Legitimate** — No phishing indicators detected
- 🚨 **Phishing** — One or more critical indicators present

---

## Lab Results Summary

| | Count |
|--|--|
| Total Emails Analyzed | 10 |
| Legitimate | 2 |
| Phishing / Suspicious | 8 |
| Most Common Indicator | Suspicious Sender Domain |
| Scam Types Identified | Advance-Fee, Brand Impersonation, Government Impersonation, Extortion, Vishing |

---

## Author

**Daysean Mensah**  
Computer Systems student with a concentration in Network & Security. Passionate about threat analysis, security awareness, and building practical, real-world skills through hands-on labs and projects.

This project was completed as part of a personal cybersecurity learning journey. All email samples were used strictly for educational purposes.
