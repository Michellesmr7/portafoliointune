# Android Enterprise – Managed App Permissions

<badge color="success">Implemented and validated</badge>

## Project Overview

Configuration and deployment of managed application permissions for Shopify on Android Enterprise personally owned Work Profile devices using Microsoft Intune.

## Lab Environment

| Component | Configuration |
|---|---|
| Platform | Android Enterprise |
| Enrollment | Personally Owned Work Profile |
| Management | Microsoft Intune |
| Target application | Shopify |
| Policy type | Managed App Permissions |

## Permission Configuration

| Setting | Applied Value |
|---|---|
| Application | Shopify |
| External storage (read) | Auto deny |
| Configuration settings | Not configured |
| Connected apps | Not configured |
| Credential Provider | Not configured |

**Security configuration:** The external storage read permission was configured to be automatically denied for Shopify.

## Deployment Results

The policy deployment was monitored through the Microsoft Intune Device Install Status report.

**Deployment Status: Succeeded**

## Evidence

### Managed App Permissions Configuration

![Android managed app permissions configuration](../images/android-managed-devices-wp-apps.jpeg)

### Device Installation Status

![Android managed app permissions deployment status](../images/android-managed-app-permissions-status.jpeg)

*Screenshots captured from a personal Microsoft Intune lab tenant. Sensitive information has been redacted for privacy.*