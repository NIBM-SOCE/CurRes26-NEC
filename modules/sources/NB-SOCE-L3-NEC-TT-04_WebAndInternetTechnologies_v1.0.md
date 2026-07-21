# Module Descriptor - Web and Internet Technologies

**Code:** NB-SOCE-L3-NEC-TT-04  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs); DELD descriptor v1.1 (K-SAM defence pattern)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the security-awareness scope check against Ethical Hacking and Application Security at specification stage (O16 relocation holds: awareness here, depth there).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-NEC-TT-04 |
| Module title | Web and Internet Technologies |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Ethical Hacking and Application Security (Year 2) - web fundamentals underpin the web-attack case studies; Level 5 Security Audit and Testing (web-security awareness); web context for Level 6 offensive work |
| Prerequisites | Fundamentals of Computing (systems awareness); runs in parallel with Networking Fundamentals for protocol context |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To give the security-facing practitioner working web literacy: how the web and internet are architecturally put together, how HTTP and HTTPS behave, how web applications are structured client and server side, and enough hands-on client-side construction to make that structure concrete. The module's focus is deliberately downgraded from development depth (O16): it builds the reader of web systems that Year 2's application-security work needs, not the builder of web applications, and web-security content stays at awareness level here - the depth and the offensive testing are owned by Ethical Hacking and Application Security.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** web and internet architecture; HTTP and HTTPS; HTML, CSS and client-server basics; how web applications are structured; web-security awareness (the module's downgraded focus, O16).
>
> **Does NOT cover:** application-security depth and offensive web testing (Ethical Hacking and Application Security, Year 2, per the O16 relocation); web-application development (outside NEC mission).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain web and internet architecture and core protocols. | Understand |
| LO2 | Build a simple client-side web page. | Apply (K-SAM category 7, defended below) |
| LO3 | Identify common web-security risks at an awareness level. | Understand (awareness) |

*Authored from the record stubs (NEC v1.1) unchanged; presented for ratification into the NEC record set, per the descriptor-stage LO device.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Ethical Hacking and Application Security (Year 2) | The O16 relocation seam: web-security awareness lives here, application-security depth and offensive web testing live there; this module supplies the web fundamentals its web-attack case studies open on. |
| Networking Fundamentals | Parallel-run protocol context: HTTP and HTTPS are read here against the transport and application-layer foundations taught there; DNS remains Networking Fundamentals territory at protocol level. |
| Fundamentals of Computing (Tier 1) | Systems awareness assumed at entry; this module begins at web-architecture level. |
| Level 5 Security Audit and Testing | Named feeder for the web-security-awareness strand (LO3): audit-and-testing work at Level 5 assumes a reader of web systems, which this module produces. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Web and internet architecture: clients, servers, intermediaries | 6 |
| U2 | HTTP and HTTPS: requests, responses, state, transport security | 9 |
| U3 | HTML and CSS foundations | 12 |
| U4 | Client-server structure: how web applications are put together | 9 |
| U5 | Web-security awareness: common risk classes and secure habits | 9 |
| U6 | Hosting and serving a page: from files to a reachable site | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U3 runs as integrated build-along sessions, and the A-3 practicals component carries the page-construction laboratory time.

### K-SAM Verb Defence (per NEC finding N8a pattern, stated not assumed)

> **Defence:** LO2 ("Build") sits above the Level 3 cognitive ladder, where application is formally a Level 4 register, but is defended under K-SAM category 7 (Information Usage and Management - transferable skills related to ICT): supervised construction of a simple client-side page against a brief is a genuine ICT skill performance at this level, standard in first-year web-literacy provision internationally. The cognitive-domain outcomes (LO1, LO3) sit at the conventional Level 3 register. This defence travels into the compliance narrative of the validation submission.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across the architecture, protocol and awareness strands.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| CW-I-Home | Client-side web page built to a brief, with a short annotation identifying the security-relevant choices made; oral vehicle: Presentation | Individual; take-home; graded; oral vehicle: Presentation | LO2, LO3 | 50 |
| EX | Written examination: web and internet architecture, HTTP and HTTPS behaviour, application structure, web-security awareness; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3 | 50 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Duckett, J., HTML and CSS: Design and Build Websites (Wiley) - primary text for the construction strand (U3).
- Robbins, J. N., Learning Web Design (O'Reilly) - broader web-structure support (U1, U4).
- McDonald, M., Web Security for Developers (No Starch Press) - the awareness strand (U5) at the intended non-specialist depth.
- MDN Web Docs (Mozilla) - named online reference resource for HTML, CSS and HTTP; connectivity-dependent.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a web-technologies domain with security awareness; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 1 |
