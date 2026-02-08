# Network_hardening_tools
Tools that aid in securing networks
# Network Hardening Tools

## Description
[cite_start]This project focuses on identifying network vulnerabilities and implementing hardening strategies for a social media organization following a major data breach[cite: 2]. [cite_start]The goal is to transition from a reactive security posture to a proactive, multi-layered defense system using industry-standard tools and methodologies[cite: 4, 5].

## Identified Vulnerabilities
Based on the initial security audit, four critical weaknesses were identified:
* [cite_start]**Credential Sharing:** Employees were sharing passwords, leading to a loss of accountability[cite: 2].
* [cite_start]**Default Settings:** The database administrator password was set to a factory default, making it an easy target[cite: 2].
* [cite_start]**Unfiltered Traffic:** Firewalls lacked specific rules to filter incoming and outgoing network traffic[cite: 2].
* [cite_start]**Lack of Multi-Factor Authentication (MFA):** Access relied solely on single-factor passwords[cite: 2].

## Proposed Hardening Methods
To mitigate these risks and prevent future breaches, the following methods are recommended:

* [cite_start]**Password Policy (NIST Standards):** Implement password policies focusing on salting and hashing rather than just complexity[cite: 5].
* [cite_start]**Multi-Factor Authentication (MFA):** Require two or more forms of identity verification, such as biometrics or one-time passwords (OTP)[cite: 4].
* [cite_start]**Firewall Maintenance & Port Filtering:** Establish strict rules to block unused ports and filter traffic to prevent unauthorized access[cite: 4, 5].
* [cite_start]**Network Access Privileges:** Limit access to sensitive assets based on specific roles, groups, or IP addresses[cite: 5].

## Technical Incident Analysis
[cite_start]A specific network incident was analyzed where IT access to the main URL (`Yummierecepesforme.com`) was denied[cite: 15].
* [cite_start]**The Problem:** Analysis of UDP traffic showed that DNS resolution was failing[cite: 9].
* [cite_start]**The Cause:** The server returned **ICMP port unreachable** messages for **UDP port 53**[cite: 9, 10].
* [cite_start]**Resolution Plan:** Verify if Port 53 is being blocked by internal firewall configurations or an external provider[cite: 20].

## Repository Files
For detailed reports and technical data, refer to the following documents:
* [Security Risk Assessment Report](Security%20risk%20assessment%20report.docx)
* [Cybersecurity Incident Report](Cybersecurity%20incident%20report%20network%20traffic%20analysis%20(1).pdf)
