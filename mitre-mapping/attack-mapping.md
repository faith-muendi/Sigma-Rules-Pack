# MITRE ATT&CK Mapping – Sigma Rules Pack

## Windows Credential Access

### Windows Brute Force Logon Attempts
- **Tactic:** Credential Access
- **Technique:** Brute Force (T1110)
- **Log Source:** Windows Security Logs
- **Event ID:** 4625

This rule detects repeated failed authentication attempts that may indicate
password guessing or credential stuffing attacks.
