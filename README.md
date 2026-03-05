# Secure Azure Environment Build (Small Business Project)

This project documents the end-to-end build of a secure Azure environment for a small business.  
The full deployment is demonstrated in a structured YouTube lab series.

---

## 🎯 Project Goals

- Build a structured Azure environment from scratch
- Apply least privilege access (RBAC)
- Implement secure networking and segmentation
- Configure monitoring and backups
- Apply governance controls (tags, locks, policy)
- Document architectural decisions

---

## 🧩 Scenario

**Company:** BluePeak Consulting (fictional)  
**Users:** ~25 employees  
**Workloads:** Windows Server VM, storage, backup, monitoring, governance  
**Environment:** Production

---

## 📺 YouTube Series

| Part | Topic | Video | Walkthrough |
|------|-------|-------|-------------|
| 1 | Planning & Architecture | (https://youtu.be/-Lg2ApqY_Ws?si=ygi290k0iYA2lkWp) | [Part 1](walkthrough/part-1-planning.md) |
| 2 | Resource Groups + Tags + Locks | (https://youtu.be/YICPzIMlhG8) | [Part 2](walkthrough/part-2-foundation.md) |
| 3 | Networking (VNet/Subnets/NSGs) | (https://youtu.be/q3EENwFaBq8) | [Part 3](walkthrough/part-3-networking.md) |
| 4 | VM Deployment + Secure Access | (https://youtu.be/fxGuteos9iA?si=SnKJQngKARf90-aU) | [Part 4](walkthrough/part-4-rbac.md) |
| 5 | Identity & RBAC | (add link) | [Part 5](walkthrough/part-5-compute.md) |
| 6 | Storage | (add link) | [Part 6](walkthrough/part-6-storage.md) |
| 7 | Backup | (add link) | [Part 7](walkthrough/part-7-backup.md) |
| 8 | Monitoring & Alerts | (add link) | [Part 8](walkthrough/part-8-monitoring.md) |
| 9 | Governance (Policy) | (add link) | [Part 9](walkthrough/part-9-governance.md) |
| 10 | Security Posture Review | (add link) | [Part 10](walkthrough/part-10-security.md) |

---

## 🏗 Architecture Overview

Architecture diagram located in:
`docs/architecture-diagram.png`

---

## 🧠 Skills Demonstrated

- Azure Administration (AZ-104 aligned)
- Networking & segmentation
- RBAC and scoped access control
- Backup and monitoring
- Governance and policy enforcement
- Cloud security baseline implementation
