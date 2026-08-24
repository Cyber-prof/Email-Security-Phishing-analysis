**Email Security & Phishing Investigation**
A practical investigation into email authentication and phishing infrastructure.

**Overview**

This project documents an investigation that began with an email configuration exercise and evolved into the analysis of a suspicious phishing email.

**The investigation covered:**
SPF
DKIM
DMARC & alignment
Email header analysis
Microsoft 365 / Exchange infrastructure
WHOIS investigation
URL/redirect analysis
Webflow infrastructure
HTML & network analysis
Credential-harvesting detection
Key Finding

Authentication ≠ Trust

The investigated email successfully passed SPF, DKIM and DMARC authentication. However, further analysis revealed characteristics consistent with a credential-harvesting phishing campaign.

This investigation demonstrates why email security cannot rely solely on authentication mechanisms.

**Investigation**
Email Authentication
Understanding SPF, DKIM, DMARC and how authentication results are evaluated.

➡️ Read the Email Authentication Investigation

**Phishing Analysis**
Analysis of the suspicious email, URLs, redirects, hosting infrastructure and phishing page.

➡️ Read the Phishing Investigation

 **Findings**
Summary of the investigation and key conclusions.

➡️ View Findings

**Tools**

Thunderbird
WHOIS
VirusTotal
urlscan
Browser DevTools

**Disclaimer**

This project is for defensive cybersecurity research and educational purposes. Sensitive information has been redacted and actionable indicators have been defanged.
