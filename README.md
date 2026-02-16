⭐ Recruiters & Hiring Managers: Watch the 5-minute demo video → **[Demo Video Link]**

---

# 🔐 Enterprise IAM Lab – Identity Lifecycle & Access Governance Simulation
**Active Directory • Microsoft Entra ID • RBAC • MFA • Governance • PAM**

This repository documents a hands-on Identity & Access Management (IAM) lab that simulates real-world identity lifecycle workflows, access controls, and privileged access governance.

It demonstrates how organizations securely manage user identities, enforce least privilege, and satisfy compliance requirements using both cloud and on-prem technologies.

---

## 📊 Architecture Diagram

The diagram below shows the identity flow and major components in this lab:

```text
                  ┌───────────────┐
                  │    Users      │
                  └───────┬───────┘
                          │
                          ▼
                  ┌───────────────┐
                  │ Active        │
                  │ Directory     │
                  └───────┬───────┘
                          │
                          ▼
           ┌────────────────────────────────┐
           │  Microsoft Entra ID (Azure AD)  │
           └───────────┬───────────┬─────────┘
                       │           │
  ┌────────────────────▼─┐   ┌─────▼────────────────┐
  │ RBAC Groups & Policies│   │ Conditional Access & │
  │                        │   │ Multi-Factor Auth     │
  └────────────────────────┘   └──────────────────────┘
                       │
            ┌──────────▼──────────┐
            │ Access Reviews &   │
            │ Governance Controls │
            └──────────┬──────────┘
                       │
            ┌──────────▼──────────┐
            │  Privileged Access  │
            │   (PIM / PAM)       │
            └─────────────────────┘
## 🧰 Tech Stack

- Active Directory (Windows Server)
- Microsoft Entra ID (Azure AD)
- Role-Based Access Control (RBAC)
- Conditional Access & MFA
- Access Governance
- Privileged Access Management (PIM/PAM)
- CyberArk

## Skills Demonstrated

- Identity provisioning & lifecycle automation
- RBAC design and enforcement
- Conditional Access & MFA
- Governance & access reviews
- Privileged access controls

These skills align directly with real-world IAM Analyst and Cloud Security responsibilities in enterprise environments.

## 📖 Full Walkthrough Article
Read the detailed step-by-step lab breakdown on Dev.to:
[]

🎥 Full walkthrough: https://youtu.be/XXXXX

## Artifacts
- Identity Access Flow Diagram: docs/identity-access-flow.md
- Access Review Checklist: governance/access-review-checklist.md
- Evidence Pack:
  - images/slide1-ou-structure.png
  - images/slide2-rbac-assignment.png
  - images/slide3-rbac-enforcement.png
