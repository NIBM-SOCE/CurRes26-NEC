# Module Descriptor - Windows Server and Directory Services

**Code:** NB-SOCE-L4-NEC-TT-03  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the Kerberos concept-level scope checked at specification against Level 5 Cybersecurity and Cryptography's opening assumptions (no formal cryptography enters here).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-03 |
| Module title | Windows Server and Directory Services |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  the thirteenth Year 2 module, D1-justified at v8.1 Stage 2 |
| Feeder targets (named) | Level 5 Cybersecurity and Cryptography (authentication protocols, Kerberos); Level 5 Security Audit and Testing (access-control auditing); Level 6 Applied Ethical Hacking (Active Directory attack paths - the enterprise offensive spine); Level 6 Advanced Infrastructure Security (identity infrastructure, NE track) |
| Prerequisites | Operating Systems and Infrastructure (Windows and domain-awareness on-ramp); Networking Fundamentals (services concept and addressing). DNS is a taught dependency, self-contained via the services redistribution rather than assumed |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To make identity a thing students build and govern, not merely a concept they can define. The module takes the Year 1 awareness strand and the identity concept seat to enterprise implementation: Windows Server administered as infrastructure, Active Directory Domain Services deployed and run - domain controllers, organisational units, Group Policy, the lifecycle of domain identities - with Active-Directory-integrated DNS taught inside the module rather than assumed, and a Windows security baseline applied through Group Policy and secure configuration. The framing is identity as managed infrastructure: this module owns who you are in the enterprise. What it deliberately does not own: defending identity (Year 2's operations module), attacking it (the offensive module), or anything Linux.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** Windows Server administration; Active Directory Domain Services - domain controllers, organisational units, Group Policy, the domain identity lifecycle; Active-Directory-integrated DNS; a Windows security baseline via Group Policy and secure configuration (the hardening baseline transferred from Network and Security Operations in the re-band); identity as managed infrastructure.
>
> **Does NOT cover:** identity defence and monitoring (Network and Security Operations); identity attack (Ethical Hacking and Application Security); Linux administration (Linux Server Administration). This module owns who you are; Data Management and Security owns what data you may touch (identity-vertical boundary).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

### Identity Vertical Position (standing obligation 2 - the bulk owner's statement)

This module is the **implementation seat of the identity vertical**: Operating Systems and Infrastructure carries the Year 1 on-ramp (local mechanics, domain awareness), Information Security Fundamentals holds the Year 1 concept seat (authentication, authorisation, accounting, least privilege, role-based access control), and this module owns the Active Directory bulk - identity built, governed and lifecycled as enterprise infrastructure. Downstream, Network and Security Operations defends it, Ethical Hacking and Application Security attacks it, and Data Management and Security governs what the authenticated identity may touch. The vertical's degree-side destinations are named in the feeder targets above; the Active Directory attack-path chain into Level 6 Applied Ethical Hacking is the enterprise offensive spine and depends on the implementation depth taught here.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Deploy and administer Active Directory Domain Services. | Apply |
| LO2 | Design and apply Group Policy for a domain. | Design / Apply (SLQF-04 analytical outcome) |
| LO3 | Manage the domain identity lifecycle and integrated DNS. | Apply |
| LO4 | Apply a Windows security baseline. | Apply |

*Authored from the record stubs (NEC v1.1) unchanged; presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs sit within the Level 4 application register, and the analytical requirement (SLQF-04 cluster rule, V12) is carried by LO2's design element; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Operating Systems and Infrastructure | The on-ramp seam (standing obligation 2): Year 1 carries Linux-led local mechanics with Windows and domain awareness only; the Active Directory bulk begins here. |
| Information Security Fundamentals | The concept seat feeds the implementation seat: the identity and access-management concepts taught there are built here as running infrastructure. |
| Networking Fundamentals | The services redistribution seam (standing obligation 4): DNS as a protocol concept is theirs; Active-Directory-integrated DNS is taught here as a self-contained dependency, assumed from no one. |
| Linux Server Administration | The platform pair: Linux administration is wholly there; Windows Server and Active Directory are wholly here. |
| Network and Security Operations | The defence seam: the Windows hardening baseline lives here (transferred in the re-band); identity defence and monitoring live there and assume this module's implementation depth. |
| Ethical Hacking and Application Security | The attack seam (O19 containment): identity attack is theirs; nothing offensive enters this module. |
| Data Management and Security | The identity-vertical boundary, quoted: this module owns who you are; Data Management and Security owns what data you may touch. |
| Level 5 Cybersecurity and Cryptography | Named feeder: authentication protocols met here operationally (Kerberos at concept level, U7) are formalised there; review item 6 polices the line. |
| Level 6 Applied Ethical Hacking / Advanced Infrastructure Security | Named feeders: Active Directory attack paths and identity infrastructure respectively - the degree-side destinations of the vertical. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Windows Server administration foundations | 6 |
| U2 | Active Directory Domain Services: domain controllers, forest and domain structure | 9 |
| U3 | Organisational units and the domain identity lifecycle: users, groups, computers | 9 |
| U4 | Group Policy: design and application | 9 |
| U5 | Active-Directory-integrated DNS | 6 |
| U6 | The Windows security baseline: hardening via Group Policy and secure configuration | 6 |
| U7 | Identity as managed infrastructure: the authentication flow and Kerberos at concept level | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U2 through U6 run laboratory-integrated in a supplied domain environment, and the A-3 practicals component carries the domain build time. U7 stays at concept level by design (review item 6): the authentication flow is described so that Level 5 can formalise it; no cryptographic formalism enters here.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 48 |
| Tutorials | 12 |
| Practicals / Laboratory | 24 |
| In-class assignments | 9 |
| Demonstration | 3 |
| Self-guided study | 54 |
| Total | 150 |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across directory concepts, identity lifecycle and the security baseline.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-G-Class | Domain build laboratory: Active Directory deployed at paired benches - domain controller, organisational units, identities, integrated DNS - with an individually maintained evidence log per student | Group (n = 2) at the bench; individually logged and graded; in-class | LO1, LO3 | 30 |
| CW-I-Home | Group Policy design case: a policy set designed and applied for a briefed organisation, with written justification of the design choices and the security baseline applied; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO2, LO4 | 30 |
| EX | Written examination: directory structure and concepts, identity lifecycle, Group Policy behaviour, integrated DNS, the security baseline, the authentication flow at concept level; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3, LO4 | 40 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Desmond, B., Richards, J., Allen, R. and Lowe-Norris, A. G., Active Directory (O'Reilly) - primary directory-services text (U2, U3, U5).
- Moskowitz, J., Group Policy: Fundamentals, Security, and the Managed Desktop (Sybex) - the Group Policy strand (U4, U6).
- Stanek, W. R., Windows Server: The Definitive Guide - Pocket Consultant series (Microsoft Press) - administration reference (U1).
- Microsoft Learn documentation for Windows Server and Active Directory (Microsoft) - named online resource, version-current; connectivity-dependent.
- School-produced domain-laboratory guides (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a Windows enterprise-infrastructure domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 3 |
