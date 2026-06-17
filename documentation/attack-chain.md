# Attack Chain Analysis

## Scenario

An attacker attempts to gain initial access through a phishing email containing a malicious attachment.

## MITRE ATT&CK Mapping

### Initial Access

T1566.001 - Spearphishing Attachment

The attacker sends a malicious document to a targeted employee.

### Execution

T1204.002 - User Execution

The user opens the attachment and executes embedded content.

### Credential Access

T1056 - Input Capture

The attacker attempts to collect credentials.

### Discovery

T1087 - Account Discovery

The attacker enumerates local accounts.

### Collection

T1005 - Data from Local System

The attacker gathers sensitive information.

## Detection Opportunities

- Suspicious email attachments
- Office applications spawning command shells
- PowerShell execution
- Unusual authentication activity
- Unexpected file access
