# Module Descriptor - Virtualisation Technologies

**Code:** NB-SOCE-L4-NEC-TT-04  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the container-introduction depth checked at specification against any degree-side container assumptions.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-04 |
| Module title | Virtualisation Technologies |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Cloud Technologies (Year 2, virtualisation underpins cloud); Level 5 Digital Forensics and Incident Analysis (forensics and incident environments); Level 5 Advanced Network Engineering (virtualised networking introduction, SDN awareness) |
| Prerequisites | Operating Systems and Infrastructure (operating-system substrate) |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To make virtualisation an instrument the pathway's practitioners hold, because nearly everything downstream stands on it: cloud platforms are virtualisation operated at provider scale, forensics and incident work runs in isolated virtual environments, and advanced networking increasingly means virtualised networking. Students deploy and manage virtual machines, virtual networks and virtual storage, meet containers at introductory level, and - the pathway's distinctive use - learn to build virtualisation into safe, isolated laboratory environments, the substrate on which the offensive and forensic modules depend. The module stays below the cloud line by design: what cloud platforms add (service and deployment models) belongs to Cloud Technologies, and production orchestration at scale is beyond the perimeter.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** hypervisors and virtual machines; virtual networking and storage; containers at introductory level; virtualisation as the forensics and laboratory substrate.
>
> **Does NOT cover:** cloud service and deployment models (Cloud Technologies); production orchestration at scale.
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Deploy and manage virtual machines and virtual networks. | Apply |
| LO2 | Explain virtualisation as the basis for cloud and laboratory environments. | Understand |
| LO3 | Configure introductory containerisation. | Apply |
| LO4 | Analyse workload and isolation requirements to select between machine and container virtualisation, justifying the design. | Analyse (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (deploy, manage, configure) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Operating Systems and Infrastructure | Direct feeder in: the operating-system substrate (installation, storage, services, the command line) is assumed; this module virtualises it. |
| Cloud Technologies | The progression seam: virtualisation underpins cloud, and this module ends where cloud begins - service and deployment models are wholly theirs; hypervisor and container internals are wholly here. |
| Linux Server Administration | The mirror seam: server administration is theirs and platform-agnostic to its host; virtualisation platforms are here and content-agnostic to their guests. |
| Level 5 Digital Forensics and Incident Analysis | Named feeder: forensics and incident environments assume the isolated-laboratory substrate built here (U6). |
| Level 5 Advanced Network Engineering | Named feeder: the virtualised-networking introduction and SDN awareness carried in U3 open its virtual-network treatment. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Virtualisation concepts and hypervisor types | 6 |
| U2 | Virtual machines: deployment, lifecycle, images and snapshots | 9 |
| U3 | Virtual networking: switches, segments and virtualised topologies (SDN awareness) | 9 |
| U4 | Virtual storage | 6 |
| U5 | Containers at introductory level: images, containers and composed services | 9 |
| U6 | Virtualisation as the laboratory and forensics substrate: building isolated environments | 9 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); every unit runs laboratory-integrated, and the A-3 practicals component carries the environment build time. The laboratory platform is selected at teaching-plan stage; delivery is platform-agnostic at concept level, with the command-line norm assumed from the Year 1 substrate.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across virtualisation concepts, networking, storage and containerisation.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Timed virtualisation tasks at the workstation: machines deployed, virtual networks configured, containers run, with a maintained evidence log | Individual; in-class; graded | LO1, LO3 | 30 |
| CW-I-Home | Isolated environment build case: a laboratory environment designed and built to a brief (machines, networks, containment), with written justification of the machine-versus-container choices made; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO1, LO4 | 35 |
| EX | Written examination: virtualisation concepts and hypervisor types, virtual networking and storage, container fundamentals, the laboratory substrate; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO2, LO3 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Portnoy, M., Virtualization Essentials (Sybex) - primary conceptual text (U1, U2, U4).
- Kane, S. P. and Matthias, K., Docker: Up and Running (O'Reilly) - the container introduction (U5); selected chapters only.
- Proxmox VE documentation (Proxmox Server Solutions) - named online resource, kit-dependent; confirmed against the selected laboratory platform at teaching-plan stage.
- School-produced laboratory-environment guides (kit-specific), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a virtualisation and infrastructure domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 4 |
