# Microsoft Entra ID Device Groups

---

# Overview

This document defines the Microsoft Entra ID security groups that will be used during the Microsoft Intune Proof of Concept (PoC).

The purpose of these groups is to provide a structured and controlled method for assigning Microsoft Intune policies, applications, configuration profiles, and compliance policies to pilot users and devices.

The groups created during this sprint are intended for validation and testing and will form the foundation for future production deployments.

---

# Objectives

The objectives of this document are to:

- Define pilot Microsoft Entra ID groups.
- Establish a consistent naming convention.
- Support policy and application targeting.
- Simplify administration.
- Prepare for scalable production deployment.

---

# Naming Convention

The following naming convention will be used throughout the project.

| Object | Naming Standard |
|---------|-----------------|
| User Group | GRP-INTUNE-PILOT-USERS |
| Device Group | GRP-INTUNE-PILOT-DEVICES |
| Windows Devices | GRP-WIN11-CORPORATE |
| Android Devices | GRP-ANDROID-CORPORATE |
| iOS Devices | GRP-IOS-CORPORATE |

This convention promotes consistency and simplifies administration.

---

# Pilot Groups

The following groups will be created during the Proof of Concept.

| Group Name | Purpose | Membership |
|------------|---------|------------|
| GRP-INTUNE-PILOT-USERS | Pilot user assignments | Assigned |
| GRP-INTUNE-PILOT-DEVICES | Pilot device assignments | Assigned |

Initially, assigned membership will be used to maintain full administrative control during testing.

Dynamic membership may be introduced during later implementation phases if appropriate.

---

# Group Assignment Strategy

The pilot groups will be used to assign:

- Configuration Profiles
- Compliance Policies
- Endpoint Security Policies
- Applications
- Scripts
- Device Management Policies

Assignments will be limited to pilot users and pilot devices during the Proof of Concept.

---

# Administration

Group administration will follow the principle of least privilege.

Administrative activities include:

- Group creation
- Membership management
- Assignment validation
- Periodic review

Group ownership should be restricted to authorized Microsoft Entra ID administrators.

---

# Validation Activities

The following validation activities will be completed:

- Verify group creation.
- Confirm group names.
- Validate assigned membership.
- Confirm pilot users.
- Confirm pilot devices.
- Verify Microsoft Intune visibility.

---

# Validation Evidence

## Expected Outcome

Pilot Microsoft Entra ID groups are successfully created and available for Microsoft Intune assignments.

## Validation Steps

- Create pilot user group.
- Create pilot device group.
- Add pilot members.
- Verify group synchronization.
- Confirm visibility within Microsoft Intune.

## Result

_To be completed during implementation._

## Screenshots

_To be added during implementation._

## Notes

_To be updated during implementation._

---

# References

- Microsoft Entra admin center
- Microsoft Intune admin center
- Microsoft Learn – Microsoft Entra groups
- Microsoft Learn – Assign apps and policies in Microsoft Intune

---

# Outcome

The Microsoft Entra ID pilot groups provide a controlled method for assigning Microsoft Intune configurations during the Proof of Concept.

These groups establish the foundation for policy targeting and will support future implementation activities as the deployment expands beyond the pilot phase.

---