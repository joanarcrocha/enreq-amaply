# FAIR-AMAP: Requirements Specification

🇬🇧 English | [🇵🇹 Português](README.pt.md)

Practical Assignment no. 1 of the Requirements Engineering course (ENGREQ), Master's in Informatics Engineering, ISEP, 2026/2027.

**Submission deadline: 15 November 2026 (Moodle).**

## Context

FAIR Software Solutions is a startup developing software solutions that facilitate the distribution and sale of food products, within the scope of the UN 2030 Agenda for Sustainable Development (17 Sustainable Development Goals, https://ods.pt/ods/).

The company has identified a business opportunity in the AMAP/CSA field and is looking for a team to specify the functional and non-functional requirements of the solution, covering all of its processes.

- **AMAP**: Association for the Maintenance of Local Farming.
- **CSA**: Community Supported Agriculture.

An AMAP/CSA is formed by a group of consumers (co-producers) who actively and directly support one or more farmers and producers, ensuring the distribution of their produce.

## Goal

Produce a complete Software Requirements Specification (SRS) including:

- general description of the system;
- system functionalities;
- external interfaces;
- non-functional requirements;
- priorities;
- estimate, in hours, for the development of each functionality;
- description of the process: method, techniques applied and supporting evidence, context, and time allocated to each analyst and task.

The full assignment is in [docs/assignment](docs/assignment/engreq_tp1_2026_27_v2_EN.pdf).

## Repository structure

```
.
├── README.md / README.pt.md
├── docs/
│   ├── assignment/    Assignment statement
│   ├── elicitation/   Session notes and synthesis of gathered requirements
│   ├── process/       Planning, session log and task tracking
│   └── srs/           SRS document (draft and final versions)
└── artefacts/         Models, diagrams, prototypes and other supporting artefacts
```

| Folder | Content | Initial files |
|---|---|---|
| `docs/elicitation` | Everything coming from stakeholders and documentary research | [session-notes.en.md](docs/elicitation/session-notes.en.md), [open-questions.en.md](docs/elicitation/open-questions.en.md) |
| `docs/process` | Evidence of the method followed, required by the assignment | [planning.en.md](docs/process/planning.en.md), [session-log.en.md](docs/process/session-log.en.md) |
| `docs/srs` | Final specification | to be created |
| `artefacts` | Diagrams, process models, prototypes | to be created |

## Language policy

All repository content and documentation is kept in English and Portuguese. Each document exists in two files with the same name: `name.en.md` and `name.pt.md`. Any change to one must be mirrored in the other. The README is the exception: `README.md` is English and `README.pt.md` is Portuguese.

## Approach

The work follows the requirements elicitation methodology taught in the course, combining several techniques:

- sessions with real stakeholders (T classes) and simulated sessions with the lecturers (PL classes);
- documentary analysis and research into relevant sources;
- continuous recording of progress in this repository (planning, meetings, tasks, artefacts).

Guiding motto for elicitation: **People, Documents, Processes**.

## Stakeholders

The stakeholders of the system are:

- **Producers/farmers**
- **Co-producers** (the clients/consumers)

Other parties mentioned in the assignment that interact with the system or the project, but are not the main stakeholders: director of FAIR Software Solutions, distributors, volunteer coordination, system engineering/security/non-functional requirements, and the AMAP coordinator.

## Team

| Name | Student no. | Role |
|---|---|---|
| _to be filled_ | | |

## Conventions

- One entry per elicitation session in `docs/process/session-log`, with date, duration, participants and technique used.
- Short, descriptive commits that state the area (for example, `elicitation: notes from session 2`).
- Work status and owners tracked in `docs/process/planning`.
