# Module Descriptor - Network and Security Operations

**Code:** NB-SOCE-L4-NEC-TT-06  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the cleanly-defensive scope re-verified at specification against Ethical Hacking and Application Security (O19: no offensive tooling enters this module); (7) the wireless-defence and identity-defence halves confirmed against their attack-half counterparts.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-06 |
| Module title | Network and Security Operations |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  re-banded 4 to 3 (V9 arithmetic; hardening baseline moved to Windows Server and Directory Services) |
| Feeder targets (named) | Level 5 Security Audit and Testing; Level 5 Cybersecurity and Cryptography (defensive operations); Level 5 Digital Forensics and Incident Analysis (the SOC and incident-analysis half); Level 6 AI-Augmented Security Operations (the SOC content it ladders to) |
| Prerequisites | Information Security Fundamentals (security-operations vertical head); Networking Fundamentals |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To build the defender. This module takes the defensive-operations awareness seeded in Information Security Fundamentals and makes it operational practice: security events monitored and analysed across a network, the processes of a security operations centre understood and rehearsed, systems and networks hardened in the running rather than at first build, and the two defensive halves of the pathway's deliberate attack-defence splits owned here - identity defended (authentication monitoring, credential-attack detection, multi-factor authentication) and wireless defended (WPA2 and WPA3, segmentation, rogue-access-point detection, monitoring). The module is cleanly defensive by design: it is the blue-team seat, and nothing offensive enters it. The hardening baseline configuration itself now lives with the Windows directory module; what lives here is hardening as an operational discipline.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** security operations and monitoring; SOC awareness; system and network hardening in operation; identity defence - authentication monitoring, credential-attack detection, multi-factor authentication (identity vertical); wireless defence - WPA2 and WPA3, segmentation, rogue-access-point detection, wireless monitoring (the wireless-split defence half).
>
> **Does NOT cover:** the hardening baseline configuration itself (moved to Windows Server and Directory Services in the re-band); offensive testing (Ethical Hacking and Application Security); identity administration (Windows Server and Directory Services). This module is cleanly defensive (O19).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

### Attack-Defence Split Position (standing obligation - stated in both split descriptors)

This module owns the **defensive half** of the pathway's two policed attack-defence splits (O19 containment):

| Split | Defensive half (this module) | Attack half (Ethical Hacking and Application Security) |
|---|---|---|
| Wireless | WPA2 and WPA3, segmentation, rogue-access-point detection, wireless monitoring | capture, cracking, evil-twin |
| Identity | authentication monitoring, credential-attack detection, multi-factor authentication | credential attacks, Active Directory misconfiguration |

The split is deliberate and clean: each half is taught in exactly one module, the two are mutually referencing but non-overlapping, and neither imports the other's posture. Windows Server and Directory Services builds identity; this module defends it; Ethical Hacking and Application Security tests it.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Monitor and analyse security events across a network. | Apply |
| LO2 | Apply defensive controls for identity and wireless. | Apply |
| LO3 | Explain SOC processes and incident awareness. | Understand |
| LO4 | Analyse security event data to detect an incident and evaluate the defensive response. | Analyse / Evaluate (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (monitor, apply) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Information Security Fundamentals | The vertical head feeds the operational seat: the defensive-operations awareness taught there (its retention clause) is the assumed entry state; this module makes it practice. |
| Windows Server and Directory Services | The identity split, defence side (obligation above): that module builds identity and holds the hardening baseline configuration; this module defends identity in operation. Neither administers what the other owns. |
| Ethical Hacking and Application Security | The attack-defence mirror (O19): the wireless and identity attack halves are theirs, the defence halves are here; the two reference each other and overlap in neither. |
| Networking Fundamentals | Monitoring and analysis assume the protocol and addressing foundation taught there. |
| Level 5 Digital Forensics and Incident Analysis | Named feeder: the SOC and incident-analysis practice here is the half that module opens on. |
| Level 6 AI-Augmented Security Operations | Named feeder: the SOC content laddered here is what that module augments. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Security operations and the SOC: roles, processes and workflow | 6 |
| U2 | Monitoring and log analysis: sources, aggregation and detection | 9 |
| U3 | Hardening in operation: maintaining a secure running posture | 6 |
| U4 | Identity defence: authentication monitoring, credential-attack detection, multi-factor authentication | 9 |
| U5 | Wireless defence: WPA2 and WPA3, segmentation, rogue-access-point detection, monitoring | 9 |
| U6 | Incident awareness: detection to response, the defender's view | 6 |
| U7 | Security-operations tooling in the laboratory: detection and analysis workflow | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U2, U4, U5 and U7 run laboratory-integrated on defensive tooling, and the A-3 practicals component carries the monitoring and detection time. All laboratory work is defensive: detection, analysis and response, never offensive tooling (review item 6).

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across operations, monitoring, identity and wireless defence, and SOC process.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Timed defensive tasks at the workstation: monitoring configured, events analysed, defensive controls applied against task sheets, with a maintained evidence log | Individual; in-class; graded | LO1, LO2 | 30 |
| CW-I-Home | Incident-analysis case: a supplied event dataset analysed to detect and characterise an incident, delivered with a report evaluating the defensive response and recommending improvements; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO4 | 35 |
| EX | Written examination: security operations and SOC process, monitoring and detection, identity and wireless defence, incident awareness; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO2, LO3 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Bejtlich, R., The Practice of Network Security Monitoring (No Starch Press) - primary text for monitoring and detection (U2, U6).
- Sanders, C. and Smith, J., Applied Network Security Monitoring (Syngress) - the laboratory-workflow strand (U2, U7).
- Diogenes, Y. and Ozkaya, E., Cybersecurity - Attack and Defense Strategies (Packt) - the defence-side chapters only, for identity and operational defence (U3, U4).
- School-produced monitoring-laboratory guides and event datasets (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a security-operations domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 5 |
