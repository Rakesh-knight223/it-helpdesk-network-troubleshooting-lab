
# Windows Performance Troubleshooting Report

## 1. Ticket Information

- Ticket ID: INC-001
- Category: Windows Performance
- Environment: Windows 11 Pro, 64-bit
- Status: Initial diagnostics completed
- Scenario: Educational troubleshooting exercise

## 2. Reported Issue

The exercise investigates a potential Windows performance
problem using built-in system diagnostic tools.

No specific performance fault has yet been confirmed.

## 3. System Information

- Operating system: Windows 11 Pro
- Processor: AMD Ryzen 5 7520U with Radeon Graphics
- Installed memory: Approximately 16 GB
- Storage: NVMe SSD
- System architecture: 64-bit

## 4. Diagnostic Findings

| Metric | Observation |
|---|---|
| CPU utilisation | 9% at capture time |
| Memory utilisation | 65% (10.0/15.3 GB) |
| Disk activity | 0% at capture time |
| C: drive used | 231.39 GB |
| C: drive free | 501.55 GB |

## 5. Tools Used

- Task Manager
- Command Prompt
- systeminfo
- tasklist
- PowerShell Get-PSDrive

## 6. Initial Analysis

CPU utilisation and disk activity were low at the time
of observation. Memory utilisation was 65%.

These measurements do not establish a performance
bottleneck. Further investigation is required if the
user continues to experience slowness.

## 7. Next Investigation Steps

- Review Task Manager's Processes tab.
- Identify applications consuming significant memory.
- Check startup applications.
- Ask when the performance issue occurs.
- Repeat measurements while reproducing the reported issue.

## 8. Resolution

No changes have been made. Root cause and resolution
remain undetermined pending further evidence.

## 9. Validation

A follow-up performance test is required if an issue
can be reproduced.

## 10. Evidence

Screenshots of Task Manager, system information,
and available disk space are collected separately.

This report uses a personal Windows computer for an
educational exercise. No production systems were accessed.
