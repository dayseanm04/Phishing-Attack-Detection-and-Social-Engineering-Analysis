#  Phishing Attack Detection and Social Engineering Analysis

This lab is a hands-on cybersecurity project where I analyzed 10 real-world email samples to identify phishing attempts, social engineering tactics, and security threats. I evaluated each email using a structured security checklist, documented with detailed findings, and assigned a risk level and final verdict.

---

## About This Project

This project simulates the role of a **help-desk security analyst** responsible for reviewing suspicious emails reported by employees. The goal was to develop practical skills in:

- Identifying phishing indicators and social engineering techniques
- Analyzing sender domains, email headers, and message content
- Recognizing common scam patterns such as advance-fee fraud, brand impersonation, and government impersonation
- Documenting security findings

### Email Analysis Examples

| Example | Type | Verdict |
|---------|------|---------|
| [**`Example 01 – Trusted Dropbox`**](./01-Email-Analysis/Example-01-Trusted-Dropbox.md) | File Sharing Notification | ✅ Legitimate |
| [Example 02 – Lottery Scam](./01-Email-Analysis/Example-02-Lottery-Scam.md) | Advance-Fee / Fake Reward | 🚨 Phishing |
| [Example 03 – Booking Confirmation](./01-Email-Analysis/Example-03-Booking-Confirmation.md) | Service Confirmation Email | ✅ Legitimate |
| [Example 04 – Extortion Email](./01-Email-Analysis/Example-04-Extortion-Email.md) | Blackmail / Extortion | 🚨 Phishing |
| [Example 05 – Fake Payment Advice](./01-Email-Analysis/Example-05-Fake-Payment-Advice.md) | Bank Impersonation | 🚨 Phishing |
| [Example 06 – Malicious HTML Attachment](./01-Email-Analysis/Example-06-Malicious-HTML-Attachment.md) | Malicious Attachment | 🚨 Phishing |
| [Example 07 – Military Inheritance Scam](./01-Email-Analysis/Example-07-Military-Inheritance-Scam.md) | Authority Impersonation / 419 Scam | 🚨 Phishing |
| [Example 08 – Fake FDIC Update](./01-Email-Analysis/Example-08-Fake-FDIC-Security-Update.md) | Government Impersonation | 🚨 Phishing |
| [Example 09 – Advance-Fee Scam](/01-Email-Analysis/Example-09-International-Bank-Draft-Scam.md) | Identity Deception / 419 Scam | 🚨 Phishing |
| [Example 10 – Fake Norton Renewal](./01-Email-Analysis/Example-10-Fake-Norton-Renewal.md) | Brand Impersonation / Vishing Setup | 🚨 Phishing |

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

**daysean mensah**  
