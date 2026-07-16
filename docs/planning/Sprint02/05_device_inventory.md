# Device Inventory

---

# Overview

This document provides a baseline inventory of the organization's managed endpoint devices.

The inventory establishes the current device landscape prior to the Microsoft Intune implementation and will be used to support planning, enrollment, policy assignments, application deployment, and lifecycle management.

The inventory will be updated throughout the project as additional devices are enrolled and managed through Microsoft Intune.

---

# Assessment Objectives

The objectives of this assessment are to:

- Identify device types within the organization.
- Establish the current managed device estate.
- Assess device readiness for Microsoft Intune.
- Identify supported operating systems.
- Support enrollment planning.
- Assist with deployment planning.

---

# Device Categories

The Microsoft Intune implementation will support the following device categories.

| Device Type | Supported | Planned Management |
|--------------|-----------|-------------------|
| Windows 10 | Yes | Microsoft Intune |
| Windows 11 | Yes | Microsoft Intune |
| Android | Yes (where applicable) | Microsoft Intune |
| iOS / iPadOS | Yes (where applicable) | Microsoft Intune |
| macOS | Future Consideration | Microsoft Intune |

---

# Current Device Estate

The current environment consists primarily of corporate Windows devices used by employees for daily business operations.

A detailed inventory will be maintained internally and updated as devices are enrolled into Microsoft Intune.

---

# Device Ownership

The implementation supports the following ownership models.

| Ownership Type | Description |
|----------------|-------------|
| Corporate-Owned | Organization-owned devices managed through Microsoft Intune |
| Personally Owned (BYOD) | Personally owned devices enrolled according to organizational policy |
| Shared Devices | Shared organizational devices where applicable |

---

# Operating System Assessment

Supported operating systems include:

- Windows 10
- Windows 11
- Android
- iOS / iPadOS

Devices running unsupported operating systems will require review before enrollment.

---

# Device Readiness

Devices must meet the following minimum requirements before enrollment:

- Supported operating system.
- Internet connectivity.
- Microsoft Entra ID authentication.
- Eligible Microsoft Intune license.
- Organizational compliance requirements.

---

# Device Enrollment Strategy

The project will support multiple enrollment methods, including:

- Windows Autopilot
- Microsoft Entra ID Join
- Manual Enrollment
- Bring Your Own Device (BYOD)

The final enrollment method will be determined during the implementation phase based on the device type and ownership model.

---

# Device Lifecycle

The Microsoft Intune implementation will support the following device lifecycle stages:

1. Procurement
2. Registration
3. Enrollment
4. Configuration
5. Compliance
6. Application Deployment
7. Operational Support
8. Retirement
9. Secure Disposal

---

# Findings

The assessment identified the following observations:

- The environment primarily consists of Windows devices.
- Multiple enrollment methods will be required.
- Device ownership models must be considered during policy design.
- A standardized enrollment process will improve consistency.

---

# Recommendations

The following recommendations are made:

- Maintain an accurate device inventory.
- Standardize device naming conventions.
- Standardize enrollment procedures.
- Review unsupported devices before implementation.
- Validate all enrollment methods in the lab before production rollout.

---

# Assessment Outcome

The current device estate provides a suitable foundation for Microsoft Intune implementation.

A detailed operational inventory will be maintained separately and updated throughout the project lifecycle.

---