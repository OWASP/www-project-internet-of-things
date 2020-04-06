---
title: Seek_And_Understand
layout:  null
tab: true
order: 1
tags: seek-understand
---

# Seek & Understand
## [IoT Top 10 ](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=IoT_Top_10)

### Project Leader(s)
- Daniel Miessler
- Aaron Guzman
- Vishruta Rudresh
- Craig Smith

### Description
Top ten things to avoid when building, deploying or managing IoT systems.


![IoT Top 10 2018](/assets/images/OWASP-IoT-Top-10-2018-final.jpg)

| [OWASP IoT Top 10 2018](https://www.owasp.org/images/1/1c/OWASP-IoT-Top-10-2018-final.pdf) | Description |
| :--- | :--- |
| I1 Weak, Guessable, or Hardcoded Passwords | Use of easily bruteforced, publicly available, or unchangeable credentials, including backdoors in firmware or client software that grants unauthorized access to deployed systems. |
| I2 Insecure Network Services | Unneeded or insecure network services running on the device itself, especially those exposed to the internet, that compromise the confidentiality, integrity/authenticity, or availability of information or allow unauthorized remote control. |
| I3 Insecure Ecosystem Interfaces | Insecure web, backend API, cloud, or mobile interfaces in the ecosystem outside of the device that allows compromise of the device or its related components. Common issues include a lack of authentication/authorization, lacking or weak encryption, and a lack of input and output filtering. |
| I4 Lack of Secure Update Mechanism | Lack of ability to securely update the device. This includes lack of firmware validation on device, lack of secure delivery \(un-encrypted in transit\), lack of anti-rollback mechanisms, and lack of notifications of security changes due to updates. |
| I5 Use of Insecure or Outdated Components | Use of deprecated or insecure software components/libraries that could allow the device to be compromised. This includes insecure customization of operating system platforms, and the use of third-party software or hardware components from a compromised supply chain |
| I6 Insufficient Privacy Protection | User’s personal information stored on the device or in the ecosystem that is used insecurely, improperly, or without permission. |
| I7 Insecure Data Transfer and Storage | Lack of encryption or access control of sensitive data anywhere within the ecosystem, including at rest, in transit, or during processing |
| I8 Lack of Device Management | Lack of security support on devices deployed in production, including asset management, update management, secure decommissioning, systems monitoring, and response capabilities. |
| I9 Insecure Default Settings | Devices or systems shipped with insecure default settings or lack the ability to make the system more secure by restricting operators from modifying configurations. |
| I10 Lack of Physical Hardening | Lack of physical hardening measures, allowing potential attackers to gain sensitive information that can help in a future remote attack or take local control of the device. |

<br><br>
## [IoT Top 10 Mapping Project](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=OWASP_IoT_Top_10_2018_Mapping_Project)

### Project Leader(s)
- Aaron Guzman
- José A. Rivas

### Description
Provides mappings of the OWASP IoT Top 10 2018 to industry publications and sister projects.


| **OWASP IoT Top 10 2014** | **OWASP IoT Top 10 2018 Mapping** |
|---|---|
| I1 Insecure Web Interface | I3 Insecure Ecosystem Interfaces |
| I2 Insufficient Authentication/Authorization | I1 Weak, Guessable, or Hardcoded Passwords<br>I3 Insecure Ecosystem Interfaces<br>I9 Insecure Default Settings |
| I3 Insecure Network Services | I2 Insecure Network Services |
| I4 Lack of Transport Encryption/Integrity Verification | I7 Insecure Data Transfer and Storage |
| I5 Privacy Concerns | I6 Insufficient Privacy Protection |
| I6 Insecure Cloud Interface | I3 Insecure Ecosystem Interfaces |
| I7 Insecure Mobile Interface | I3 Insecure Ecosystem Interfaces |
| I8 Insufficient Security Configurability | I9 Insecure Default Settings |
| I9 Insecure Software/Firmware | I4 Lack of Secure Update Mechanism<br>I5 Use of Insecure or Outdated Components |
| I10 Poor Physical Security | I10 Lack of Physical Hardening |

<br><br>
## [IoTGoat](https://github.com/OWASP/IoTGoat)

### Project Leader(s)
- Aaron Guzman
- Fotios Chantzis
- Paulino Calderon

### Description
IoTGoat is a deliberately insecure firmware based on OpenWrt. The project’s goal is to teach users about the most common vulnerabilities typically found in IoT devices. The vulnerabilities will be based on the top 10 vulnerabilities as documented by OWASP: https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project. IoTGoat is expected to be released in 2020.

![IoTGoat](/assets/images/blue-logo-text.png)
