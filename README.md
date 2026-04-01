# SOC Analyst Project

## Brute Force Attack Detection

This project demonstrates detection of brute force attacks using Windows Security Logs by analyzing Event ID 4625.

The attack was simulated by generating multiple failed login attempts, and logs were analyzed using Windows Event Viewer to identify suspicious patterns.

## Detection Logic

- Multiple failed login attempts (Event ID 4625)
- Attempts within a short time period
- Same user account targeted

These patterns indicate a brute force attack.

Tools Used:
- Windows Event Viewer

Author: Abhishek Chouhan
