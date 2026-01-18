# Incident Report: Suspicious Identity Activity

## Summary
Multiple failed login attempts detected against a user account indicating potential credential attack activity.

## Detection Method
Microsoft Entra sign-in logs.

## Timeline
- 10:32 – First failed login  
- 10:34 – Additional failed attempts  
- 10:36 – Investigation initiated  

## Indicators of Compromise
- User: Chris.Contractor  
- IP Address: xxx.xxx.xxx.xxx  
- Activity: Repeated failed authentication  
- Client App: Browser  

## Root Cause
Account targeted by repeated authentication attempts.

## Impact
No successful compromise observed.

## Remediation
Implemented Conditional Access policy enforcing MFA and blocking risky sign-ins.

## Lessons Learned
Identity telemetry is critical for early detection and response.
