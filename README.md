# Network Hardening Tools

## Description
This project focuses on identifying network vulnerabilities and implementing hardening strategies for a social media organization following a major data breach. The goal is to transition from a reactive security posture to a proactive, multi-layered defense system using industry-standard tools and methodologies.

## Identified Vulnerabilities
Based on the initial security audit, four critical weaknesses were identified:
* **Credential Sharing:** Employees were sharing passwords, leading to a loss of accountability.
* **Default Settings:** The database administrator password was set to a factory default, making it an easy target.
* **Unfiltered Traffic:** Firewalls lacked specific rules to filter incoming and outgoing network traffic.
* **Lack of Multi-Factor Authentication (MFA):** Access relied solely on single-factor passwords.

## Proposed Hardening Methods
To mitigate these risks and prevent future breaches, the following methods are recommended:

* **Password Policy (NIST Standards):** Implement password policies focusing on salting and hashing rather than just complexity.
* **Multi-Factor Authentication (MFA):** Require two or more forms of identity verification, such as biometrics or one-time passwords (OTP).
* **Firewall Maintenance & Port Filtering:** Establish strict rules to block unused ports and filter traffic to prevent unauthorized access.
* **Network Access Privileges:** Limit access to sensitive assets based on specific roles, groups, or IP addresses.

## Technical Incident Analysis
A specific network incident was analyzed where IT access to the main URL (`Yummierecepesforme.com`) was denied.
* **The Problem:** Analysis of UDP traffic showed that DNS resolution was failing.
* **The Cause:** The server returned **ICMP port unreachable** messages for **UDP port 53**.
* **Resolution Plan:** Verify if Port 53 is being blocked by internal firewall configurations or an external provider.

## Repository Files
* [Security Risk Assessment Report](Security%20risk%20assessment%20report.docx)
* [Cybersecurity Incident Report](Cybersecurity%20incident%20report%20network%20traffic%20analysis%20(1).pdf)
