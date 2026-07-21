# Module Descriptor - Enterprise Network Engineering

**Code:** NB-SOCE-L4-NEC-TT-01  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the Level 5 Advanced Network Engineering feeder confirmation (O11) recorded at specification stage; the fully-subscribed-core scope-refusal line holds.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-01 |
| Module title | Enterprise Network Engineering |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours)  ·  re-banded 4 to 3 (V9 arithmetic; former Enterprise Routing and Switching merged with Network Services and Wireless, O7 Option A) |
| Feeder targets (named) | Level 5 Advanced Network Engineering (the primary chain; O11 confirms the re-banded module still feeds it at specification stage); Level 6 Network Architecture and Automation (NE track) |
| Prerequisites | Networking Fundamentals (addressing, protocols, basic configuration) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To build the enterprise routing and switching core that the networking half of the award title stands on: segmented switched networks (VLANs, inter-VLAN routing, resilience), routed connectivity (static and single-area OSPF), and the traffic controls an enterprise edge requires (ACLs, NAT), with wireless carried at fundamentals level only. The module consumes network services and does not teach them - services implementation is owned by the server-administration modules, the concept by Networking Fundamentals. Its scope is deliberately and tightly subscribed: the protected core fills the full lecture allocation, and this is the first module in the programme at which any future scope pressure must be refused rather than absorbed.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** the SRWE core - VLANs, inter-VLAN routing, spanning tree, EtherChannel, static routing; selected ENSA core - single-area OSPF, ACLs, NAT; wireless fundamentals only (standards, SSID and association, basic access-point configuration - the three-way split minimum). The protected routing and switching core fully subscribes the 48 lecture hours; this is the tightest module in the programme and the first point at which future scope pressure must be refused (standing note).
>
> **Does NOT cover:** network-services implementation (redistributed to Networking Fundamentals for the concept, Linux Server Administration and Windows Server and Directory Services for implementation); wireless defence (Network and Security Operations) or wireless attack (Ethical Hacking and Application Security); full CCNA ENSA breadth such as WAN technologies and QoS depth (consciously out of perimeter).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Configure VLANs, inter-VLAN routing and switching resilience. | Apply |
| LO2 | Implement static and single-area OSPF routing. | Apply |
| LO3 | Apply ACLs and NAT to an enterprise topology. | Apply |
| LO4 | Design a segmented enterprise topology, justifying the switching, routing and access-control choices made. | Analyse / Design (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (configure, implement, apply) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Networking Fundamentals | Direct feeder in; the services redistribution seam (standing obligation 4): this module "teaches the routing and switching core and consumes services, it does not teach them". |
| Linux Server Administration / Windows Server and Directory Services | The services-implementation counterparts: what this module consumes as running services, they teach as implementation (Linux-side and Windows-side respectively). |
| Network and Security Operations / Ethical Hacking and Application Security | The wireless split (O19 extended): wireless fundamentals live here; wireless defence there, wireless attack there - neither returns to this module. |
| Level 5 Advanced Network Engineering | The primary feeder chain; O11 confirms at specification that the re-banded module still satisfies its entry assumptions. The CCNA posture holds (standing obligation 5): SRWE core plus selected ENSA, no full-coverage claim, NetAcad as delivery resource only. |
| Level 6 Network Architecture and Automation | The NE-track destination: the enterprise core built here is what automation later abstracts over. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | VLANs and trunking | 6 |
| U2 | Inter-VLAN routing | 6 |
| U3 | Switching resilience: spanning tree and EtherChannel | 9 |
| U4 | Static routing | 3 |
| U5 | Single-area OSPF | 9 |
| U6 | Access control lists | 6 |
| U7 | Network address translation | 3 |
| U8 | Wireless fundamentals: standards, SSID and association, basic access-point configuration | 3 |
| U9 | Integrated enterprise topology: bringing the core together in the laboratory | 3 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U1 through U7 run bench-integrated, and the A-3 practicals component carries the topology build time. **Scope protection (MD note):** the unit set above is the fully-subscribed protected core; specification-stage adjustment may move hours among these units in multiples of 3 but may not admit new topic territory - additions are refused here first, per the record's standing note.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across the routing and switching core.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-G-Class | Staged bench build of an enterprise topology: VLANs, inter-VLAN routing, resilience, OSPF, ACLs and NAT configured and verified at paired benches, with an individually maintained evidence log per student | Group (n = 2) at the bench; individually logged and graded; in-class | LO1, LO2, LO3 | 30 |
| CW-I-Home | Topology design task: a segmented enterprise design produced against a brief, with written justification of the switching, routing and access-control choices; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO4 | 25 |
| EX | Written examination: switching and routing operation, protocol behaviour, access control and translation, wireless fundamentals; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO2, LO3 | 45 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Odom, W., CCNA 200-301 Official Cert Guide, Volume 2 (Cisco Press) - laboratory-aligned support for the switching, OSPF, ACL and NAT core; used as a resource, not a specification.
- Perlman, R., Interconnections: Bridges, Routers, Switches, and Internetworking Protocols (Addison-Wesley) - selected chapters for the conceptual depth behind spanning tree and routing.
- Kurose, J. F. and Ross, K. W., Computer Networking: A Top-Down Approach (Pearson) - continuing conceptual reference from Networking Fundamentals.
- Cisco Networking Academy SRWE and ENSA curricula - School-arranged delivery resources only (equipment- and account-dependent), confirmed at teaching-plan stage.

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
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 3 |
