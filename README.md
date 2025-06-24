# Task 2: Phishing Email Analysis

## 📌 Objective
To analyze a suspicious email claiming to be from IRCTC and identify phishing traits that could potentially deceive users into revealing personal information or performing unintended actions.

## 🧪 Email Sample Source
Email Template: IRCTC Refund Processing  
Sender: irctc-helpdesk@securesupportcloud[.]com  
To: john[.]doe@mybusiness[.]com

## 🚩 Major Phishing Traits Identified
- **Impersonation of IRCTC** using a lookalike support email address
- **False refund claim** to attract attention with a specific amount (₹4,240)
- **Embedded QR Code** that prompts users to verify their mobile number, possibly leading to credential theft or malware
- **Lack of personalization**, no greeting or user-specific data
- **Time pressure tactics** ("expires in 2 business days") to rush users into action

## 🧰 Techniques Used
- WHOIS Lookup: Checked domain registration of the sender email and found it unaffiliated with IRCTC
- Email Header Analysis: Identified discrepancies in domain origin and sending server
- VirusTotal: QR code link was extracted and scanned for malicious intent
- Google Search: Verified that IRCTC does not use QR codes for refund processing
- General Awareness: Applied known phishing detection principles including urgency, grammar cues, and visual formatting
