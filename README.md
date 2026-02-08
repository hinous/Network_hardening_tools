# Network Hardening Tools

## Project Scenario
In this project, I acted as a security analyst for a social media organization that recently suffered a major data breach. The goal was to perform a security risk assessment and implement strong network hardening practices based on the following identified vulnerabilities:

* Password Sharing: Employees shared credentials.
* Default Credentials: Database admin password was set to factory default.
* Unfiltered Traffic: Firewalls lacked traffic filtering rules.
* Lack of MFA: Multifactor authentication was not implemented.

---

## Hardening Solutions and Analysis
This guide outlines essential security hardening tasks, descriptions, and their common use cases for securing network infrastructure based on the organization's needs.

### Hardening Overview Table

| Security Hardening Task | Description | Common Uses |
| :--- | :--- | :--- |
| **Baseline Configurations** | A documented set of specifications within a system used as a basis for future builds, releases, and updates. | To restore a system to a previous baseline after a network outage or unauthorized changes. |
| **Configuration Checks** | Updating the encryption standards for data that is stored in databases. | To see if there are any unauthorized changes to the system. |
| **Disabling Unused Ports** | Ports can be blocked on firewalls, routers, and servers to prevent potentially dangerous network traffic. | To prevent malicious actors from entering the network before an incident, or after to prevent future attacks. |
| **Encryption (Latest Standards)** | Rules or methods used to conceal outgoing data and decrypt incoming data. | Implemented regularly to assess if standards are secure or updated after a data breach. |
| **Firewall Maintenance** | Checking and updating security configurations regularly to stay ahead of potential threats. | Updated in response to abnormal traffic or to protect against various DDoS attacks. |
| **Hardware & Software Disposal** | Ensures all old hardware is properly wiped and outdated software is removed. | Prevents access through unpatched devices or software that lack the latest security updates. |
| **Multifactor Authentication (MFA)** | Requires a user to verify identity in two or more ways (e.g., password, OTP, fingerprint). | Protects against brute force attacks; usually set up once and then maintained. |
| **Network Access Privileges** | Permitting, limiting, or blocking access privileges for people, roles, IPs, or MAC addresses. | Reduces the risk of unauthorized users and traffic from accessing the internal network. |
| **Network Log Analysis** | The process of examining network logs to identify events of interest, often using a SIEM. | Used to track traffic or alert teams to abnormal activity before, during, or after an attack. |
| **Password Policies** | NIST recommendations focus on salting and hashing rather than complex rotation. | Prevents attackers from guessing passwords manually or using brute force scripts. |
| **Patch Updates** | Software and OS updates that address specific security vulnerabilities within a product. | Fixes security problems; applied to prevent attackers from targeting known vulnerabilities. |
| **Penetration Test (Pen Test)** | A simulated attack that helps identify vulnerabilities in systems, networks, and applications. | Used to protect and prevent against potential attacks. |
| **Port Filtering** | A firewall function that blocks or allows certain port numbers to limit unwanted communication. | Used to control network traffic and prevent attackers from entering a private network. |
| **Removing Unused Apps/Services** | Disabling applications that are less likely to be maintained or updated with security features. | Used to reduce potential vulnerabilities within a network. |
| **Server & Data Storage Backups** | Protecting data assets by storing them in physical locations or cloud repositories. | Used to restore lost data from attacks, human error, or equipment failures. |

---

## Key Takeaways

* **Proactive Prevention**: Measures like Penetration Testing and Disabling Unused Ports are essential to stop attacks before they happen.
* **Identity Management**: MFA and strong Password Policies following NIST standards significantly reduce the success rate of brute force attacks.
* **System Recovery**: Baseline configurations and regular backups ensure that a network can be restored quickly following an incident or unauthorized change.

---

### 1. Security Risk Assessment Report
This document covers the hardening tools selected (NIST, MFA, Firewall rules) and the justification for their implementation.

[Link to Hardening Tools Report](./Hardening%20Tools%20Report.pdf)

### 2. Cybersecurity Incident Report (Network Traffic Analysis)
This report includes a detailed analysis of network traffic and the implementation of real-time monitoring tools.

[Link to Incident Report](./Cybersecurity%20incident%20report%20network%20traffic%20analysis%20(1).pdf)

## Conclusion
The implementation of these hardening methods significantly reduces the organization's attack surface and protects customer data from future breaches.
