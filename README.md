⭐ Recruiters & Hiring Managers: Watch the 5-minute demo video for a full walkthrough → [Demo Video Link]
---

## 🔐 Identity & Access Management Portfolio Project
Active Directory • Microsoft Entra ID • RBAC • MFA • Governance • PAM

---

# Enterprise IAM Lab – Identity Lifecycle & Access Governance Simulation

## Overview
This project simulates a real-world enterprise Identity & Access Management (IAM) environment using Active Directory, Microsoft Entra ID, and governance controls.

The goal was to gain hands-on experience with identity lifecycle management, RBAC, access reviews, and privileged access management — the same processes used in production environments.
## Architecture Diagram

```text
[ HR System ]
      |
      v
[ Entra ID / Azure AD ] -----> [ RBAC Groups ] -----> [ Applications ]
      |
      +----> Conditional Access + MFA
      |
      +----> PIM (Privileged Access)
      |
      +----> CyberArk Vault → Credential Rotation
```

---
## Architecture
On-Prem Active Directory → Microsoft Entra ID → Applications → Governance → PAM

Users are provisioned in AD/Entra, assigned through groups, protected with MFA, reviewed through governance, and privileged access is granted just-in-time.

---

## Technologies Used

- Active Directory (Windows Server 2022)
- Microsoft Entra ID (Azure AD)
- RBAC
- Conditional Access
- MFA
- Identity Lifecycle (JML)
- Access Reviews
- Privileged Identity Management (PIM/PAM)

---

## Lab Phases

### Phase 1 – Active Directory
- Domain controller setup
- Users, groups, OUs
- Group-based permissions

### Phase 2 – Entra ID
- Users and groups
- RBAC
- MFA
- Conditional Access
- App registrations (SSO)

### Phase 3 – Identity Lifecycle
- Joiner provisioning
- Role changes
- Immediate deprovisioning

### Phase 4 – Governance
- Access reviews
- Audit logs
### Phase 5 – Privileged Access
- Just-in-time admin roles
---
## Skills Demonstrated
- Identity provisioning & deprovisioning
- Access governance
- Least privilege enforcement
- RBAC design
- Cloud IAM administration
- Compliance-ready auditing

---

## Demo
Video walkthrough: [Link here]

---

## Lessons Learned
- Group-based access scales better than direct assignments
- JML workflows reduce risk
- MFA and Conditional Access are critical controls
- Governance is as important as provisioning
