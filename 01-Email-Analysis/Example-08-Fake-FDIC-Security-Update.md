# Example 08 – Fake FDIC Security Update

## Classification  
Suspicious Email (Phishing / Government Impersonation)

## Email Screenshot

![Fake FDIC Security Update Email Screenshot](/02-Images/Example-08-fdic-scam.png)

---

## Scenario Summary  

This email claims to be from the FDIC (Federal Deposit Insurance Corporation), a U.S. government agency. It warns the recipient that their account transactions have been suspended and instructs them to click a link to download a security update.

**Displayed Sender Name:** ACH Payment  
**Sender Email:** Opal@boomansion.net

---


Dear client,

Your account **ACH and Wire transactions** have been **temporarily suspended** for your Security.<br/>
due to the expiration of your security version <br/>
To download and install the newest Updates, follow this link security **http://www.update.fdic.gov**<br/><br/>
As soon as it is set up, your transaction abilities will be fully restored.<br/>
Best regards, Online security department Federal Deposit Insurance Corporation.

---

## Security Analysis  

### 1. Sender Domain Does Not Match the Claimed Organization  

- The email claims to be from the **FDIC**, a U.S. federal government agency
- The actual sender email is **Opal@boomansion.net**
- Government agencies use **.gov** domains — any legitimate FDIC communication would come from an address ending in **@fdic.gov**

A non-government domain is being used to impersonate a federal agency is a major red flag.

---

### 2. Suspicious and Unofficial Link  

- The email directs the recipient to: **http://www.update.fdic.gov**
- The link uses **HTTP** instead of **HTTPS**, meaning the connection is unencrypted and unsecured
- The FDIC does not have a **update.fdic.gov** subdomain
- This URL is crafted to appear legitimate while pointing to a potentially malicious destination


Clicking links from unverified senders can lead to credential theft or malware installation.

---

### 3. Vague and Nonsensical Reasoning  

- The email claims transactions were suspended due to an expired **"security version"**
- This is not a real technical term used by banks or government agencies
- Legitimate financial institutions provide clear, specific explanations when suspending account activity

The vague language is designed to cause panic without requiring the scammer to provide verifiable details.

---

### 4. Urgency and Fear Based Social Engineering  

- The message implies immediate financial consequences, a suspended **ACH and Wire transactions**
- This creates urgency, pressuring the recipient to act quickly without thinking critically
- Scammers use urgency to bypass the recipient's better judgment

---

### 5. Generic Greeting  

- The email starts with **"Dear client"** rather than the recipient's actual name
- A real government agency like the FDIC would address the account holder by their full legal name
- Generic greetings are a common indicator that the email was sent in bulk to many targets

---

### 6. Strategic Use of Bold Formatting  

- The email uses **bold text** to emphasize specific phrases such as **"ACH and Wire Transactions"**, **"temporarily suspended"**, and **"install the newest Updates"**
- This formatting is intentional it draws the reader's those phrases to create panic

---

