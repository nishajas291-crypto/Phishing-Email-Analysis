Phishing-Email-Analysis
 TASK 2 – Phishing Email Analysis

Objective

To analyze a suspicious email and identify phishing characteristics using free and publicly available tools. This task focuses on recognizing email spoofing, brand impersonation, and social engineering techniques commonly used in phishing attacks.


 Email Sample Overview

Subject: ID Badge Update Needed – Urgent

Sender: eHealth Support <health-care@webnotifications.net>

Recipient:john.doe@mybusiness.com


Summary:
The email impersonates Apple / iCloud services and claims that there is an iCloud+ billing or fraud issue. The recipient is warned about an unrecognized charge and is urged to take immediate action by clicking links such as “click here” or “contact support”.



Tools Used

1. Email Header / Sender Domain Analysis
2. VirusTotal(Domain and URL Reputation Analysis)



 Tool 1: Email Header / Sender Domain Analysis

 Purpose

 To verify whether the sender email address belongs to the legitimate organization it claims to represent.

 Analysis

 The sender address used in the email: health-care@webnotifications.net

 The email visually uses"Apple branding and" refers to Apple ID, iCloud+, and billing notifications.
 Official Apple emails originate from trusted domains such as:

  
  @apple.com
  @icloud.com
  

 Result

The sender domain webnotifications.net does not match Apple’s official domains.
This confirms email spoofing, a common phishing technique.



 Tool 2: VirusTotal (Domain and Link Analysis)

 Purpose 

 To analyze the reputation and safety of the sender domain and suspicious links found in the email.

 Analysis

 The sender domain and copied phishing link were analyzed using VirusTotal.
 Example domain checked: webnotifications.net


Result

 VirusTotal reported 0 detections from security vendors at the time of analysis.
 However, the domain is not officially associated with Apple** and is commonly used for bulk notifications.

Important Note:
A domain showing “0 detections” does not guarantee legitimacy. Context such as brand mismatch, email behavior, and social engineering indicators are critical in phishing detection.

 Phishing Indicators Identified

 Spoofed sender domain
 Brand impersonation (Apple / iCloud)
 Urgency and fear-based language
 Generic call-to-action links (“click here”)
 Social engineering tactics


 Conclusion

The analyzed email exhibits multiple phishing characteristics including sender domain mismatch, brand impersonation, and urgency-driven messaging. Despite VirusTotal not flagging the domain as malicious, the overall email context confirms that this is a phishing attempt

Users should avoid interacting with such emails and should verify account-related alerts only through official websites.


Safety Note

This analysis was conducted strictly for educational and cybersecurity awareness purposes.
No links were clicked and no sensitive information was shared during this analysis.

