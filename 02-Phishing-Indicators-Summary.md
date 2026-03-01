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

### Example 07 – Military Inheritance Scam
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Requests sensitive information | Likely |
| Suspicious sender domain | Yes |
| Identity mismatch | Yes |
| Unrealistic financial reward | Yes |
| Authority impersonation | Yes |
| Urgency / emotional manipulation | Yes |
| Use of alternate contact email | Yes |

**Notes:** The email claimed to be from a U.S. Marine Corps Captain in Iraq but was sent from a Dutch domain (@uwv.nl). The recipient was instructed to reply to a separate personal email address. The offer of $500,000 from funds found near Saddam's palace is a classic advance-fee (419) scam tactic.

---

### Example 08 – Fake FDIC Security Update
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Suspicious sender domain | Yes |
| Government impersonation | Yes |
| Unsecured / suspicious link (HTTP) | Yes |
| Vague technical reasoning | Yes |
| Urgency / fear-based manipulation | Yes |
| Generic greeting (no recipient name) | Yes |
| Bold formatting used to induce panic | Yes |

**Notes:** The email impersonated the FDIC using a non government email domain (@boomansion.net). The link provided used HTTP instead of HTTPS and pointed to a fake FDIC subdomain. Phrases like "temporarily suspended" and "ACH and Wire Transactions" were bolded to cause panic.

---

### Example 09 – Advance-Fee Scam (Fake Bank Draft)
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Requests personal information | Yes |
| Suspicious sender domain | Yes |
| Sender name and email mismatch | Yes |
| Unrealistic financial reward | Yes |
| Advance-fee scam pattern (419) | Yes |
| Use of third-party contact email | Yes |
| Poor grammar and spelling | Yes |
| Generic greeting (no recipient name) | Yes |

**Notes:** The sender claimed to be Daniel Arscott writing from Japan, but the email domain was Brazilian (.br). Multiple spelling errors were present including "transfered", "droped", and "concers". The information request at the bottom lacked spaces between numbers and fields, and used "Full names" instead of "Full name". The recipient was asked to send personal details to a third-party Yahoo email address to claim a $1.5 million bank draft.

---


### Example 10 – Fake Norton Renewal
**Verdict: 🚨 Suspicious**

| Indicator | Present |
|------------|----------|
| Suspicious sender domain (Gmail) | Yes |
| Inconsistent charge amounts | Yes |
| Urgency / fear-based manipulation | Yes |
| Suspicious helpline number | Yes |
| Generic greeting (no recipient name) | Yes |
| COVID-19 used as an excuse | Yes |

**Notes:** The email listed two different charge amounts ($480.87 and $399.99) that did not match. A fraudulent helpline number was provided to trick the recipient into calling and giving their financial information. COVID-19 was used as an excuse for why no prior confirmation was sent.

---

## Key Takeaways

**Sender domain is the first thing to check.** In nearly every suspicious email, the sender's domain had no connection to the organization being impersonated. Government agencies use .gov, companies use their own corporate domain, and military personnel do not email from foreign commercial domains.

**Urgency is a weapon.** Most phishing emails create a sense of panic, suspended accounts, unexpected charges, threatening consequences — to pressure the recipient into acting without thinking.

**Generic greetings are a red flag.** Legitimate organizations that have your account information will address you by name. "Dear Friend," "Dear Sir/Madam," and "Dear Client" are common signs of a bulk phishing campaign.

**Financial offers and rewards are almost always scams.** No one is sending you $500,000, a $1.5 million bank draft, or lottery winnings through a random email. These are advance-fee scams designed to extract money or personal information over time.

**Always verify before you act.** If an email asks you to click a link, call a number, download a file, or send money, stop and verify through the organization's official website or a their customer service.
