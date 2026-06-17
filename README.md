# Threat Detection Assessment Lab

This project demonstrates threat emulation, attack chain analysis, detection engineering, and security documentation using MITRE ATT&CK methodologies.

## Project Objective

This project simulates a phishing-based attack chain and demonstrates how an attacker may leverage PowerShell execution, account discovery, and data collection techniques. The project maps attacker behavior to the MITRE ATT&CK framework and develops Sigma detection rules to identify malicious activity.

## Skills Demonstrated

- Threat Emulation
- MITRE ATT&CK Mapping
- Detection Engineering
- Security Analysis
- Incident Response
- Security Documentation

## Technologies & Frameworks

- MITRE ATT&CK
- Sigma Rules
- Windows Event Analysis
- Threat Detection Concepts
- Security Operations

## Repository Structure

```text
attack-notes/
detection-notes/
detection-rules/
documentation/
screenshots/
```

## Threat Emulation Workflow

```mermaid
flowchart LR
A[Phishing Email] --> B[User Opens Attachment]
B --> C[PowerShell Execution]
C --> D[Account Discovery]
D --> E[Data Collection]
E --> F[Detection Rule Triggered]
```

## MITRE ATT&CK Techniques

| Technique ID | Technique Name |
|-------------|---------------|
| T1566.001 | Phishing: Spearphishing Attachment |
| T1059.001 | PowerShell |
| T1087 | Account Discovery |
| T1005 | Data from Local System |
