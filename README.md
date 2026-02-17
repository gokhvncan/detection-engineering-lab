# Detection Engineering Lab

## Scope
Development of MITRE-aligned detection rules.

## Covered Techniques
- T1110 - Brute Force
- T1003 - Credential Dumping
- T1059.001 - PowerShell

## Validation Method
- Sigma rule creation
- Conversion to Elastic query
- Testing via Atomic Red Team
- Alert validation in SIEM

## Detection Logic Example
If more than 5 failed logins from same IP within 3 minutes → Trigger alert
