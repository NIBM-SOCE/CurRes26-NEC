# CurRes26 - Pathway: Network Engineering and Cybersecurity

Governance repository for the Years 1 and 2 module descriptors of the Network Engineering and Cybersecurity pathway, produced under NIBM's School of Computing and Engineering (SOCE) curriculum restructuring initiative, CurRes26.

This repository holds the governance-ready module descriptors for the Network Engineering and Cybersecurity (NEC) pathway. NEC is one of four pathways in the restructured BSc programme; the others (Computer Science with Software Engineering, Computer Science with Artificial Intelligence and Data Science, and Information Technology for Business) are governed and versioned separately.

---

## 1. Programme Context

The programme is delivered in two stages:

- **Years 1 and 2** are governed by NIBM under the Sri Lanka Qualifications Framework (SLQF). This is the scope of this repository.
- **Years 3 and 4** are delivered in partnership with Coventry University under the UK Framework for Higher Education Qualifications (FHEQ), leading to a BSc (Hons) award. Years 3 and 4 are outside this repository; they are referenced here only for continuity.

Years 1 and 2 form the Higher National Diploma stage of the BSc (Hons) Applied Cybersecurity programme, which at Level 6 opens into two tracks (Ethical Hacking; Network Engineering). The pathway is built so that both tracks find the networking, systems, security and programming foundations they assume, without either field crowding out the other.

## 2. Qualification Structure

| Programme stage | SLQF award | FHEQ equivalent | NVQ target | Award title |
|---|---|---|---|---|
| Year 1 (exit) | Diploma level | Level 4 | NVQ Level 5 (target) | Diploma in Network Engineering and Cybersecurity |
| Year 2 (exit) | Higher Diploma level | Level 5 | NVQ Level 6 (target) | Higher National Diploma in Network Engineering and Cybersecurity |
| Years 3-4 (Coventry) | Bachelors Honours level | Levels 5-6 | n/a | BSc (Hons) Applied Cybersecurity |

"Higher National Diploma" is the award-certificate term; SLQF itself uses "Higher Diploma" for the same level. Both are used, with the SLQF level stated alongside.

**TVEC accreditation:** TVEC accreditation is being actively pursued and has not yet been granted. The NVQ-level targets above, and any other TVEC/NVQ-facing mappings referenced from this programme, are targets that may be adjusted once TVEC confirms its specific requirements. SLQF conventions are binding now, independently of that outcome. Any exit-award or accreditation language should carry this caveat until TVEC's requirements are final.

## 3. Credit and Hours Convention

- **1 credit = 50 notional learning hours.** Industrial Training is the one exception, at 1 credit = 100 hours.
- **Delivery follows the institute's 3-hour session pattern.** Lecture hours are fixed by credit weight: 48 hours (16 sessions) for a 3-credit taught module, 66 hours (22 sessions) for a 4-credit module, and 30 hours (10 sessions) for a 2-credit module. All other timetabled components (tutorials, practicals, laboratory work, in-class assignments, demonstrations) are set in multiples of three hours.
- **Self-guided study always carries the largest share** of a taught module's notional hours; this holds across every credit weight.
- CREST, the Year 2 entrepreneurship component, is delivered on the skills-module hours pattern but does not count toward award credit totals; it is a mandatory pass/fail component, not a credit-bearing one.

## 4. Programme Architecture - NEC

### Year 1 - Diploma Stage

<sub>37 credits · 1,850 notional hours</sub>

| Module group | Modules | Credits |
|---|---|---|
| Institution-wide common | Fundamentals of Computing, Mathematical Thinking, Algorithmic Thinking, Digital Electronics and Logic Design | 14 |
| Pathway (NEC) | Operating Systems and Infrastructure, Networking Fundamentals, Applied Programming for Networks and Security, Web and Internet Technologies, Information Security Fundamentals | 18 |
| Integrative Skills | Effective Communication Skills I, Creative Project | 5 |
| Exit Block (Diploma exit only) | Industry Horizons, Professional Practice Foundations | 4 |

The exit block applies only to students exiting the programme at Diploma level. Including it, the Diploma exit stands at **13 modules, 41 credits**.

NEC's Year 1 pathway envelope is larger than most pathways carry, because NEC builds its foundations in-field from the start: instead of the general cluster-common modules, the pathway teaches its own networks-and-security-focused foundations, including a Python-first applied programming module aimed squarely at networks and security work.

### Year 2 - Higher Diploma Stage

<sub>39 credits · 2,200 notional hours</sub>

