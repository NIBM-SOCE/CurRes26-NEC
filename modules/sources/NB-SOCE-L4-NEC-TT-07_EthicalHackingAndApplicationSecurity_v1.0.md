# Module Descriptor - Ethical Hacking and Application Security

**Code:** NB-SOCE-L4-NEC-TT-07  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the mandatory ethical and legal framing ratified into the specification (record obligation); (7) the retained defensive-validation counterweight confirmed present at specification (standing obligation - the module keeps its defensive-validation half despite the offensive-led title).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-07 |
| Module title | Ethical Hacking and Application Security |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  name confirmed at v8.1 Stage 2 (working name at design was Applied Security Testing); realises the Level 4 part of mitigation M3 |
| Feeder targets (named) | Level 6 Applied Ethical Hacking (EH track) - the primary offensive feeder; Level 5 Security Audit and Testing (ladders by intent); the application-security strand upward into Levels 5 and 6 |
| Prerequisites | Information Security Fundamentals (security concepts, IAM); Web and Internet Technologies (web fundamentals for web attacks); Applied Programming for Networks and Security (scripting for tooling) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To build the ethical attacker, inside an explicit ethical and legal framework that is not an add-on but the condition of the module. Students learn the ethical-hacking method (reconnaissance, scanning, vulnerability assessment, exploitation basics), apply web attack techniques against the web fundamentals they already hold, and own the two offensive halves of the pathway's deliberate attack-defence splits - wireless attacked (capture, cracking, evil-twin) and identity attacked (credential attacks, Active Directory misconfiguration). The module is the pathway's recruitment-facing on-ramp to the Ethical Hacking track, but it is not offence-only: a defensive-validation counterweight is retained by design, so that every tested vulnerability is closed by a validated defence and the attacker learns to think as the defender must. Malware analysis and reverse engineering are consciously deferred to Level 6 research territory.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** ethical-hacking method (reconnaissance, scanning, vulnerability assessment, exploitation basics); application security (web attack techniques, secure-testing concepts); wireless attacks - capture, cracking, evil-twin (the wireless-split attack half); identity and credential attacks and Active Directory misconfiguration (the identity-vertical attack half); a retained defensive-validation counterweight (standing obligation - despite the offensive-led title, the module keeps its defensive-validation half).
>
> **Does NOT cover:** security operations and defence (Network and Security Operations); malware analysis and reverse engineering (deferred to Level 6 research territory, degree-record O2); identity administration (Windows Server and Directory Services).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

### Ethical and Legal Framing (mandatory, record obligation)

Offensive technique is taught only within an explicit ethical and legal framework, and that framing is a condition of the module rather than a preface to it. All practical work is confined to controlled laboratory environments and authorised targets; scope, authorisation, rules of engagement and responsible disclosure are taught before technique and assessed alongside it. This framing is ratified into the specification and is non-negotiable at every downstream stage.

### Attack-Defence Split Position (standing obligation - stated in both split descriptors)

This module owns the **offensive half** of the pathway's two policed attack-defence splits (O19 containment):

| Split | Attack half (this module) | Defensive half (Network and Security Operations) |
|---|---|---|
| Wireless | capture, cracking, evil-twin | WPA2 and WPA3, segmentation, rogue-access-point detection, wireless monitoring |
| Identity | credential attacks, Active Directory misconfiguration | authentication monitoring, credential-attack detection, multi-factor authentication |

The split is deliberate and clean: each half is taught in exactly one module, the two are mutually referencing but non-overlapping, and neither imports the other's posture. Windows Server and Directory Services builds identity; Network and Security Operations defends it; this module tests it. The retained defensive-validation counterweight (LO4) is within this module's own scope and is not the defensive half of the split - it validates that a tested vulnerability can be closed, without importing security-operations content.

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Conduct reconnaissance, scanning and vulnerability assessment ethically. | Apply |
| LO2 | Demonstrate common application and wireless attack techniques in a controlled laboratory. | Apply |
| LO3 | Assess identity and Active Directory misconfigurations. | Analyse (SLQF-04 analytical outcome) |
| LO4 | Validate defences against tested vulnerabilities. | Apply / Evaluate |

