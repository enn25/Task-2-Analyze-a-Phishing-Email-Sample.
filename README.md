# Task 2: Phishing Email Analysis

## Objective

Identify phishing characteristics in a suspicious email sample.
- Spoofed sender addresses
- Suspicious links and attachments
- Email header discrepancies
- Social engineering tactics

---

## Tools & Resources

| Tool | Purpose | Link |
|------|---------|------|
| **Google Admin Toolbox** | Email header analysis | [Message Header Analyzer](https://toolbox.googleapps.com/apps/messageheader) |
| **Manual Inspection** | Visual email examination | - |
| **Public Samples** | Reference phishing examples | Hook Security, Spamhaus |

---

## Sample Email Analysis

### **Email Metadata**
```
Subject: [Spam-Mail] Dear Sir/Madam. (This message should be blocked: ctdos35128)
From: JOSEPH CAMARAH VIEIRA <vieira@aol.com>
Return Path: mail.shako.com.tw
Client: Microsoft Outlook Express 6.00.2600.0000
Recipients: Undisclosed recipients
```

### **Initial Assessment**
This email represents a **classic bulk phishing attempt** featuring:
- Obfuscated sender details
- Mismatched mail headers
- Malicious link disguised as "Grant application"
- Financial fraud social engineering tactics

---

## Phishing Indicators Analysis

| # | **Indicator** | **Evidence Found** | **Risk Level** |
|---|---------------|-------------------|----------------|
| 1 | **Sender Spoofing** | Claims `aol.com` origin but sent via `mail.shako.com.tw` | **High** |
| 2 | **Header Discrepancies** | Suspicious mail servers (`hinet.net`, `shako.com.tw`) with `-12 mins` delivery time | **High** |
| 3 | **Malicious Links** | "Grant application" link pointing to non-government domain | **Critical** |
| 4 | **Psychological Manipulation** | Subject mentions "should be blocked" to bypass filters | **Medium** |
| 5 | **URL Mismatch** | Trusted appearance but redirects to unrelated external site | **High** |
| 6 | **Generic Targeting** | "Dear Sir/Madam" indicates mass distribution | **Medium** |
| 7 | **Language Anomalies** | Awkward phrasing and suspicious identifiers | **Medium** |

### **Attack Vector Summary**
This sophisticated phishing campaign employs **sender identity spoofing**, **misleading hyperlinks**, and **financial opportunity baiting** to deceive recipients into clicking the fraudulent "Grant application" link and potentially surrendering sensitive credentials.

---

## Visual Evidence

### **Repository Structure**
```
screenshots/
├── phishing_email.png      # Hook Security Office 365 spoof sample
├── header_analysis.png      # Google Admin Toolbox analysis output
 email-header.txt                   # Raw email header data for analysis
```

---

## Cybersecurity Concepts Demonstrated

### **Core Techniques Analyzed**
- **Email Spoofing**: Forged sender addresses to establish false legitimacy
- **Header Forensics**: Technical analysis of email routing and authentication
- **Link Deception**: Legitimate-appearing hyperlinks masking malicious destinations  
- **Social Engineering**: Psychological manipulation through urgency and financial incentives

---

## Screenshot
-> Phishing email : 

<img width="700" height="600" alt="phishing-email" src="https://github.com/user-attachments/assets/958837b6-14b3-495f-97a4-8ccb7c2b3c84" />

-> Header analysis :

<img width="700" height="600" alt="header-analysis" src="https://github.com/user-attachments/assets/578bbeec-2291-40f6-aba0-21d6de4aac24" />

---
