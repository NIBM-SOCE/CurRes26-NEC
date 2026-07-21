# Module Descriptor - Cloud Technologies

**Code:** NB-SOCE-L4-NEC-TT-05  ·  **Tier:** Pathway (NEC)  ·  **Type:** Pathway / Taught  ·  **Status:** Draft for Review v1.0  ·  **Date:** 20 Jul 2026
**Sources:** NEC record set v1.1; 00_Master_Decisions.md v2.5; 01_Shared_Spine.md v2.2; 04_Conventions.md v1.2; 05_Hours_Model.md v1.2; 07_SLQF_Reference.md v1.1; 08_Descriptor_Style.md v1.1; v8.1 Phase 2 Register v1.0; NEC Applied Cybersecurity decision records L3-L4 and L5-L6 (fixed degree-side inputs)

> **Items requiring confirmation at review:** (1) the learning-outcome set, including the added analytical LO4 (ratified into the NEC record set); (2) assessment attributes and weightings at specification sign-off; (3) syllabus hour allocations; (4) indicative reading; (5) staffing names; (6) the identity-touchpoint platform coverage (AWS IAM primary, Microsoft Entra ID at awareness level, per thread platform ruling T2) confirmed at specification against Level 6 Cloud Security's identity assumptions; (7) laboratory account and cost arrangements for the AWS environment confirmed at teaching-plan stage.

## 1. Module Identity and Architecture

| Field | Value |
|---|---|
| Module code | NB-SOCE-L4-NEC-TT-05 |
| Module title | Cloud Technologies |
| Scope / type | Pathway: NEC  ·  Pathway / Taught |
| SLQF level / credits | Level 4 (Year 2)  ·  3 credits  ·  150 notional hours (1 credit = 50 hours) |
| Feeder targets (named) | Level 6 Cloud Security (the primary cloud-continuity chain, bridged through the M2 cloud-networking seed in Level 5 Advanced Network Engineering); cloud identity and access management (Entra ID, IAM roles) into the identity vertical and Level 6 Cloud Security's identity assumptions |
| Prerequisites | Virtualisation Technologies; Networking Fundamentals |
| Delivery mode | Session-based: 3-hour blocks (V10); 16 lecture sessions plus tutorials, practicals and demonstration per the hours profile |
| Hours profile | Taught 3-credit (A-3), 05_Hours_Model.md v1.2 |

## 2. Module Purpose and Aims

To give the pathway the solid cloud foundation its degree-side continuity requires: what the cloud service and deployment models actually mean, how core infrastructure services behave, how cloud networks are put together, and how identity and access are governed in a cloud platform - taught by provisioning and operating real infrastructure, not by describing it. The module's posture follows the pathway's cloud boundary, quoted not re-drawn: this pathway provisions and operates, the software-engineering pathway builds - no application development enters here. Equally deliberately, this is the solid-foundation feeder and not the security module: cloud security at depth is Level 6's, and this module's job is to make that module's opening assumptions safe.

### Specification Boundary (from the NEC record set v1.1 - QUOTED, never edited)

> **Covers:** cloud service and deployment models; core cloud infrastructure services; a cloud identity and access-management touchpoint (identity vertical); cloud networking basics.
>
> **Does NOT cover:** cloud security at depth (Level 6 Cloud Security - this module is the solid-foundation feeder, not the security module); virtualisation internals (Virtualisation Technologies).
>
> *Boundary changes are change requests against Master Decisions, not descriptor edits.*

## 3. Learning Outcomes

| Ref | Intended Learning Outcome | Register |
|---|---|---|
| LO1 | Explain cloud service and deployment models. | Understand |
| LO2 | Deploy basic cloud infrastructure and services. | Apply |
| LO3 | Configure cloud identity and access controls. | Apply |
| LO4 | Evaluate cloud service and deployment options for a given workload and justify the selection. | Evaluate (SLQF-04 analytical outcome) |

*LO1 to LO3 authored from the record stubs (NEC v1.1) unchanged; LO4 added to satisfy the Level 4 analytical requirement (SLQF-04 cluster rule, V12) and presented for ratification into the NEC record set. Verb audit run at Level 4: the practical verbs (deploy, configure) sit within the Level 4 application register; no K-SAM category 7 defence is required.*

### Integrative Points and Seams

