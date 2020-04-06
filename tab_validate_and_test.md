---
title: Validate_And_Test
layout:  null
tab: true
order: 2
tags: validate-test
---

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

![FSTM](/assets/images/cover_ofstm.png)

<br><br>
## [ByteSweep](https://wiki.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=ByteSweep)

### Project Leader(s)
- Matt Brown

### Description
ByteSweep is a Free Software IoT security analysis platform. This platform will allow IoT device makers, large and small, to conduct fully automated security checks before firmware is shipped.
