# Incident Report: Suspicious Identity Activity

## Summary
Multiple failed authentication attempts were detected against a user account, consistent with credential attack behavior.

## Detection Method
Microsoft Entra Sign-In Logs.

## Timeline
- 10:32 PM – First failed login  
- 10:34 PM – Additional failed attempts  
- 10:36 PM – Investigation initiated  

## Indicators of Compromise
- User: contractor@tenant.onmicrosoft.com
- IP: xx.xxx.xxx.xxx
- Location: Unknown
- Activity: Multiple failed logins
- Client App: Browser
- Pattern: Repeated authentication failures
  
## Root Cause
Account targeted by repeated authentication attempts using invalid credentials.

## Impact
No successful compromise observed.

## Remediation
Implemented Conditional Access policy enforcing MFA and strengthening authentication controls.

## Lessons Learned
Identity telemetry is critical for early detection and proactive risk reduction.
