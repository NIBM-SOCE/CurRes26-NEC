# Module Descriptor - Operating Systems and Infrastructure

**Code:** NB-SOCE-L3-NEC-TT-01  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs); DELD descriptor v1.1 (K-SAM defence pattern)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) dual-family laboratory environment provisioning (Red Hat and Debian derivatives, thread platform ruling T1, 20 Jul 2026).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-NEC-TT-01 |
| Module title | Operating Systems and Infrastructure |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Linux Server Administration (Year 2) - the administration substrate at depth; Windows Server and Directory Services (Year 2) - the Windows and domain-awareness on-ramp; Level 5 Digital Forensics and Incident Analysis - operating-system internals substrate (file systems, storage, memory, processes) |
| Prerequisites | Fundamentals of Computing (operational operating-system awareness); Digital Electronics and Logic Design assumed in parallel for hardware grounding |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To build the systems-administration substrate of the pathway. Students install, configure and administer operating systems - predominantly Linux, worked at the command line across both major derivative families - and come to understand processes, memory, storage and file systems from the administrator's view rather than the theorist's. Windows local identity and directory-service concepts are carried as a light awareness strand only: the identity-vertical on-ramp, deliberately not the bulk, which Year 2 owns. The module is honest about its scope limits - it is an administration module, not an operating-systems-theory module, and it teaches no programming.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** operating-system installation and configuration; processes, memory, storage and file systems from the administrator's view; users, groups, permissions and ACLs; services; shell administration - predominantly Linux, with Windows local identity and directory-service awareness carried as a light strand only (the identity-vertical on-ramp, not the bulk).
>
> **Does NOT cover:** digital logic, electronics and computer organisation (Digital Electronics and Logic Design); Windows Server, Active Directory Domain Services and domain administration (Windows Server and Directory Services, Year 2); programming (Applied Programming for Networks and Security).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Configure and administer a Linux operating system: users, permissions, storage and services. | Apply (K-SAM category 7, defended below) |
| LO2 | Explain operating-system internals - processes, memory, file systems - from an administration perspective. | Understand |
| LO3 | Demonstrate awareness of Windows local identity and directory-service concepts. | Understand (awareness) |
| LO4 | Carry out routine administration tasks at the command line across Red Hat and Debian derivative environments. | Apply (K-SAM category 7, defended below) |

*Authored from the record stubs (NEC v1.1) with LO4 added to carry the command-line and dual-family commitment (thread platform ruling T1); presented for ratification into the NEC record set, per the descriptor-stage LO device.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Digital Electronics and Logic Design | Policed mutual boundary (V2, standing obligation 3): "Digital Electronics and Logic Design owns logic, electronics, computer organisation and hardware literacy; Operating Systems and Infrastructure owns the systems-administration substrate, predominantly Linux. Neither crosses." |
| Windows Server and Directory Services (Year 2) | Identity vertical (standing obligation 2): this module carries Linux-led local mechanics with Windows and domain awareness only; Windows Server and Directory Services owns the Active Directory bulk - it "owns who you are". |
| Linux Server Administration (Year 2) | Direct feeder: the administration substrate taught here is taken to server depth there; nothing server-scale is anticipated here. |
| Applied Programming for Networks and Security | Programming is excluded here in full; shell administration in this module is interactive command-line work, while scripted automation begins in Applied Programming and matures in Scripting and Automation (Year 2). |
| Level 5 Digital Forensics and Incident Analysis | The internals strand (LO2) is the operating-system substrate the Level 5 module opens on: file systems, storage, memory and processes understood from the administrator's view. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Operating-system roles and structure; installation and boot | 6 |
| U2 | The command line: shells and core tools across Red Hat and Debian derivatives | 6 |
| U3 | Users, groups, permissions and ACLs | 9 |
| U4 | Processes and memory from the administrator's view | 9 |
| U5 | Storage and file systems | 9 |
| U6 | Services and service management | 6 |
| U7 | Windows local identity and directory-service awareness | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U2 through U6 are run with integrated hands-on command-line work, and the A-3 practicals component carries the laboratory administration time.

**Platform note (thread ruling T1, 20 Jul 2026):** delivery is command-line-first throughout, with graphical tooling secondary. Laboratory environments cover both Red Hat and Debian derivative families on a concept-once, practise-twice pattern: each administration concept is taught once and exercised in both families where conventions differ (package management, service management, configuration layout). Honest cost: dual-family portability is bought with single-family depth; the module produces administrators who transfer across families, not specialists in either, and Linux Server Administration (Year 2) supplies the depth.

### K-SAM Verb Defence (per NEC finding N8a, stated not assumed)

> **Defence:** LO1 ("Configure and administer") and LO4 ("Carry out routine administration tasks") sit above the Level 3 cognitive ladder, where application is formally a Level 4 register, but are defended under K-SAM category 7 (Information Usage and Management - transferable skills related to ICT): supervised laboratory administration of an operating system against task specifications is a genuine ICT skill performance at this level, standard in first-year systems provision internationally. The cognitive-domain outcomes (LO2, LO3) sit at the conventional Level 3 register. This defence travels into the compliance narrative of the validation submission.
>
> *Pattern note (MD only): the box follows the established Digital Electronics and Logic Design pattern (descriptor v1.1); the category 7 naming here follows 07_SLQF_Reference.md v1.1 - see the Batch 1 delivery note to master on the DELD gloss.*

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Laboratory administration tasks: timed workstation exercises against task sheets across both derivative families, with a maintained evidence log | Individual; in-class; graded | LO1, LO4 | 30 |
| CW-I-Home | Small-server build-and-configure case task with a configuration report; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2, LO4 | 30 |
| EX | Written examination: operating-system internals from the administration perspective, administration concepts, Windows local identity awareness; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO2, LO3 | 40 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Nemeth, E., Snyder, G., Hein, T. R., Whaley, B. and Mackin, D., UNIX and Linux System Administration Handbook (Addison-Wesley) - primary administration text, family-portable.
- Ward, B., How Linux Works (No Starch Press) - the internals-from-the-administrator's-view strand (U4, U5).
- Shotts, W., The Linux Command Line (No Starch Press) - command-line foundation (U2); Bash-environment dependency stated.
- Silberschatz, A., Galvin, P. B. and Gagne, G., Operating System Concepts (Wiley) - selected chapters only, for the LO2 internals register; not a course-long text.
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
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 1 |
