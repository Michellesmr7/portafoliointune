# Windows Security Baseline Deployment

<badge color="success">Implemented and validated</badge>

## Project Overview

This project demonstrates the deployment of a Microsoft Windows Security Baseline through Microsoft Intune.

## Lab Environment

| Component | Configuration |
|---|---|
| Platform | Windows 11 |
| Management | Microsoft Intune |
| Policy | Security baseline for Windows |
| Assignment | Windows devices |
| Test device | Windows 11 Virtual Machine |

## Security Configuration

The baseline uses Microsoft's recommended default configuration settings.

Security areas include:

- Microsoft Defender
- User Account Control (UAC)
- Local Security Authority (LSASS)
- Windows Firewall
- BitLocker
- SMB security
- Remote Desktop
- PowerShell logging
- Microsoft SmartScreen

## Deployment and Validation

The baseline was assigned to the Windows devices group.

Microsoft Intune reported:

| Status | Records |
|---|---:|
| Successful | 2 |
| Errors | 0 |
| Conflicts | 0 |
| In progress | 0 |

Both successful status records refer to the same virtual machine, `WINDOWS11`, reported under different accounts. They do not represent two separate devices.

## Evidence

### Microsoft Intune Deployment Status

![Windows Security Baseline deployment status](../images/windows-security-baseline-status.jpeg)

*Screenshot captured from a personal Microsoft Intune lab tenant. Sensitive information has been redacted for privacy.*
