# Awesome-Identity-Governance-Administration-IGA

## Top Identity Governance & Administration (IGA) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Access Certification, Entitlement Management, Role Mining, Segregation of Duties, Identity Lifecycle & Compliance Governance*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Governance & Administration (IGA)**. These systems manage who has access to what, enforce least privilege, run access reviews and certifications, detect segregation-of-duties conflicts, and govern the full identity lifecycle for compliance and risk reduction.

**Examples** include Microsoft Entra ID Governance, SailPoint IdentityIQ / Identity Security Cloud, Saviynt, Omada Identity, IBM Security Verify Governance, Oracle Identity Governance, One Identity Manager, ClearSkies, Simeio, and ConductorOne (the category leaders).

**Open-source emphasis**: Full-featured IGA (access certification campaigns, role mining, SoD policy engines, large connector ecosystems) is almost exclusively commercial. Limited open-source options exist—most notably **OpenIAM**—along with governance-related capabilities in broader identity platforms. This section expands what is available while remaining realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Entra ID Governance](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id-governance)**  
  Native IGA capabilities inside Microsoft Entra (Access Reviews, Entitlement Management, Lifecycle Workflows) optimized for Microsoft-centric environments.

- **[SailPoint IdentityIQ / Identity Security Cloud](https://www.sailpoint.com/)**  
  Market-leading IGA platform offering deep access certification, AI-assisted reviews, role mining, SoD, and extensive connectors for enterprise applications.

- **[Saviynt](https://saviynt.com/)**  
  Cloud-native IGA platform strong in application governance (especially ERP), converged identity security, and compliance reporting.

- **[Omada Identity](https://www.omadaidentity.com/)**  
  Process-oriented IGA solution emphasizing best-practice workflows, access requests, and identity lifecycle management.

- **[IBM Security Verify Governance](https://www.ibm.com/products/verify-governance)**  
  IBM’s identity governance offering covering access certification, role management, and compliance within the broader Verify portfolio.

- **[Oracle Identity Governance](https://www.oracle.com/security/identity-management/)**  
  Oracle’s IGA suite for access requests, certifications, role management, and integration with Oracle and third-party systems.

- **[One Identity Manager](https://www.oneidentity.com/products/identity-manager/)**  
  Comprehensive identity governance and administration platform focused on lifecycle management and access control.

- **[ClearSkies](https://www.clearskies.com/)**  
  IGA and identity security platform providing governance, risk, and compliance capabilities for identity.

- **[Simeio](https://www.simeio.com/)**  
  Identity and access management services and solutions with strong governance and managed service offerings.

- **[ConductorOne](https://www.conductorone.com/)**  
  Modern identity governance platform focused on continuous access reviews, just-in-time access, and developer-friendly integrations.

## Open-Source GitHub Projects
- **[OpenIAM](https://www.openiam.com/)**  
  One of the few open-source platforms with dedicated IGA features—user lifecycle, access request workflows, access certification, role management, and provisioning connectors (Community and Enterprise editions).

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  Leading open-source IAM that can support basic access control, fine-grained authorization, and user federation; often extended for lighter governance use cases.

- **[Authentik](https://github.com/goauthentik/authentik)**  
  Modern open-source identity provider with strong authorization policies and self-service capabilities that can form part of a governance stack.

- **[Ory](https://github.com/ory)**  
  Modular open-source identity components (including Keto for fine-grained authorization) useful for building custom access-control and governance logic.

- **[Open Policy Agent (OPA) / Gatekeeper](https://github.com/open-policy-agent/opa)**  
  Policy engine widely used to enforce access and compliance rules that complement identity systems.

- **[SpiceDB / OpenFGA](https://github.com/authzed/spicedb)**  
  Open-source fine-grained authorization systems (Zanzibar-inspired) that support relationship-based access control useful in governance architectures.

- **[Documentation and OpenIAM / Keycloak governance patterns](https://www.openiam.com/)**  
  Guides for implementing access reviews, provisioning workflows, and basic certification processes with open tools.

- **[Self-hosted identity lifecycle scripts and connectors](https://github.com/)**  
  Community automation for joiner-mover-leaver processes and basic access attestation.

- **[Audit and compliance reporting frameworks](https://github.com/)**  
  Open tooling for generating access reports and evidence that support governance and audit requirements.

- **[Custom role-mining and SoD analysis notebooks](https://github.com/)**  
  Data-science oriented approaches to analyzing entitlements and detecting conflicts when commercial IGA is not available.

### Additional Strong Open-Source Options
- Using **OpenIAM** where true open-source IGA features (certification, provisioning, role management) are required.
- Combining **Keycloak** or **Authentik** with **OPA/SpiceDB** and custom workflows for lighter governance.
- Accepting that enterprise-scale access certification campaigns, AI-driven role mining, broad application connectors, and mature SoD policy engines remain the domain of commercial platforms (SailPoint, Saviynt, Omada, Entra ID Governance, etc.).
- Focusing open-source efforts on ownership of identity data, custom policy logic, and cost control for mid-sized or specialized environments.

**Frameworks for building custom systems**: Identity provider (Keycloak/Authentik/OpenIAM) → fine-grained authorization (OPA or SpiceDB) → custom access-request and review workflows → reporting for audits. Suitable for organizations with strong engineering capacity. Most regulated enterprises adopt commercial IGA for scale and proven compliance coverage.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity governance directly impacts security and regulatory compliance. Open-source or custom solutions require rigorous design, testing, and audit readiness. This list is not compliance or security advice.

---
**Made for identity governance teams, security architects, and open identity advocates.**
Let's keep access governed, least-privilege enforced, and as open as practical.
