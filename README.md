Endpoint Security & System Hardening Lab

📌 Project Overview

This lab focused on implementing endpoint security controls and applying system hardening best practices within a Windows environment. The objective was to simulate real-world IT support and security tasks involving user access control, firewall configuration, malware protection, and patch management.

The lab reinforced foundational cybersecurity concepts relevant to IT support roles.

🛠 Technologies Used

Windows 10 Virtual Machine

Windows Defender

Windows Firewall

BitLocker

Event Viewer

Local Security Policy

PowerShell

🏗 Lab Environment

1 Windows 10 client VM

Local administrative account

Standard user account

Virtual internal network

🎯 Objectives

Configure endpoint security settings

Implement least-privilege access control

Enable disk encryption

Review system logs

Practice patch man
agement

Simulate malware detection

🔧 Key Tasks Performed
1️⃣ User Access Control

Created standard user account

Restricted administrative privileges

Tested privilege escalation limitations

Applied least-privilege principles

2️⃣ Windows Defender Configuration

Ran full system malware scan

Reviewed threat protection settings

Enabled real-time protection

Verified automatic updates

3️⃣ Firewall Configuration

Reviewed inbound and outbound rules

Disabled specific services for testing

Created custom firewall rule

Verified blocked traffic behavior
4️⃣ BitLocker Implementation

Enabled BitLocker encryption

Generated recovery key

Verified encryption status

Documented security benefits

5️⃣ Event Viewer Log Analysis

Reviewed Security logs

Identified login attempts

Reviewed system warnings and errors

Documented suspicious activity simulation

6️⃣ Patch Management

Reviewed Windows Update settings

Installed pending updates

Verified system patch status

Documented update process

🧪 Security Scenarios Tested

❗ Scenario: Unauthorized Access Attempt

Observation: Failed login attempts recorded in Security log
Action: Reviewed Event Viewer for Event ID related to failed logins

❗ Scenario: Malware Detection

Action: Ran Defender scan
Result: No threats found
Verification: Reviewed protection history

❗ Scenario: Restricted Admin Rights

Test: Attempted software install as standard user
Result: Blocked due to insufficient privileges
🔐 Security Principles Applied

Least Privilege

Defense in Depth

Endpoint Protection

Log Monitoring

Patch Management

📚 Key Takeaways

Administrative rights should be tightly controlled

Event logs provide visibility into system activity

Firewall rules significantly impact endpoint exposure

Regular patching is critical for security posture

🚀 Next Steps

Deploy basic SIEM (Splunk Free)

Automate user creation with PowerShell

Implement additional security baselines
