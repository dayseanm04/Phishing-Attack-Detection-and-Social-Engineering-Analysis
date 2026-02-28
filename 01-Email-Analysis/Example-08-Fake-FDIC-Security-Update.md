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