| Counterpart | Seam |
|---|---|
| Virtualisation Technologies | The progression seam in: virtualisation underpins cloud; internals are theirs, platform models and services are here. |
| Networking Fundamentals | Addressing and protocol foundations assumed; cloud networking (U4) builds virtual networks with them. |
| SE pathway (cloud boundary, standing obligation 3 - quoted, never re-drawn) | "This pathway provisions and operates, SE builds": cloud application development belongs to the software-engineering pathway; nothing built here is an application. |
| Windows Server and Directory Services / Information Security Fundamentals | The identity vertical: the concept seat (Year 1) and the directory implementation seat (Year 2) are extended here by the cloud identity touchpoint (U5) - IAM roles and policies as cloud-managed identity. |
| Level 5 Advanced Network Engineering | The M2 cloud-networking seed: the bridge through which the cloud-continuity chain runs; U4 supplies its assumed basics. |
| Level 6 Cloud Security | The primary chain: this module is the named solid foundation; its identity assumptions (Entra ID, IAM roles) are addressed per the platform note and review item 6. |

## 4. Curriculum and Delivery

### Indicative Syllabus

| Unit | Content | Lecture hours |
|---|---|---|
| U1 | Cloud service and deployment models | 9 |
| U2 | Core infrastructure services I: compute and storage | 9 |
| U3 | Core infrastructure services II: databases and supporting services at concept level | 6 |
| U4 | Cloud networking basics: virtual networks, subnets, security groups | 9 |
| U5 | Cloud identity and access management: IAM roles and policies; directory-cloud identity awareness | 9 |
| U6 | Operating in the cloud: provisioning workflows, monitoring basics and cost awareness | 6 |
| | Total lecture hours | 48 |

48 lecture hours are delivered as 16 three-hour sessions (V10); U2 through U6 run console-and-CLI-integrated, and the A-3 practicals component carries the provisioning laboratory time.

**Platform note (thread ruling T2, 20 Jul 2026):** concepts are provider-neutral; AWS is the default working platform for laboratory and assessment. The posture mirrors the pathway's networking modules: no vendor-certification alignment claim is made or implied, and AWS documentation and academy materials are delivery resources only, never the specification. The identity touchpoint (U5) runs on AWS IAM as primary, with directory-cloud identity (Microsoft Entra ID) carried at awareness level so that the named degree-side identity assumptions are satisfied rather than silently narrowed (review item 6). Honest cost: single-provider laboratory depth is bought at the price of multi-cloud breadth; U1 keeps the model-level treatment provider-neutral so the Level 6 chain is not platform-locked.

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

Components per the Assessment Component Taxonomy (04_Conventions.md v1.2); weightings confirmed at specification sign-off. The examination is carried for breadth across models, services, networking and identity.

| Component code | Task | Attributes | ILOs | Weight |
|---|---|---|---|---|
| PR-I-Class | Timed cloud provisioning tasks: infrastructure and identity controls configured at the console and CLI against task sheets, with a maintained evidence log | Individual; in-class; graded | LO2, LO3 | 30 |
| CW-I-Home | Cloud deployment case: basic infrastructure deployed to a brief on the default platform, delivered with a service-and-deployment selection report justifying the choices for the given workload; oral vehicle: Viva-defence | Individual; take-home; graded; oral vehicle: Viva-defence | LO2, LO4 | 35 |
| EX | Written examination: service and deployment models, core infrastructure services, cloud networking, identity and access management; 2 hours, closed resources, invigilated | Individual; in-class; graded | LO1, LO3, LO4 | 35 |

Weights sum to 100. Reassessment: by the failed component only, with an equivalent task, per School regulations. All assessment under the academic integrity policy including its generative-AI provisions; module-level AI stance at teaching-plan stage.

## 6. Resources, Staff and Governance

### Indicative Reading

- Wittig, A. and Wittig, M., Amazon Web Services in Action (Manning) - primary platform text for the working environment; used as a resource, not a specification.
- Ruparelia, N. B., Cloud Computing (MIT Press) - the provider-neutral concepts strand (U1).
- AWS product documentation (Amazon Web Services) - named online resource, version-current; connectivity-dependent.
- Microsoft Entra ID documentation (Microsoft) - named online resource for the directory-cloud identity awareness strand (U5); connectivity-dependent.
- School-produced provisioning laboratory guides and cost-control notes (account-dependent), confirmed at teaching-plan stage.

### Staffing (D7)

| Role | Name | Domain credential |
|---|---|---|
| Module leader 1 |  |  |
| Module leader 2 |  |  |
| External module auditor |  |  |

**Domain-expertise statement:** Taught from a cloud-technologies domain; generic delivery is non-compliant (D7).

### Version and Sign-off

| Version | Date | Amendment | Authority |
|---|---|---|---|
| 1.0 | 20 Jul 2026 | Initial descriptor | NEC descriptor thread, Batch 4 |
