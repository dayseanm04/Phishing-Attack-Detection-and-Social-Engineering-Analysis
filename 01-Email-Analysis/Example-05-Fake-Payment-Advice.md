# Example 05 – Fake Payment Advice Email

## Classification  
Suspicious Email (Impersonation / Malicious Attachment)


## Email Screenshot  

![Fake Payment Advice Email Screenshot](/02-Images/Example-05-fake-payment-advice.png)

---

## Scenario Summary  

This email appears to be a payment notification.

**Sender Email:** mail_server@company.com  
**Attachment:** Payment Advice.pdf

The message implies a financial transaction and includes a PDF attachment labeled “Payment Advice.pdf.”

---

## Security Analysis  

### 1. Suspicious Sender Address  
- The sender email is **mail_server@company.com**  
- The domain is generic and does not represent a known financial institution  
- Legitimate banks and financial institutions use official domain names  

Notification emails from legitimate organizations typically come from structured addresses like: no-reply@bankname.com  

The use of a vague “company.com” domain is a major red flag.

---

### 2. Unsolicited Financial Attachment  
- The email includes an attachment titled **Payment Advice.pdf**  
- The recipient was probably not expecting a payment notification  
- Unsolicited financial documents are commonly used to distribute malware  

Banks typically provide statements through secure portals rather than random email attachments.

---

### 3. Impersonation Attempt  
- The message attempts to appear as a financial notification  
- The sender identity does not match any legitimate institution  
- There is no verification of the recipient’s identity  

This suggests an impersonation attempt designed to trick the recipient into opening the attachment.

---

### 4. Malware Delivery Risk  
PDF attachments in phishing emails may:

- Contain malicious scripts
- Deliver a malware  

Opening unexpected financial attachments presents a significant security risk.

---

## Phishing Indicator Checklist Review  

| Indicator | Present |
|------------|----------|
| Requests sensitive information | Potential |
| Suspicious sender domain | Yes |
| Unexpected attachment | Yes |
| Financial context without verification | Yes |
| Legitimate institutional branding | No |
| Requests money | Implied |

Multiple phishing indicators are present.

---

## Final Assessment  

This email fails the security evaluation checklist due to the suspicious sender domain and the unexpected financial attachment.

The generic “**company.com**” domain combined with an unsolicited “**Payment Advice.pdf**” strongly suggests a phishing or malware distribution attempt.

**Risk Level: High**  
**Conclusion: Phishing – Impersonation with Malicious Attachment**