| Module group | Modules | Credits |
|---|---|---|
| Pathway (NEC) | Enterprise Network Engineering, Linux Server Administration, Windows Server and Directory Services, Virtualisation Technologies, Cloud Technologies, Network and Security Operations, Ethical Hacking and Application Security, Scripting and Automation, Data Management and Security, Capstone Project, Industrial Training | 37 |
| Integrative Skills | Entrepreneurship, Creativity and Innovation (CREST, non-credit), Effective Communication Skills II | 2 |
| Exit Block (HND exit only) | Professional Standing and Career Strategy, Ethics and Responsibility in Computing Practice | 4 |

<sub>Industrial Training is credited at 100 notional hours per credit rather than the standard 50, which is why 2,200 notional hours runs above the simple 39 × 50.</sub>

The exit block applies only to students exiting the programme at Higher National Diploma level. Including it, the HND exit stands at **15 modules, 43 credits**.

### Why Year 2 Is Shaped This Way

Year 2's taught set was built to a clear brief, worth explaining rather than just listing:

- **Security is taught from both sides.** Network and Security Operations builds the defensive skill set (hardening, monitoring, security operations), and Ethical Hacking and Application Security builds the offensive skill set that professional security testing depends on: finding weaknesses the way an attacker would, then validating and reporting them so systems can be hardened. Teaching both gives students the complete, employable picture, with the offensive module carrying a defensive-validation counterweight so the skill is exercised constructively.
- **Enterprise Network Engineering delivers a focused routing and switching core.** It consolidates the enterprise networking essentials into one coherent module, and the network-services and wireless material is taught where it naturally belongs: services concepts in Networking Fundamentals, Linux-side implementation in Linux Server Administration, and Windows-integrated DNS in Windows Server and Directory Services. Students get a clean, well-sequenced networking spine rather than one sprawling module.
- **Server administration is taught as two modules, Linux Server Administration and Windows Server and Directory Services.** Students gain both major server ecosystems at real depth rather than a shallow pass over each. This also lets the Linux module go deep, and lets the Windows module close the identity and directory vertical in-year: authentication, authorisation and Active Directory, which the later security modules build directly on.
- **Nine taught modules, uniformly at 3 credits.** The even banding gives each area of the pathway comparable weight and teaching time, so students leave with balanced strength across networking, systems, security, scripting and data rather than a transcript skewed to one strand.
- **The discipline spread reflects the award's two fields.** Across the taught set, systems and infrastructure carry the largest share (Active Directory, servers, virtualisation, cloud), with security, networking, programming and data each holding a clear place. The mix delivers a genuine networking and infrastructure spine while seeding the security, scripting and data foundations that both Level 6 tracks assume.

### Years 3 and 4

Progression continues at Coventry University under FHEQ Levels 5 and 6, leading to a BSc (Hons) in Applied Cybersecurity, at 240 credits across the full four-year programme. Level 5 is a shared year taken by the whole cohort; at Level 6 the programme opens into two named tracks, allowing students to specialise:

- **Ethical Hacking track** - offensive security, applied ethical hacking and AI for cybersecurity.
- **Network Engineering track** - advanced network architecture, automation and infrastructure security.

Years 3 and 4 module descriptors are Coventry's and are not held in this repository.

## 5. Module Descriptors

Each row links to the governance descriptor: the polished, review-ready module descriptor document. These are the authoritative version of each module's identity, learning outcomes, curriculum, assessment and staffing arrangement.

