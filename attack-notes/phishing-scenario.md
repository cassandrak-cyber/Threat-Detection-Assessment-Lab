# Phishing Initial Access Scenario

## Objective

Simulate a phishing-based attack that results in user execution of a malicious attachment.

## Attack Flow

1. User receives phishing email.
2. User opens attachment.
3. Microsoft Word launches PowerShell.
4. PowerShell downloads malicious content.
5. Attacker establishes persistence.
6. Credentials and sensitive data are targeted.

## ATT&CK Techniques

- T1566.001 Spearphishing Attachment
- T1204.002 User Execution
- T1059.001 PowerShell
- T1087 Account Discovery
- T1005 Data from Local System
