# Module Descriptor - Linux Server Administration

**Code:** NB-SOCE-L4-NEC-TT-02  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) dual-family depth allocation across units confirmed at specification (thread platform ruling T1: Red Hat and Debian derivatives both, concept-once practise-twice).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-02 |
| Module title | Linux Server Administration |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  retitled from Server Administration (Windows and Linux); Windows Server content ceded to Windows Server and Directory Services |
| Feeder targets (named) | Level 5 Advanced Network Engineering (server-side infrastructure); Level 5 Digital Forensics and Incident Analysis (Linux systems evidence); supports the automation spine into Scripting and Automation |
| Prerequisites | Operating Systems and Infrastructure (Linux administration substrate) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To take the Year 1 administration substrate to server depth. Students administer Linux as infrastructure: headless servers run from the command line, services managed for reliability, storage administered deliberately, and the Linux side of the programme's network services - DNS, DHCP, web and NTP - implemented rather than merely understood. Hardening is treated as ordinary administration, not an add-on: a server is configured secure, kept minimal and kept current as a matter of course. The module is Linux-scoped by design - the Windows half of the former combined module now lives in Windows Server and Directory Services - and it stops short of routing, switching and virtualisation platforms, which their own modules own.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** Linux server administration at depth - services, storage, shell administration, hardening; Linux-side network-services implementation - DNS, DHCP, web and NTP (the services redistribution).
>
> **Does NOT cover:** Windows Server and Active Directory Domain Services (Windows Server and Directory Services); routing and switching (Enterprise Network Engineering); virtualisation platforms (Virtualisation Technologies).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Administer and harden a Linux server environment. | Apply |
| LO2 | Deploy and configure core network services on Linux. | Apply |
| LO3 | Manage storage and services for reliability. | Apply |
| LO4 | Evaluate the security and reliability posture of a Linux server configuration and justify hardening decisions. | Evaluate (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (administer, deploy, configure, manage) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Operating Systems and Infrastructure | Direct feeder in: the Year 1 substrate (users, permissions, storage, services, the command line across both families) is assumed whole; this module begins at server scale. |
| Networking Fundamentals | The services redistribution seam (standing obligation 4): the protocol-level concept of DNS and DHCP is taught there; this module implements the Linux side. |
| Windows Server and Directory Services | The platform pair: Windows Server and Active Directory are wholly there; Linux administration is wholly here. Active-Directory-integrated DNS is theirs; general DNS service implementation is here. |
| Enterprise Network Engineering | This module implements the services that Enterprise Network Engineering consumes; routing and switching never enter here. |
| Virtualisation Technologies | Server administration here is platform-agnostic to its host; virtualisation platforms themselves are owned there. |
| Scripting and Automation | The automation spine support: administration is taught here as understood manual practice; its automation at scale is owned there (Bash and Python, V13). |
| Level 5 Digital Forensics and Incident Analysis | Named feeder: Linux systems evidence assumes an administrator's command of file systems, services and logs, which this module supplies at server depth. |
| Level 5 Advanced Network Engineering | Named feeder: server-side infrastructure competency underpinning the advanced networking chain. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Server installation and headless administration across Red Hat and Debian derivative families | 6 |
| U2 | Package and software management: conventions of both families | 6 |
| U3 | Services at depth: service management, units and logging | 6 |
| U4 | Storage administration: volumes, file systems and reliability concepts | 6 |
| U5 | Network-services implementation I: DNS and DHCP on Linux | 9 |
| U6 | Network-services implementation II: web and NTP | 6 |
| U7 | Hardening: secure baseline, access controls, updates and minimal services | 6 |
| U8 | Reliability operations: backup, monitoring basics and service recovery | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); every unit runs laboratory-integrated, and the A-3 practicals component carries the server build time.

**Platform note (thread ruling T1, 20 Jul 2026):** the dual-family commitment lands substantively in this module. Delivery is command-line-first throughout; each administration concept is taught once and practised in both Red Hat and Debian derivative environments where conventions differ - package management, service management and configuration layout. Honest cost, restated from the Year 1 descriptor: dual-family parity inside a 3-credit module trades single-family depth for portability; the module produces administrators who transfer across families, structured concept-once, practise-twice rather than as two parallel tracks.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across administration, services and hardening, individually verified.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Timed server-administration tasks at the workstation across both derivative families, with a maintained evidence log | Individual; in-class; graded | LO1, LO2, LO3 | 30 |
| CW-I-Home | Server build case: a Linux server deployed to a brief with core services implemented, delivered with a hardening-and-reliability report justifying the decisions taken; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO2, LO4 | 35 |
| EX | Written examination: server administration concepts, services implementation, storage and reliability, hardening rationale; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3, LO4 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Nemeth, E., Snyder, G., Hein, T. R., Whaley, B. and Mackin, D., UNIX and Linux System Administration Handbook (Addison-Wesley) - primary text, carried forward from Year 1 and now read at server depth.
- Hertzog, R. and Mas, R., The Debian Administrator's Handbook (Freexian) - the Debian-family reference (U1, U2).
- Red Hat Enterprise Linux product documentation (Red Hat) - named online resource for the Red Hat family; connectivity-dependent.
- Liu, C. and Albitz, P., DNS and BIND (O'Reilly) - selected chapters for the DNS implementation strand (U5).
- School-produced laboratory guides for both derivative families (kit-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a Linux systems-administration domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 3 |