Pathway (NEC) modules are held in this repository. The institution-wide common modules (the four Tier 1 commons, the Integrative Skills modules and the exit-block modules) are shared across all four pathways and maintained centrally; their descriptors are published on the [central common-modules page](https://nibm-soce.github.io/CurRes26-CS-SE/), where the current version of each is always available.

### Year 1 - Diploma Stage

<sub>37 credits · 1,850 notional hours</sub>

| Code | Module | Type | Credits | Descriptor |
|---|---|---|---|---|
| NB-SOCE-L3-CM-TT-01 | Fundamentals of Computing | Institution-wide common | 4 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-TT-02 | Mathematical Thinking | Institution-wide common | 4 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-TT-03 | Algorithmic Thinking | Institution-wide common | 3 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-TT-04 | Digital Electronics and Logic Design | Institution-wide common | 3 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-NEC-TT-01 | Operating Systems and Infrastructure | Pathway (NEC) | 3 | [Descriptor](modules/L3-Year1-Diploma/NB-SOCE-L3-NEC-TT-01_OperatingSystemsAndInfrastructure_Gov_v1.0.docx) |
| NB-SOCE-L3-NEC-TT-02 | Networking Fundamentals | Pathway (NEC) | 4 | [Descriptor](modules/L3-Year1-Diploma/NB-SOCE-L3-NEC-TT-02_NetworkingFundamentals_Gov_v1.0.docx) |
| NB-SOCE-L3-NEC-TT-03 | Applied Programming for Networks and Security | Pathway (NEC) | 4 | [Descriptor](modules/L3-Year1-Diploma/NB-SOCE-L3-NEC-TT-03_AppliedProgrammingForNetworksAndSecurity_Gov_v1.0.docx) |
| NB-SOCE-L3-NEC-TT-04 | Web and Internet Technologies | Pathway (NEC) | 3 | [Descriptor](modules/L3-Year1-Diploma/NB-SOCE-L3-NEC-TT-04_WebAndInternetTechnologies_Gov_v1.0.docx) |
| NB-SOCE-L3-NEC-TT-05 | Information Security Fundamentals | Pathway (NEC) | 4 | [Descriptor](modules/L3-Year1-Diploma/NB-SOCE-L3-NEC-TT-05_InformationSecurityFundamentals_Gov_v1.0.docx) |
| NB-SOCE-L3-CM-IS-01 | Effective Communication Skills I | Integrative Skills | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-IS-02 | Creative Project | Integrative Skills | 3 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-IS-03 | Industry Horizons | Exit Block (Diploma) | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L3-CM-IS-04 | Professional Practice Foundations | Exit Block (Diploma) | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |

### Year 2 - Higher Diploma Stage

<sub>39 credits · 2,200 notional hours</sub>

| Code | Module | Type | Credits | Descriptor |
|---|---|---|---|---|
| NB-SOCE-L4-NEC-TT-01 | Enterprise Network Engineering | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-01_EnterpriseNetworkEngineering_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-02 | Linux Server Administration | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-02_LinuxServerAdministration_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-03 | Windows Server and Directory Services | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-03_WindowsServerAndDirectoryServices_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-04 | Virtualisation Technologies | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-04_VirtualisationTechnologies_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-05 | Cloud Technologies | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-05_CloudTechnologies_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-06 | Network and Security Operations | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-06_NetworkAndSecurityOperations_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-07 | Ethical Hacking and Application Security | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-07_EthicalHackingAndApplicationSecurity_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-08 | Scripting and Automation | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-08_ScriptingAndAutomation_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-TT-09 | Data Management and Security | Pathway (NEC) | 3 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-TT-09_DataManagementAndSecurity_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-SK-01 | Capstone Project | Pathway (NEC) | 5 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-SK-01_CapstoneProject_Gov_v1.0.docx) |
| NB-SOCE-L4-NEC-SK-02 | Industrial Training | Pathway (NEC) | 5 | [Descriptor](modules/L4-Year2-HigherDiploma/NB-SOCE-L4-NEC-SK-02_IndustrialTraining_Gov_v1.0.docx) |
| NB-SOCE-L4-CM-IS-01 | Entrepreneurship, Creativity and Innovation (CREST) | Integrative Skills - non-credit, pass/fail | 0 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L4-CM-IS-02 | Effective Communication Skills II | Integrative Skills | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L4-CM-IS-03 | Professional Standing and Career Strategy | Exit Block (HND) | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |
| NB-SOCE-L4-CM-IS-04 | Ethics and Responsibility in Computing Practice | Exit Block (HND) | 2 | [Common module](https://nibm-soce.github.io/CurRes26-CS-SE/) |

## 6. Feeder and Consumer Map

[Open the NEC Feeder and Consumer Map](map/NIBM_SOCE_NEC_FeederConsumerMap_v8_1.html)

An interactive view of how Year 1 and Year 2 modules feed into each other and into the Years 3-4 Coventry modules, and which modules each one draws on in turn. Download the file and open it in a browser to explore it.

## 7. Repository Structure

```
CurRes26-NEC/
├── README.md
├── modules/
│   ├── L3-Year1-Diploma/          Governance descriptors, Year 1 pathway modules
│   ├── L4-Year2-HigherDiploma/    Governance descriptors, Year 2 pathway modules
│   └── sources/                   Working source files behind the descriptors above
└── map/
    └── NIBM_SOCE_NEC_FeederConsumerMap_v8_1.html   Interactive feeder/consumer map for NEC
```

This repository holds the NEC pathway descriptors only. The `modules/sources` directory holds the working markdown behind each pathway descriptor and is not linked module-by-module above; it carries more internal drafting detail than the governance descriptors and is intended for the curriculum team rather than external readers.

## 8. Status and Conventions

Descriptors in this repository are issued as governance-ready drafts for review. Where a descriptor still has an open item (for example, a learning-outcome set or an assessment weighting awaiting confirmation), that is stated explicitly within the descriptor itself. Documents follow UK English, Title Case module titles, and a table-first presentation throughout.
