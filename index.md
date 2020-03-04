---

layout: col-sidebar
title: OWASP Internet of Things
tags: iot
level: 3

---

![OWASP Internet of Things image](/assets/images/owasp_iotlogo.png)

The OWASP Internet of Things Project is designed to help manufacturers, developers, and consumers better understand the security issues associated with the Internet of Things, and to enable users in any context to make better security decisions when building, deploying, or assessing IoT technologies.

The project looks to define a structure for various IoT sub-projects separated into the following categories - **Seek & Understand**, **Validate & Test**, and **Governance**. Right now, you can find the following active and upcoming OWASP Internet of Things projects:

<br><br>
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
## [IoTGoat](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=IoTGoat)

### Project Leader(s)
- Aaron Guzman
- Fotios Chantzis
- Paulino Calderon

### Description
IoTGoat is a deliberately insecure firmware based on OpenWrt. The project’s goal is to teach users about the most common vulnerabilities typically found in IoT devices. The vulnerabilities will be based on the top 10 vulnerabilities as documented by OWASP: https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project. IoTGoat is expected to be released in 2020.

![IoTGoat](/assets/images/blue-logo-text.png)

<br><br><br>
# Validate & Test
## [Firmware Analysis Project](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=Firmware_Analysis)

### Project Leader(s)
- Craig Smith

### Description
The Firmware Analysis Project provides: Security testing guidance for vulnerabilities in the "Device Firmware" attack surface, Steps for extracting file systems from various firmware files, Guidance on searching a file systems for sensitive of interesting data, Information on static analysis of firmware contents, Information on dynamic analysis of emulated services (e.g. web admin interface), Testing tool links, and a site for pulling together existing information on firmware analysis

<br><br>
## [Firmware Security Testing Methodology (FSTM)](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=Firmware_Security_Testing_Methodology)

### Project Leader(s)
- Aaron Guzman

### Description
The Firmware Security Testing Methodology (FSTM) is composed of nine stages tailored to enable security researchers, software developers, consultants, hobbyists, and Information Security professionals with conducting firmware security assessments.

GitHub: https://github.com/scriptingxss/owasp-fstm

| **Stage** | **Description** |
|---|---|
| 1. Information gathering and reconnaissance | Acquire all relative technical and documentation details pertaining to the target device's firmware |
| 2. Obtaining firmware | Attain firmware using one or more of the proposed methods listed |
| 3. Analyzing firmware | Examine the target firmware's characteristics |
| 4. Extracting the filesystem | Carve filesystem contents from the target firmware |
| 5. Analyzing filesystem contents | Statically analyze extracted filesystem configuration files and binaries for vulnerabilities |
| 6. Emulating firmware | Emulate firmware files and components |
| 7. Dynamic analysis | Perform dynamic security testing against firmware and application interfaces |
| 8. Runtime analysis | Analyze compiled binaries during device runtime |
| 9. Binary Exploitation | Exploit identified vulnerabilities discovered in previous stages to attain root and/or code execution |

<a href="/assets/images/cover_ofstm.png"><img src="/assets/images/cover_ofstm.png" width="75%"/></a>

<br><br>
## [ByteSweep](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=ByteSweep)

### Project Leader(s)
- Matt Brown

### Description
ByteSweep is a Free Software IoT security analysis platform. This platform will allow IoT device makers, large and small, to conduct fully automated security checks before firmware is shipped.

<br><br><br>
# Governance
## Catalogue of IoT regulatory policies and Certifications

### Project Leader(s)
- TBD

### Description
TBD

<br><br><br>
Not what you are looking for? Please have a look at the [Internet of Things Page Archive](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project).

Want to start a new IoT security project? Follow [https://www.owasp.org/index.php/Category:OWASP_Project#Starting_a_New_Project](https://www.owasp.org/index.php/Category:OWASP_Project#Starting_a_New_Project) or contact one of the leaders of the active projects.
