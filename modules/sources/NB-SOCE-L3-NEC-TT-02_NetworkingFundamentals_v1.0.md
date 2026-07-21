# Module Descriptor - Networking Fundamentals

**Code:** NB-SOCE-L3-NEC-TT-02  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs); DELD descriptor v1.1 (K-SAM defence pattern)

> **Items requiring confirmation at review:** (1) the learning-outcome set (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the NetAcad delivery-resource arrangement (standing obligation 5: delivery resource only, no coverage claim).

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L3-NEC-TT-02 |
| Module title | Networking Fundamentals |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 3 (Year 1)  ·  4 credits  ·  200 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Enterprise Network Engineering (Year 2) - the routing and switching core builds directly on this; Level 5 Advanced Network Engineering (through Enterprise Network Engineering, feeder check O11); binary and hexadecimal in context supports addressing and downstream cryptographic work |
| Prerequisites | Fundamentals of Computing (operational network awareness, networks-weighted per V3.1) |
| Delivery mode | Session-based: 3-hour blocks (V10); 22 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 4-credit (A-4), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To build the networking foundation of the pathway whole and unhurried: how networks are modelled, how addressing works and is calculated, how the core protocols behave across the stack, and how a small network is physically and logically put together and configured at basic device level. Network services are taught here as protocols and concepts - what DNS and DHCP are and do - while their implementation is deliberately deferred to the Year 2 server-administration modules. The design target is the Level 5 Advanced Network Engineering feeder, not certification alignment: coverage tracks the CCNA ITN core because that core is the right foundation, and no certification claim is made or implied.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** the CCNA ITN core essentially whole - network models and Ethernet, IPv4/IPv6 addressing and subnetting, TCP/UDP, media and devices, basic device configuration; the network-services concept and application-layer view (DNS and DHCP as protocols, per the services redistribution); binary and hexadecimal in an addressing context.
>
> **Does NOT cover:** enterprise routing and switching configuration (Enterprise Network Engineering); network-services implementation (Linux Server Administration for Linux-side, Windows Server and Directory Services for Windows-side); wireless beyond the fundamentals concept.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Apply IPv4 and IPv6 addressing and subnetting to a small network. | Apply / quantitative interpretation (category 1) |
| LO2 | Explain the operation of core network protocols across the stack. | Understand |
| LO3 | Configure basic switch and end-device connectivity. | Apply (K-SAM category 7, defended below) |
| LO4 | Describe common network services at protocol level. | Understand |

*Authored from the record stubs (NEC v1.1) unchanged in substance; presented for ratification into the NEC record set, per the descriptor-stage LO device.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Enterprise Network Engineering (Year 2) | Direct feeder (standing obligation 4): this module carries the services concept and application-layer view; Enterprise Network Engineering "teaches the routing and switching core and consumes services, it does not teach them". |
| Linux Server Administration / Windows Server and Directory Services (Year 2) | The services redistribution counterparts: Linux-side services implementation lands in Linux Server Administration; Windows and Active-Directory-integrated DNS lands in Windows Server and Directory Services. This module supplies the protocol-level concept both open on. |
| Applied Programming for Networks and Security | Binary and hexadecimal fluency built here in the addressing context is exercised in code there; the cryptography chain itself (O14) is owned by Applied Programming and Information Security Fundamentals, not this module. |
| Fundamentals of Computing (Tier 1) | The raised, networks-weighted operational awareness (V3.1) is the assumed entry state; this module begins at protocol and configuration level, not at first exposure. |
| Level 5 Advanced Network Engineering | The named design target (via Enterprise Network Engineering); the CCNA posture holds: NetAcad ITN is usable as a delivery resource only, and records claim no full CCNA coverage (standing obligation 5). |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Network models, encapsulation and Ethernet | 9 |
| U2 | Binary and hexadecimal in the addressing context | 3 |
| U3 | IPv4 addressing and subnetting | 12 |
| U4 | IPv6 addressing | 6 |
| U5 | Transport layer: TCP and UDP | 6 |
| U6 | Media, devices and the physical layer | 6 |
| U7 | Basic device configuration: switch and end device | 12 |
| U8 | Network services at protocol level: DNS, DHCP and the application-layer view | 9 |
| U9 | Wireless fundamentals at concept level | 3 |
| | Total lecture hours | 66 |

66 lecture hours are delivered as 22 three-hour sessions (V10); U3 and U7 carry the heaviest hands-on load, with the A-4 practicals component carrying bench configuration time and the tutorials carrying addressing drill.

**Posture note (standing obligation 5):** the syllabus tracks the CCNA ITN core because that core is the correct Level 5 feeder foundation; the module makes no certification-alignment claim, and the Cisco NetAcad ITN curriculum is a delivery resource only, never the specification.

### K-SAM Verb Defence (per NEC finding N8a pattern, stated not assumed)

> **Defence:** LO3 ("Configure") sits above the Level 3 cognitive ladder, where application is formally a Level 4 register, but is defended under K-SAM category 7 (Information Usage and Management - transferable skills related to ICT): supervised bench configuration of switch and end-device connectivity against a task specification is a genuine ICT skill performance at this level, standard in first-year networking provision internationally. LO1's applied subnetting is quantitative interpretation within the Level 3 category 1 register (present and interpret quantitative data); the remaining outcomes (LO2, LO4) sit at the conventional Level 3 register. This defence travels into the compliance narrative of the validation submission.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth: the module's foundation role requires individually verified coverage across the whole protocol and addressing core.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-G-Class | Bench configuration tasks: switch and end-device connectivity built and verified at paired benches, with an individually maintained evidence log per student | Group (n = 2) at the bench; individually logged and graded; in-class | LO3 | 25 |
| CW-I-Class | Addressing and subnetting design exercise: an addressing plan produced under supervision for a given small-network brief; oral vehicle: None | Individual; in-class (supervised, stated-restricted resources); graded; oral vehicle: None | LO1 | 25 |
| EX | Written examination: network models, protocol operation across the stack, addressing, services at protocol level; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO4 | 50 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Kurose, J. F. and Ross, K. W., Computer Networking: A Top-Down Approach (Pearson) - primary conceptual text for models, protocols and the application-layer view.
- Odom, W., CCNA 200-301 Official Cert Guide, Volume 1 (Cisco Press) - laboratory-aligned support for addressing and device configuration; used as a resource, not a specification (posture note above).
- Tanenbaum, A. S., Feamster, N. and Wetherall, D., Computer Networks (Pearson) - selected chapters for media, the physical layer and transport.
- Cisco Networking Academy ITN curriculum - School-arranged delivery resource only (equipment- and account-dependent), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from an enterprise-networking domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 1 |
