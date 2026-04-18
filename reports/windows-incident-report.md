# Windows Server Incident Investigation Report

## Summary
A security investigation was conducted on a Windows Server system after detecting suspicious authentication activity and potential unauthorized access attempts.

## Tools Used
- Windows Event Viewer
- System logs analysis
- Windows Server environment

## Investigation Process
1. Reviewed security logs in Event Viewer
2. Identified repeated failed login attempts
3. Detected account lockout events
4. Analyzed process creation logs
5. Correlated events to determine attack pattern

## Key Findings
- Multiple failed login attempts from a single source
- Account lockout triggered due to brute-force behavior
- Suspicious process execution observed during investigation

## Conclusion
The activity was consistent with a simulated brute-force attack in a controlled lab environment. The investigation demonstrated the ability to detect, analyze, and respond to Windows-based security incidents.
