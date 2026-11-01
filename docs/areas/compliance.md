
# DEVICE COMPLIANCE MANAGEMENT

## Microsoft Intune Compliance Policies

Evaluate device health and security configuration to determine whether corporate endpoints meet organizational requirements.

<div class="grid cards" markdown>

-   :material-shield-check: **Device Compliance**

    Security and configuration evaluation.

-   :material-laptop: **Windows 11**

    Managed endpoint platform.

-   :material-cloud-check: **Microsoft Intune**

    Centralized compliance reporting.

-   :material-lock-check: **Access Control**

    Integration with Conditional Access.

</div>

<badge color="info">Technical reference</badge>

## 1. Objectives

- Define device compliance requirements.
- Evaluate Windows security settings.
- Monitor device compliance status.
- Understand the relationship between compliance and Conditional Access.

## 2. Architecture

<div class="grid cards" markdown>

-   **01 · Windows Device**

    Managed endpoint reports its configuration.

-   **02 · Intune Compliance Policy**

    Evaluates configured compliance requirements.

-   **03 · Compliance Evaluation**

    Device receives a compliance status.

-   **04 · Conditional Access**

    Can use device compliance as an access condition.

</div>

## 3. Key Configuration Areas

| Configuration | Purpose |
|---|---|
| Minimum OS version | Enforce supported Windows versions |
| Firewall | Require Windows Firewall |
| Antivirus | Require antivirus protection |
| Antispyware | Require antispyware protection |
| Secure Boot | Evaluate Secure Boot status |
| BitLocker | Require disk encryption |

## 4. Compliance States

| Status | Meaning |
|---|---|
| Compliant | Meets configured requirements |
| Not compliant | One or more requirements failed |
| In grace period | Remediation period is active |
| Not evaluated | Evaluation has not completed |

## 5. Validation

Validation should include:

- Reviewing the assigned compliance policy.
- Checking device compliance status.
- Reviewing individual setting results.
- Investigating non-compliance reasons.
- Confirming reporting in the Intune admin center.

## 6. Technical Considerations

- Compliance policies evaluate device requirements.
- Configuration profiles apply device settings.
- Conditional Access can restrict access based on compliance.
- Compliance status depends on policy evaluation and device reporting.

## Key Takeaways

- Compliance policies help assess endpoint security posture.
- Intune provides centralized compliance reporting.
- Conditional Access can use compliance as an access condition.
