---

## Included Detection Rules

### Windows – Credential Access
- **Windows Brute Force Logon Attempts**
  - Detects repeated failed authentication attempts
  - Event ID: 4625
  - MITRE: T1110 (Brute Force)

### Windows – Execution
- **Suspicious PowerShell Execution**
  - Detects PowerShell usage with encoded or hidden execution flags
  - Event ID: 4688
  - MITRE: T1059.001 (PowerShell)

### Windows – Persistence
- **Registry Run Key Persistence**
  - Detects modification of common Windows Run and RunOnce keys
  - Event ID: 4657
  - MITRE: T1547.001 (Registry Run Keys)
