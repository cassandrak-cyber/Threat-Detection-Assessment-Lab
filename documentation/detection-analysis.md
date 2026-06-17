# Detection Analysis

## Objective

Identify behaviors associated with phishing-based initial access and credential theft.

## Key Indicators

### Email Activity

- Attachment delivery
- Suspicious sender domains
- Macro-enabled documents

### Process Activity

- WINWORD.exe spawning powershell.exe
- Excel spawning cmd.exe

### Authentication Activity

- Multiple failed logins
- Logins from unusual locations
- Privilege escalation attempts

## Investigation Workflow

1. Review email logs.
2. Validate attachment details.
3. Examine endpoint process activity.
4. Review authentication logs.
5. Contain affected systems.
6. Document findings.
