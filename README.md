# Network Hardening Tools 🛡️

## Project Scenario
In this project, I acted as a security analyst for a social media organization that recently suffered a major data breach. The goal was to perform a security risk assessment and implement strong network hardening practices based on the following identified vulnerabilities:

* **Password Sharing:** Employees shared credentials.
* **Default Credentials:** Database admin password was set to factory default.
* **Unfiltered Traffic:** Firewalls lacked traffic filtering rules.
* **Lack of MFA:** Multifactor authentication was not implemented.

## Hardening Solutions and Analysis
Below are the official reports developed for this exercise. You can view them directly in your browser:

# Network Hardening Tools and Strategies

This guide outlines essential security hardening tasks, descriptions, and their common use cases for securing network infrastructure.

---

## Hardening Overview Table

| Security Hardening Task | Description | Common Uses |
| :--- | :--- | :--- |
| **Baseline Configurations** | [cite_start]A documented set of specifications within a system used as a basis for future builds, releases, and updates[cite: 1]. | [cite_start]To restore a system to a previous baseline after a network outage or unauthorized changes[cite: 1]. |
| **Configuration Checks** | [cite_start]Updating the encryption standards for data that is stored in databases[cite: 1]. | [cite_start]To see if there are any unauthorized changes to the system[cite: 1]. |
| **Disabling Unused Ports** | [cite_start]Ports can be blocked on firewalls, routers, and servers to prevent potentially dangerous network traffic[cite: 1]. | [cite_start]To prevent malicious actors from entering the network before an incident, or after to prevent future attacks[cite: 1]. |
| **Encryption (Latest Standards)** | [cite_start]Rules or methods used to conceal outgoing data and decrypt incoming data[cite: 1]. | [cite_start]Implemented regularly to assess if standards are secure or updated after a data breach[cite: 1]. |
| **Firewall Maintenance** | [cite_start]Checking and updating security configurations regularly to stay ahead of potential threats[cite: 1]. | [cite_start]Updated in response to abnormal traffic or to protect against various DDoS attacks[cite: 1]. |
| **Hardware & Software Disposal** | [cite_start]Ensures all old hardware is properly wiped and outdated software is removed[cite: 1]. | [cite_start]Prevents access through unpatched devices or software that lack the latest security updates[cite: 1]. |
| **Multifactor Authentication (MFA)** | [cite_start]Requires a user to verify identity in two or more ways (e.g., password, OTP, fingerprint)[cite: 1]. | [cite_start]Protects against brute force attacks; usually set up once and then maintained[cite: 1]. |
| **Network Access Privileges** | [cite_start]Permitting, limiting, or blocking access privileges for people, roles, IPs, or MAC addresses[cite: 2]. | [cite_start]Reduces the risk of unauthorized users and traffic from accessing the internal network[cite: 2]. |
| **Network Log Analysis** | [cite_start]The process of examining network logs to identify events of interest, often using a SIEM[cite: 2]. | [cite_start]Used to track traffic or alert teams to abnormal activity before, during, or after an attack[cite: 2]. |
| **Password Policies** | [cite_start]NIST recommendations focus on salting and hashing rather than complex rotation[cite: 2]. | [cite_start]Prevents attackers from guessing passwords manually or using brute force scripts[cite: 2]. |
| **Patch Updates** | [cite_start]Software and OS updates that address specific security vulnerabilities within a product[cite: 2]. | [cite_start]Fixes security problems; applied to prevent attackers from targeting known vulnerabilities[cite: 2]. |
| **Penetration Test (Pen Test)** | [cite_start]A simulated attack that helps identify vulnerabilities in systems, networks, and applications[cite: 2]. | [cite_start]Used to protect and prevent against potential attacks[cite: 2]. |
| **Port Filtering** | [cite_start]A firewall function that blocks or allows certain port numbers to limit unwanted communication[cite: 2]. | [cite_start]Used to control network traffic and prevent attackers from entering a private network[cite: 2]. |
| **Removing Unused Apps/Services** | [cite_start]Disabling applications that are less likely to be maintained or updated with security features[cite: 3]. | [cite_start]Used to reduce potential vulnerabilities within a network[cite: 3]. |
| **Server & Data Storage Backups** | [cite_start]Protecting data assets by storing them in physical locations or cloud repositories[cite: 3]. | [cite_start]Used to restore lost data from attacks, human error, or equipment failures[cite: 3]. |

---

## Key Takeaways

* [cite_start]**Proactive Prevention**: Measures like Penetration Testing [cite: 2] [cite_start]and Disabling Unused Ports [cite: 1] are essential to stop attacks before they happen.
* [cite_start]**Identity Management**: MFA and strong Password Policies (following NIST standards) significantly reduce the success rate of brute force attacks[cite: 1, 2].
* [cite_start]**System Recovery**: Baseline configurations and regular backups ensure that a network can be restored quickly following an incident or unauthorized change[cite: 1, 3].

### 1. Security Risk Assessment Report
This document covers the hardening tools selected (NIST, MFA, Firewall rules) and the justification for their implementation.

<p align="center">
  <object data="./Hardening%20Tools%20Report.pdf" type="application/pdf" width="100%" height="600px">
    <p>Your browser does not support viewing PDFs directly. <a href="./Hardening%20Tools%20Report.pdf">Click here to download the report.</a></p>
  </object>
</p>

---

### 2. Cybersecurity Incident Report (Network Traffic Analysis)
This report includes some of the better hardening tools youe¿ can use up to date


<p align="center">
  <object data="./Cybersecurity%20incident%20report%20network%20traffic%20analysis%20(1).pdf" type="application/pdf" width="100%" height="600px">
    <p>Your browser does not support viewing PDFs directly. <a href="./Cybersecurity%20incident%20report%20network%20traffic%20analysis%20(1).pdf">Click here to download the report.</a></p>
  </object>
</p>

## Conclusion
The implementation of these hardening methods significantly reduces the organization's attack surface and protects customer data from future breaches.
