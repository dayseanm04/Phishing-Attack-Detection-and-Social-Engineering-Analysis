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
