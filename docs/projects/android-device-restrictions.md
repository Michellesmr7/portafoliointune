# Android Enterprise – Device Restrictions Policy

<badge color="success">Implemented and validated</badge>

## Project Overview

Configuration and deployment of an Android Enterprise Device Restrictions policy through Microsoft Intune on a personally owned device enrolled with a Work Profile.

## Lab Environment

| Component | Configuration |
|---|---|
| Platform | Android Enterprise |
| Enrollment | Personally Owned Work Profile |
| Management | Microsoft Intune |
| Policy type | Device Restrictions |

## Policy Configuration

| Setting | Applied Value |
|---|---|
| Require password | Enabled |
| Remaining settings | Default values |

## Deployment Results

The policy was assigned to the intended device group.

**Deployment Status: Succeeded**

## Evidence

### Device Restrictions Configuration

![Android Device Restrictions configuration](../images/android-device-restrictions-settings.jpeg)

### Policy Assignment Status

![Android Device Restrictions assignment status](../images/android-device-restrictions-status.jpeg)

*Screenshots captured from a personal Microsoft Intune lab tenant. Sensitive information has been redacted for privacy.*