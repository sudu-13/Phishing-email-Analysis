# Phishing-email-Analysis

#What is Phishing Email Analysis?

Phishing Email Analysis is the process of examining suspicious emails to determine whether they are legitimate or malicious. The goal is to identify indicators of phishing attacks and protect users from credential theft, malware infections, and financial fraud.

# Objectives
Identify phishing indicators in an email.
Analyze email headers.
Examine sender information.
Check URLs and attachments.
Determine the attacker's intent.
Recommend mitigation and response actions.

# Steps for Phishing Email Analysis
# 1. Examine the Sender's Email Address
Check whether the sender's address matches the organization it claims to represent.
# Example:
Legitimate: support@paypal.com
Phishing: support-paypal@gmail.com

# Red Flags:
Misspelled domains
Free email providers
Suspicious domain names

# 2. Analyze the Subject Line
Attackers often create urgency.
# Examples:
"Your Account Will Be Suspended!"
"Urgent Payment Required"
"Verify Your Password Immediately"

# 3. Review the Email Content
Look for:
Grammar mistakes
Spelling errors
Generic greetings ("Dear Customer")
Threatening language
Requests for sensitive information

# 4. Inspect URLs
Hover over links without clicking.
# Example:
Displayed:
https://www.paypal.com
Actual:
http://paypal-login-security.xyz

# Tools:
VirusTotal
URLScan
PhishTank




# 🎯 Lab Objective
The objective of this lab is to analyze a real-world phishing email sample using manual investigation techniques. Students will learn to review email headers, validate the sender's identity, check domain/IP reputation, and extract indicators of compromise (IOCs).

# 🛠️ Lab Setup
📨 Download Email Sample (.eml)
💻 Tools Recommended:
MX Toolbox Email Header Analyzer
EML Analyzer
IP reputation check (e.g., VirusTotal, AbuseIPDB, Cisco Talos)
Whois lookup (e.g., whois.domaintools.com)
URL and Domain analysis (e.g., urlscan.io, VirusTotal)
# 🧪 Lab Task: Analyze the Suspicious Email
# 📥 Scenario:
You received an email from BANCO DO BRADESCO LIVELO claiming that your card has 92,990 points expiring today, sent from banco.bradesco@atendimento.com.br.

Investigate and answer the following:

🔍 Questions:
# 1. What is the full email address of the sender?
![Email Header Analysis](https://github.com/sudu-13/Phishing-email-Analysis/blob/2cc44277acdce8ec14b6d3164f03dbd66a72e74a/Screenshot%202026-06-11%20073624.png)

The screenshot only shows the EML Analyzer upload page with the file “BRADESCO LIVELO.eml” selected. It does not display any email headers, sender information, or analysis results.
So, the full email address of the sender cannot be determined from this screenshot alone.
If you want me to identify the sender, please upload either:
1. The EML file itself (BRADESCO LIVELO.eml), or
2. A screenshot of the analysis results showing the email headers (e.g., From, Return-Path, Reply-To, etc.).
Once you provide that, I can extract the sender's full email address.

# 2. What domain is used to send this email? (Check Return-Path or From)
![Email Header Analysis](https://github.com/sudu-13/Phishing-email-Analysis/blob/a851119784bc1f4588533ebee7a251e766c10d8e/Screenshot%202026-06-11%20074121.png)
The screenshot shows the From field as:

# banco.bradesco@atendimento.com.br
Therefore, the domain used to send the email (from the From header) is:
# atendimento.com.br

# 3. What is the sender’s IP address from the header?
![Email Header Analysis](https://github.com/sudu-13/Phishing-email-Analysis/blob/bbdf0ae6b077e9cf8f820e3c5bb48d84e984adc6/Screenshot%202026-06-11%20074951.png)
From the email header "Hops" table, the earliest external source (Hop 2) shows:
From: 137.184.34.4




