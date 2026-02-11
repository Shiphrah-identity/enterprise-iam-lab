⭐ Recruiters & Hiring Managers: Watch the 5-minute demo video for a full walkthrough → **[Demo Video Link]**

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
