# Module Descriptor - Data Management and Security

**Code:** NB-SOCE-L4-NEC-TT-09  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the data-modelling instruction line held at applied-use level and re-verified against the cluster common Data Models and Management Systems at specification (this module secures data, it does not teach data modelling as a common would); (7) the SQL continuation confirmed as applied use, not re-instruction (the SQL support strand from Applied Programming continues here).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-09 |
| Module title | Data Management and Security |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  discipline is Data with a data-security register - the security in the title is the lens, not a security block (Stage 2 ruling) |
| Feeder targets (named) | Level 5 Digital Forensics and Incident Analysis (data handling); Level 5 Cyber Law and Legal Frameworks (the privacy and regulatory seed); Level 6 AI-Augmented Security Operations (security-data literacy) |
| Prerequisites | Applied Programming for Networks and Security (the SQL support strand continues here) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To make data something the security practitioner can hold, query and above all protect. The module's discipline is data, read through a security lens: enough data modelling and database use to work with data competently, then the protection that is the point - classification, data-level access control, encryption at rest, backup and recovery - and the privacy and regulatory awareness that frames all lawful data handling. In the pathway's identity vocabulary, this module owns what data you may touch, the counterpart to the directory module's who you are. It is deliberately not a data-modelling common: modelling is taught only to the applied-use level a security practitioner needs, never as the standalone data-modelling instruction the cluster common carries, which this pathway does not take.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** data modelling and database use; securing data - classification, data-level access control, encryption at rest, backup and recovery; privacy and regulatory awareness.
>
> **Does NOT cover:** security operations (Network and Security Operations); offensive testing (Ethical Hacking and Application Security); directory identity (Windows Server and Directory Services owns who you are, this module owns what data you may touch); production database administration. Disambiguation for validation readers: distinct from the cluster common Data Models and Management Systems, which NEC does not carry - this is a pathway data-security module, not a data-modelling common.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Model and query data for applied tasks. | Apply |
| LO2 | Apply data-security controls - classification, access, encryption at rest. | Apply |
| LO3 | Explain privacy and regulatory obligations for data handling. | Understand |
| LO4 | Analyse a data holding for security and privacy risk and design proportionate controls. | Analyse / Design (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (model, query, apply) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Applied Programming for Networks and Security | The SQL continuation (review item 7): the SQL support strand begun there continues here as applied use, not re-instruction; programmatic data access is assumed, not re-taught. |
| Windows Server and Directory Services | The identity-vertical boundary, quoted: that module owns who you are; this module owns what data you may touch. Authenticated identity is assumed; this module governs its data reach. |
| Data Models and Management Systems (cluster common - NOT carried by NEC) | The disambiguation seam (review item 6): the common teaches data modelling as standalone instruction; this pathway does not carry it, and this module teaches modelling only to applied-use level under a security lens. The two are not interchangeable for validation readers. |
| Network and Security Operations | Data protection here is a data-platform discipline, not a monitored-operations one; security operations remain wholly theirs. |
| Ethical Hacking and Application Security | Offensive testing of data platforms is theirs; this module is protective only. |
| Level 5 Digital Forensics and Incident Analysis / Cyber Law and Legal Frameworks | Named feeders: data-handling competence and the privacy-and-regulatory seed respectively. |
| Level 6 AI-Augmented Security Operations | Named feeder: security-data literacy - the ability to hold and reason about security data - is seeded here. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Data modelling for applied use: the relational model at working depth | 6 |
| U2 | Database use and querying: applied SQL continued | 9 |
| U3 | Data classification and data-level access control | 9 |
| U4 | Encryption at rest | 6 |
| U5 | Backup and recovery | 6 |
| U6 | Privacy and regulatory awareness for data handling | 9 |
| U7 | Data protection in practice: assessing a holding and designing controls | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U2 through U5 run laboratory-integrated against supplied datasets, and the A-3 practicals component carries the applied data-security time. U1 and U2 are held at applied-use level by design (review item 6): modelling and querying are taught to the working depth a security practitioner needs, not as the standalone data-modelling instruction the cluster common owns.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across data use, the security controls and the privacy and regulatory strand.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Timed applied tasks at the workstation: data queried, classification and access controls applied, encryption at rest configured against a supplied dataset, with a maintained evidence log | Individual; in-class; graded | LO1, LO2 | 30 |
| CW-I-Home | Data-protection case: a supplied data holding assessed for security and privacy risk, with a designed set of proportionate controls and a justification referencing the regulatory obligations; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO2, LO4 | 35 |
| EX | Written examination: applied data modelling and querying, data-security controls, privacy and regulatory obligations; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Hoffer, J. A., Ramesh, V. and Topi, H., Modern Database Management (Pearson) - selected chapters only, for the applied-use modelling and querying strand (U1, U2); not read as a full data-modelling course.
- Harrington, J. L., Relational Database Design and Implementation (Morgan Kaufmann) - applied-use support (U1).
- ISO/IEC 27001 and 27002 guidance materials - named reference for the classification and controls strand (U3, U4).
- Voigt, P. and von dem Bussche, A., The EU General Data Protection Regulation (GDPR): A Practical Guide (Springer) - the privacy and regulatory strand (U6), read alongside applicable local data-protection law confirmed at teaching-plan stage.
- School-produced dataset and laboratory guides (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a data-management domain with a data-security emphasis; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 5 |
