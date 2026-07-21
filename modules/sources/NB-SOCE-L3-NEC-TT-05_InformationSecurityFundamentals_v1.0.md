# Module Descriptor - Information Security Fundamentals

**Code:** NB-SOCE-L3-NEC-TT-05  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) operations-content retention re-verified at specification against Network and Security Operations' opening assumptions (rename-audit retention clause).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-NEC-TT-05 |
| Module title | Information Security Fundamentals |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Network and Security Operations (Year 2) - head of the security-operations vertical; Level 5 Cybersecurity and Cryptography - cryptography touchpoint 2 (O14), public-key meaning; Level 5 Security Audit and Testing; the identity vertical's Year 1 concept seat; serves the Level 6 AI modules through the GenAI-risk seed |
| Prerequisites | Fundamentals of Computing (systems and network awareness); runs in parallel with Applied Programming for Networks and Security for the cryptography concept |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To seat the cybersecurity half of the award title in genuine conceptual foundations: what security protects and why (the triad and its companions), who threatens it and how (the threat landscape and attack lifecycle, with the defensive-operations awareness Year 2 assumes), how encryption works at the level of meaning (connecting modular arithmetic to public-key cryptography), and who may do what (identity and access management, the identity vertical's Year 1 concept seat). A single deliberate unit introduces generative-AI tooling and its first risks. The module is conceptual and awareness-building by design: operations at depth, offensive testing and directory implementation are all Year 2 territory, and formal cryptography is Level 5's.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** the confidentiality-integrity-availability triad and information-security principles; the threat landscape, attack lifecycle and defensive-operations awareness (retention clause - this operations-facing content must not drift out under the rename, since Network and Security Operations assumes it and nothing else in Year 1 supplies it); symmetric and asymmetric encryption conceptually, connecting modular arithmetic to how public-key cryptography works (touchpoint 2); identity and access management concepts - authentication, authorisation, accounting, least privilege, role-based access control (the identity-vertical seat); a single short unit on generative-AI tooling and its first risks such as prompt injection and untrusted AI output (D6 / O17).
>
> **Does NOT cover:** security operations at depth (Network and Security Operations, Year 2); offensive testing (Ethical Hacking and Application Security, Year 2); directory implementation (Windows Server and Directory Services, Year 2); formal cryptography (Level 5). Distinct in level and register from ITB's Information Security, Assurance and Audit (a Level 4 assurance-and-audit module in a different pathway; no cohort overlap).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

### Cryptography Chain Position (standing obligation 1 / O14 - stated in both touchpoint descriptors)

This module is **cryptography touchpoint 2** of the Year 1 chain: symmetric and asymmetric encryption are treated conceptually, connecting the modular arithmetic taught in code in Applied Programming for Networks and Security (touchpoint 1, parallel run) to how public-key cryptography works - the same arithmetic, now carrying meaning. Mathematical Thinking supplies elementary modular arithmetic as common support. **Level 5 Cybersecurity and Cryptography opens on a brief formal refresh** - that opening assumption is what this chain exists to satisfy, and it must not weaken.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain information-security principles and the threat landscape. | Understand |
| LO2 | Describe symmetric and asymmetric encryption and the arithmetic underpinning public-key methods. | Understand |
| LO3 | Explain identity and access-management concepts. | Understand |
| LO4 | Identify first-order risks of generative-AI tooling. | Understand (awareness) |

*Authored from the record stubs (NEC v1.1) unchanged; presented for ratification into the NEC record set, per the descriptor-stage LO device. Verb audit run: all outcomes sit at or below the Level 3 cognitive ladder; no K-SAM category 7 defence is required for this module.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Applied Programming for Networks and Security | Cryptography chain counterpart (parallel run): mechanics in code there, public-key meaning here; both touchpoints reference the same modular arithmetic. |
| Mathematical Thinking (Tier 1) | Common support: elementary modular arithmetic supplied there underwrites the LO2 concept treatment here. |
| Network and Security Operations (Year 2) | Retention-clause seam: the defensive-operations awareness taught here is the opening assumption of the security-operations vertical; nothing else in Year 1 supplies it, and depth is owned there. |
| Windows Server and Directory Services (Year 2) | Identity vertical (standing obligation 2): the concept seat is here (authentication, authorisation, accounting, least privilege, role-based access control); directory implementation and the Active Directory bulk are owned there - it "owns who you are". |
| Ethical Hacking and Application Security (Year 2) | Offensive testing is excluded here in full; the threat-landscape treatment stays on the defender's side of the O19 containment line. |
| ITB - Information Security, Assurance and Audit | Distinct in level and register (Level 4 assurance-and-audit, different pathway; no cohort overlap); the record-set wording is carried to prevent false-duplicate readings at validation. |
| Level 5 Cybersecurity and Cryptography / Security Audit and Testing | Named degree-side feeders: the opening assumption (chain position above) and the audit-facing awareness strand respectively. |
| Level 6 AI modules | The GenAI-risk seed (LO4, U7): first-order risk awareness that the Level 6 AI-facing modules build on. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Information-security principles: the confidentiality-integrity-availability triad and its companions | 9 |
| U2 | The threat landscape and the attack lifecycle | 12 |
| U3 | Defensive-operations awareness: monitoring, detection and response at concept level | 9 |
| U4 | Cryptography concepts: symmetric and asymmetric encryption; modular arithmetic to public-key meaning | 12 |
| U5 | Identity and access management: authentication, authorisation, accounting, least privilege, role-based access control | 12 |
| U6 | The human factor in the threat landscape: social engineering and security awareness | 6 |
| U7 | Generative-AI tooling and its first risks: prompt injection and untrusted AI output | 6 |
| | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10); tutorials carry scenario and case discussion, and the A-4 practicals component carries structured case-laboratory work (analysis exercises, not offensive tooling). U3 is the retention-clause unit (review item 6): its scope is checked at specification against Network and Security Operations' opening assumptions and may not drift out.

### Teaching and Learning Hours (SLQF, V10)

| Component | Hours |
|---|---|
| Lectures (fixed) | 66 |
| Tutorials | 15 |
| Practicals / Laboratory | 30 |
| In-class assignments | 9 |
| Demonstration | 6 |
| Self-guided study | 74 |
| Total | 200 |

## 5. Assessment

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across the principles, cryptography-concept, identity and GenAI-risk strands.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Threat-and-defence case analysis: a briefed scenario analysed through the attack lifecycle with a defensive-operations response at awareness level, reported and presented; oral vehicle: Presentation | Individual; take-home; graded; oral vehicle: Presentation | LO1 | 30 |
| CW-I-Class | Structured supervised exercise: an identity-and-access scenario worked through, with cryptography-concept questions; oral vehicle: None | Individual; in-class (supervised); graded; oral vehicle: None | LO2, LO3 | 20 |
| EX | Written examination: principles and threat landscape, encryption concepts and the arithmetic underpinning public-key methods, identity and access management, generative-AI first risks; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO3, LO4 | 50 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Whitman, M. E. and Mattord, H. J., Principles of Information Security (Cengage) - primary text for principles, threat landscape and management concepts.
- Stallings, W. and Brown, L., Computer Security: Principles and Practice (Pearson) - selected chapters for the technical register of U3, U4 and U5.
- Singh, S., The Code Book (Fourth Estate) - narrative support for the cryptography-meaning strand (U4) at the intended conceptual depth.
- OWASP Top 10 for Large Language Model Applications (OWASP Foundation) - named online resource for U7; connectivity-dependent.
- School-produced case briefs and scenario packs, confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from an information-security domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 2 |
