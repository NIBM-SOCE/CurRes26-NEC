# Module Descriptor - Scripting and Automation

**Code:** NB-SOCE-L4-NEC-TT-08  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5 (V13 working-languages register); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the tooling-breadth unit held at orientation level and the Python automation core protected at specification (the re-band trim landed on breadth, not the core).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-08 |
| Module title | Scripting and Automation |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  re-banded 4 to 3 (V9 arithmetic; the trim lands on tooling breadth, not the Python automation core) |
| Feeder targets (named) | Level 6 Network Architecture and Automation (NE track); Level 5 scripting expectations across modules; Level 6 AI-Augmented Security Operations (automation pipelines) |
| Prerequisites | Applied Programming for Networks and Security (the Python and Bash spine, protected upstream) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To turn the Year 1 programmer into an automator of infrastructure. The working languages are Bash and Python (V13): what was learned as programming becomes automation of real networking, systems and security workflows - devices configured through code, checks and reports generated rather than compiled by hand, repetitive operations made repeatable, and the manual practice taught in the administration modules deliberately superseded by scripted equivalents. Infrastructure-as-code is introduced at working-concept level - declarative definitions and idempotence made concrete - and a closing orientation unit surveys the wider tooling landscape at breadth only, the dimension the module consciously trades away to protect its Python core. Programming fundamentals are not re-taught, and production software engineering remains outside the pathway's mission.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** automation of networking and systems tasks; scripting for infrastructure and security workflows; introductory infrastructure-as-code concepts; a breadth of automation tooling (the trimmed dimension - the core Python automation is protected).
>
> **Does NOT cover:** programming fundamentals (Applied Programming for Networks and Security, Year 1); production software engineering.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Automate networking and systems tasks with scripts. | Apply |
| LO2 | Apply automation to security and infrastructure workflows. | Apply |
| LO3 | Explain infrastructure-as-code concepts. | Understand |
| LO4 | Analyse a manual operational workflow and design its automation, justifying tool selection and naming residual risks. | Analyse / Design (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (automate, apply) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Applied Programming for Networks and Security | The spine in (V13, protected upstream): Python and Bash fundamentals are assumed whole and never re-taught; simple task automation begun there matures here to scale. |
| Operating Systems and Infrastructure / Linux Server Administration | The interactive/scripted seam completed: administration was taught there as understood manual practice; this module supersedes it with scripted equivalents - understanding first, automation second, by design. |
| Enterprise Network Engineering | The enterprise core built there is the object of network automation here: device configuration through code assumes its routing and switching competency. |
| Cloud Technologies | Adjacent at the provisioning seam: infrastructure-as-code concepts here are exercised against laboratory infrastructure; cloud platform services and models remain wholly theirs. |
| Level 6 Network Architecture and Automation | The NE-track destination: the automation practice built here is what that module architects with. |
| Level 6 AI-Augmented Security Operations | Named feeder: automation pipelines for security workflows (U5) are the assumed substrate. |
| Level 5 modules generally | The scripting expectation across Level 5 assumes this module's working fluency; the Bash strand assumes the command-line norm across both derivative families (thread platform ruling T1). |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Automation foundations: from interactive administration to scripted operations (Bash and Python) | 6 |
| U2 | Python automation core I: automating systems and services tasks | 9 |
| U3 | Python automation core II: network-device and API-driven automation | 9 |
| U4 | Bash in operations: pipelines, scheduling and glue | 6 |
| U5 | Scripting for security workflows: log handling, checks and reporting | 6 |
| U6 | Infrastructure-as-code concepts: declarative definitions and idempotence, worked introduction | 9 |
| U7 | Automation tooling landscape: orientation survey only | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U1 through U6 run code-along against laboratory infrastructure, and the A-3 practicals component carries supervised automation time. U2 and U3 are the protected Python core (review item 6); U7 is deliberately held at orientation level - it is the dimension the re-band trimmed, and the trade is recorded rather than hidden: breadth of tooling was surrendered to keep the core deep.

**Language note (V13):** Bash and Python are the working languages. Python carries the automation core; Bash carries operational glue and assumes the command-line norm established in Year 1 and Linux Server Administration across both Red Hat and Debian derivative families (thread platform ruling T1).

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for integrity and breadth: individually verified automation competency and concept command, independent of take-home tooling.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Automation portfolio: staged automations across systems, network and security contexts, culminating in a workflow automation with a design document analysing the manual process, justifying tool selection and naming residual risks; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2, LO4 | 40 |
| PR-I-Class | Timed automation tasks at the workstation: scripts written and run against supplied laboratory infrastructure | Individual; in-class; graded | LO1, LO2 | 30 |
| EX | Written examination: script reading and construction in Bash and Python, automation design reasoning, infrastructure-as-code concepts; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3, LO4 | 30 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Edelman, J., Lowe, S. S. and Oswalt, M., Network Programmability and Automation (O'Reilly) - primary text for the network-automation core (U3).
- Sweigart, A., Automate the Boring Stuff with Python (No Starch Press) - carried forward from Year 1, now read at workflow scale (U2).
- Morris, K., Infrastructure as Code (O'Reilly) - selected chapters for the concepts strand (U6); read at concept level, not as a platform commitment.
- Shotts, W., The Linux Command Line (No Starch Press) - the Bash operational strand (U4); Bash-environment dependency stated.
- School-produced laboratory infrastructure and exercise sets (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from an automation domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 4 |
