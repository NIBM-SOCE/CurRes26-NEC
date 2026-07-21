# Module Descriptor - Applied Programming for Networks and Security

**Code:** NB-SOCE-L3-NEC-TT-03  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5 (V13 working-languages register); 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs); DELD descriptor v1.1 (K-SAM defence pattern)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the U4 concept register confirmed non-reducible at specification (O14 must-not-weaken rule: the mechanics alone are non-compliant).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-NEC-TT-03 |
| Module title | Applied Programming for Networks and Security |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours)  ·  held at 4, non-movable (cryptography touchpoint 1, must not weaken) |
| Feeder targets (named) | Scripting and Automation (Year 2); Level 5 scripting expectations across modules; Level 6 Network Architecture and Automation (NE track) and AI-Augmented Security Operations - the Python-first spine (V13); Level 5 Cybersecurity and Cryptography - cryptography touchpoint 1 (O14), the mechanics-and-concepts on-ramp |
| Prerequisites | Algorithmic Thinking (problem decomposition, pseudocode) |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To make the pathway's practitioners programmers of their own tools. The module is Python-first (V13), with Bash and SQL carried as working support, and every construct is taught inside networking and security applied contexts - parsing network data, automating small tasks, querying data, building simple tooling - rather than in abstract exercises. It deliberately is not a software-engineering module: production engineering sits outside the pathway's mission, and automation at scale belongs to Year 2. The module also carries the first of the pathway's two cryptography touchpoints: modular arithmetic is taught in code with the concepts named explicitly, so that encryption is met first as something computed and understood, not something invoked.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** Python-first programming (control flow, data structures, functions, file and data handling); Bash scripting support; SQL support (querying, basic manipulation); modular arithmetic taught in code with the concepts named explicitly - modular exponentiation, GCD, primes, and why each underpins encryption (O14 mechanics and register together, must not weaken); networking and security applied contexts throughout.
>
> **Does NOT cover:** production software engineering (outside NEC mission); automation at scale (Scripting and Automation, Year 2); formal cryptography (Level 5).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

### Cryptography Chain Position (standing obligation 1 / O14 - stated in both touchpoint descriptors)

This module is **cryptography touchpoint 1** of the Year 1 chain: the mechanics are taught in code with the concepts named explicitly - modular exponentiation, GCD, primes, and why each underpins encryption. Information Security Fundamentals, running in parallel, is touchpoint 2, connecting the same modular arithmetic to public-key meaning; Mathematical Thinking supplies elementary modular arithmetic as common support. **Level 5 Cybersecurity and Cryptography opens on a brief formal refresh** - that opening assumption is what this chain exists to satisfy. The concept register survives credit pressure at specification stage; the mechanics alone are non-compliant (must-not-weaken rule, applying to transfer students as to natives).

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Write Python programs applying core constructs to networking and security tasks. | Apply (K-SAM category 7, defended below) |
| LO2 | Automate simple tasks with Bash and query data with SQL. | Apply (K-SAM category 7, defended below) |
| LO3 | Implement and explain modular-arithmetic operations underpinning encryption. | Apply / Understand (implementation defended below) |

*Authored from the record stubs (NEC v1.1) unchanged; presented for ratification into the NEC record set, per the descriptor-stage LO device.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Information Security Fundamentals | Cryptography chain counterpart (parallel run): mechanics in code here, public-key meaning there; the two touchpoints reference the same modular arithmetic. |
| Mathematical Thinking (Tier 1) | Common support: elementary modular arithmetic is supplied there; this module computes with it in applied contexts. |
| Algorithmic Thinking (Tier 1) | Prerequisite seam: problem decomposition and pseudocode are assumed; this module renders them in Python. |
| Networking Fundamentals | Binary and hexadecimal fluency built there in the addressing context is exercised in code here; network-data contexts draw on its protocol vocabulary. |
| Scripting and Automation (Year 2) | Direct feeder: simple task automation begins here; automation at scale, scheduling and infrastructure-facing scripting are owned there (Bash and Python, V13). |
| Operating Systems and Infrastructure | Shell administration there is interactive command-line work; scripted automation lives here - the interactive/scripted seam is deliberate. |
| Level 5 Cybersecurity and Cryptography | Opening assumption: a brief formal refresh, satisfied by the two-touchpoint chain (position statement above). |
| Level 6 Network Architecture and Automation; AI-Augmented Security Operations | The Python-first spine (V13): the working-language commitment made here is the one those modules assume. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Python foundations: control flow, functions and data types | 12 |
| U2 | Data structures, file and data handling in Python | 9 |
| U3 | Networking applied contexts: reading and parsing network data, simple network clients | 9 |
| U4 | Modular arithmetic in code: modular exponentiation, GCD, primes - and why each underpins encryption | 9 |
| U5 | Bash scripting support: the shell as a programming environment | 9 |
| U6 | SQL support: querying and basic manipulation | 9 |
| U7 | Security applied contexts: log parsing and simple security tooling | 9 |
| | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10); every unit runs code-along, and the A-4 practicals component carries supervised programming time. U4's hour allocation and its concept register are protected at specification (review item 6): trimming may not touch this unit below the point where the concepts remain explicitly named and assessed.

**Language note (V13):** Python-first throughout; Bash and SQL as support strands, not co-equal languages. Bash work assumes the command-line norm established in Operating Systems and Infrastructure across both derivative families (thread platform ruling T1); SQL is exercised against supplied datasets with language-neutral host tooling.

### K-SAM Verb Defence (per NEC finding N8a, stated not assumed)

> **Defence:** LO1 ("Write"), LO2 ("Automate", "query") and the implementation half of LO3 ("Implement") sit above the Level 3 cognitive ladder, where application is formally a Level 4 register, but are defended under K-SAM category 7 (Information Usage and Management - transferable skills related to ICT): supervised construction of small programs and scripts against task specifications is a genuine ICT skill performance at this level, standard in first-year programming provision internationally. The explanatory half of LO3 sits at the conventional Level 3 register. This defence travels into the compliance narrative of the validation submission.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for integrity and breadth: individually verified command of constructs and of the encryption-underpinning concepts, independent of take-home tooling.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Programming portfolio: staged tasks across networking and security contexts, culminating in a small working toolkit with documented code; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO2 | 40 |
| PR-I-Class | Supervised programming practical: timed tasks at the workstation, including modular-arithmetic implementations | Individual; in-class; graded | LO1, LO3 | 25 |
| EX | Written examination: code reading and construction, Bash and SQL support strands, and the concepts underpinning encryption - modular exponentiation, GCD, primes and their roles; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO3 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Matthes, E., Python Crash Course (No Starch Press) - primary Python text (U1, U2).
- Sweigart, A., Automate the Boring Stuff with Python (No Starch Press) - the applied-automation register (U3, U7).
- Shotts, W., The Linux Command Line (No Starch Press) - the Bash support strand (U5); Bash-environment dependency stated.
- Beaulieu, A., Learning SQL (O'Reilly) - the SQL support strand (U6); selected chapters only.
- Paar, C. and Pelzl, J., Understanding Cryptography (Springer) - selected early sections only, as concept support for U4; not a formal-cryptography commitment.
- School-produced exercise sets and datasets (environment-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from an applied-programming-for-security domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 2 |
