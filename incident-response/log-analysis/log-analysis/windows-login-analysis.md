# Windows Login Attempt Analysis

## Objective
Identify suspicious login attempts using Windows event logs.

## Background
Windows records login activity in Event Viewer. Security analysts monitor these logs to detect brute force attacks.

Important Event IDs:
4624 – Successful login
4625 – Failed login attempt

## Investigation

Multiple Event ID 4625 entries indicate repeated failed login attempts. This can indicate a brute force password attack.

## Example Scenario

An attacker attempts multiple passwords on a user account.

Event logs show repeated 4625 events within a short period of time.

## Conclusion

Repeated failed logins from the same IP or account may indicate a brute force attack attempt.


