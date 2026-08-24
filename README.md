# Task 2: Phishing Email Analysis
> **TL;DR**: Analyzed a phishing email impersonating IRCTC (fake refund + 
> malicious QR code). Used WHOIS to confirm the sender domain was unaffiliated 
> with IRCTC and VirusTotal to flag the QR code link, identifying 10 distinct 
> phishing indicators — from missing DKIM/SPF to urgency-based social engineering.

## 📌 Objective
To analyze a suspicious email claiming to be from IRCTC and identify phishing traits that could potentially deceive users into revealing personal information or performing unintended actions.

## 🧰 Techniques Used
- WHOIS Lookup: Checked domain registration of the sender email and found it unaffiliated with IRCTC
- VirusTotal: QR code link was extracted and scanned for malicious intent
- Google Search: Verified that IRCTC does not use QR codes for refund processing
- General Awareness: Applied known phishing detection principles including urgency, grammar cues, and visual formatting

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

