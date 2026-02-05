# Windows Security Event Log Analysis Report  
**Task 12 **

---

## Target Environment
- Operating System: Windows 11
- Log Source: Windows Security Event Log
- Scope: Educational and self-testing only

---

## Objective
The objective of this task is to analyze Windows Security logs to identify
failed login attempts using Event Viewer and Event ID filtering.

---

## Event ID Analyzed
### Event ID 4625 – Failed Logon
This event is generated when a user fails to log in due to incorrect
credentials or unauthorized access attempts.

---

## Analysis Procedure
- Accessed Event Viewer
- Selected Windows Logs → Security
- Applied filter for Event ID 4625
- Reviewed event details including:
  - Date and time
  - Account name
  - Logon type
  - Failure reason

---

## Findings
- Multiple failed login attempts can be identified easily
- Logs provide detailed information useful for investigations
- Filtering improves efficiency during security audits

---

## Security Importance
Analyzing failed login events helps in:
- Detecting brute-force attempts
- Monitoring unauthorized access
- Improving incident response
- Strengthening system security awareness

---

## Conclusion
This task successfully demonstrated how Windows Event Viewer can be used
to analyze failed authentication attempts. Event ID filtering is a simple
yet powerful method for basic security monitoring.


