# Phishing Indicators Summary

## Overview

This document summarizes the phishing indicators identified across all 10 email examples analyzed in this lab. Each example was evaluated against a standard security checklist to determine whether it was legitimate or a phishing/scam attempt.

Out of 10 emails reviewed, **9 were identified as suspicious** and **2 was identified as legitimate**.

---

### Example 01 – Trusted Dropbox Notification
**Verdict: ✅ Legitimate**

| Indicator | Present |
|------------|----------|
| Requests sensitive information | No |
| Suspicious sender domain | No |
| Generic greeting | No |
| Poor grammar or spelling | No |
| Urgency / fear-based manipulation | No |
| Suspicious links or attachments | No |

**Notes:** Email was sent from no-reply@dropbox.com, a verified Dropbox domain. The Dropbox Transfer logo was legitimate. The email was a standard automated notification informing the recipient that a file had been shared with them. No red flags were present.

---

### Example 02 – Lottery Scam
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Requests sensitive information | Yes |
| Suspicious sender domain | Yes |
| Generic greeting (no recipient name) | Yes |
| Poor grammar or spelling | Yes |
| Unrealistic financial reward | Yes |
| Suspicious attachment | Yes |

**Notes:** The email claimed to be from a US lottery but was sent from a Japanese domain (.jp). The body contained grammatical errors, no spaces after punctuation, and a suspicious PDF attachment. The recipient's name was not included in the congratulatory message.

---

### Example 03 – Booking Confirmation
**Verdict: ✅ Legitimate**

| Indicator | Present |
|------------|----------|
| Requests sensitive information | No |
| Suspicious sender domain | No |
| Generic greeting | No |
| Poor grammar or spelling | No |
| Urgency / fear-based manipulation | No |
| Requests money via email | No |

**Notes:** The email was a well-written booking confirmation from Bears Moving Co. The subject line included the company name, date, client name, and time. Payment methods were listed informally but no payment was requested via email.

---

### Example 04 – Extortion Email
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Requests money | Yes |
| Threatening language | Yes |
| Suspicious sender domain | Yes |
| Urgency / fear-based manipulation | Yes |
| Bitcoin payment requested | Yes |

**Notes:** The email was a blackmail attempt threatening to expose the recipient for watching inappropriate videos unless they send $3,000 via Bitcoin. The sender provided a Bitcoin wallet address.

---

### Example 05 – Fake Payment Advice
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Suspicious sender domain | Yes |
| Suspicious attachment | Yes |
| Impersonating a bank | Yes |
| Not sent from a no-reply address | Yes |

**Notes:** The email was sent from mail_server@company.com, a vague and unverified domain. It included a "Payment Advice.pdf" attachment, which banks do not send unsolicited. A legitimate bank notification would come from a verified no-reply address with the bank's official domain.

---

### Example 06 – Malicious HTML Attachment
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Sender name and signature mismatch | Yes |
| Suspicious attachment (HTML files) | Yes |
| Unprofessional subject line | Yes |
| Identity mismatch | Yes |

**Notes:** The email was sent by Theresa Baustert but signed off as Uzman Shamsi. The subject line was written in all caps and was highly unprofessional. The two attached HTML files were suspicious, HTML attachments can open fake webpages designed to steal user credentials.

---
