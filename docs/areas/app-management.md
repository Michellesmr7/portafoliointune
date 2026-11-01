
# APPLICATION MANAGEMENT

## Microsoft Intune Application Lifecycle

Manage, deploy and monitor applications across Windows endpoints using Microsoft Intune.

<div class="grid cards" markdown>

-   :material-package-variant: **Win32 Applications**

    Package and deploy Windows applications.

-   :material-microsoft-windows: **Microsoft Store Apps**

    Manage application distribution.

-   :material-download: **Application Deployment**

    Configure assignments and installation behavior.

-   :material-check-circle: **Detection & Monitoring**

    Validate installation and deployment status.

</div>

<badge color="success">Practical implementation available</badge>

## 1. Core Capabilities

| Area | Key topics |
|---|---|
| Packaging | Win32 Content Prep Tool |
| Configuration | Install and uninstall commands |
| Requirements | OS version and architecture |
| Detection | File, registry and MSI rules |
| Assignment | User and device groups |
| Monitoring | Installation status and troubleshooting |

## 2. Application Lifecycle

<div class="grid cards" markdown>

-   **01 · Prepare**

    Obtain and prepare the application installer.

-   **02 · Package**

    Generate the `.intunewin` package.

-   **03 · Configure**

    Define commands, requirements and detection rules.

-   **04 · Assign**

    Deploy to selected users or devices.

-   **05 · Monitor**

    Review installation and deployment status.

</div>

## 3. Win32 Application Deployment

A practical implementation is documented using 7-Zip x64 on Windows 11.

<badge color="success">Implemented and validated</badge>

**Project:** 7-Zip Win32 Application Deployment

- Application packaging using Microsoft's Win32 Content Prep Tool.
- Configuration in Microsoft Intune.
- Device group assignment.
- Installation and detection validation.

[View the 7-Zip implementation](../projects/win32-app-deployment.md)

## 4. Technical Knowledge

- Win32 application packaging
- Microsoft Store application deployment
- Application dependencies
- Supersedence
- Detection rules
- Assignment filters
- Application troubleshooting

## Key Takeaways

- Intune supports multiple application deployment types.
- Correct detection rules are essential for reliable deployment.
- Assignments determine the deployment target.
- Monitoring helps identify installation failures.