*Authored from the record stubs (NEC v1.1) unchanged; presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (conduct, demonstrate) sit within the Level 4 application register, and the analytical requirement (SLQF-04 cluster rule, V12) is carried by LO3's assessment of misconfigurations; no K-SAM category 7 defence is required. All practical outcomes are qualified by the ethical and legal framing above.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Information Security Fundamentals | Prerequisite in: security concepts and IAM are assumed; this module attacks what that module defines. |
| Web and Internet Technologies | Prerequisite in (the O16 relocation, receiving end): web-security awareness is theirs, application-security depth and offensive web testing are here; the web fundamentals built there are the target surface. |
| Applied Programming for Networks and Security | Prerequisite in: Python and Bash scripting is the tooling substrate for offensive work. |
| Network and Security Operations | The attack-defence mirror (O19): the wireless and identity attack halves are here, the defence halves are theirs; the two reference each other and overlap in neither. |
| Windows Server and Directory Services | The identity split, attack side: that module builds identity; this module attacks its misconfigurations; neither administers nor defends what the other owns. |
| Level 6 Applied Ethical Hacking | The primary offensive feeder (EH track): this module is the recruitment-facing on-ramp; the Active Directory attack-path depth built via Windows Server and Directory Services ladders through here into that module. |
| Level 5 Security Audit and Testing | Feeder by intent: the ethical-testing method here ladders into audit-and-testing there. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Ethical and legal framework: scope, authorisation, rules of engagement, responsible disclosure | 6 |
| U2 | Ethical-hacking method: reconnaissance, scanning, vulnerability assessment | 9 |
| U3 | Exploitation basics in a controlled laboratory | 6 |
| U4 | Application security: web attack techniques and secure-testing concepts | 9 |
| U5 | Wireless attacks: capture, cracking, evil-twin | 6 |
| U6 | Identity and credential attacks; Active Directory misconfiguration | 6 |
| U7 | Defensive validation: closing tested vulnerabilities and confirming the fix | 6 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U1 is taught first and its framing governs every subsequent unit. U2 through U7 run in controlled, isolated laboratory environments only, on authorised targets built for the purpose - the virtualisation laboratory substrate from Virtualisation Technologies is the intended containment. The A-3 practicals component carries the controlled-laboratory time; no technique is exercised outside the sanctioned environment (review item 6).

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for integrity and for the ethical and legal framing: individually verified method knowledge and framework command, independent of laboratory tooling.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Controlled-laboratory portfolio: a staged ethical engagement against an authorised laboratory target - reconnaissance to exploitation to defensive validation - documented with scope, authorisation and disclosure records; oral vehicle: Viva-defence | Individual; take-home (controlled-laboratory access); graded; oral vehicle: Viva-defence | LO1, LO2, LO4 | 40 |
| PR-I-Class | Timed method tasks at the workstation: scanning, assessment and a bounded exploitation exercise on a sanctioned target, with a maintained evidence log | Individual; in-class; graded | LO2, LO3 | 25 |
| EX | Written examination: the ethical and legal framework, ethical-hacking method, application and wireless attack concepts, identity misconfiguration, defensive validation; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3, LO4 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage. The ethical and legal framing is itself assessed and a serious breach in any component is a failing condition irrespective of technical merit.

## 6. Resources, Staff and Governance

### Indicative Reading

- Engebretson, P., The Basics of Hacking and Penetration Testing (Syngress) - primary method text (U2, U3).
- Stuttard, D. and Pinto, M., The Web Application Hacker's Handbook (Wiley) - the application-security strand (U4).
- Sikorski, M. and Honig, A., Practical Malware Analysis (No Starch Press) - boundary reference only, marking where this module stops and Level 6 begins; not taught.
- EC-Council and offensive-security community code-of-conduct and legal-framework materials - named resources for U1; used within the School's ethical-use policy.
- School-produced controlled-laboratory guides and authorised-target environments (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from an offensive-security domain within an explicit ethical and legal framework; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 5 |
