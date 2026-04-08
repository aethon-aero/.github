<div align="center">

<img alt="Aethon Aerospace" src="https://raw.githubusercontent.com/aethon-aero/.github/main/assets/logo-light.png" width="420">

<br><br>

**Software-Defined Aviation for the Next Century**

<br>

![Aethon](https://img.shields.io/badge/Aethon-Aerospace-0A2240?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active_Development-2EA44F?style=for-the-badge)
![Classification](https://img.shields.io/badge/Classification-Internal_Use_Only-DC3545?style=for-the-badge&logo=lock&logoColor=white)
![License](https://img.shields.io/badge/License-Proprietary-37474F?style=for-the-badge)

<br>

**28 Repositories** · **14 Engineering Teams** · **3 Aircraft Programs** · **5 Aethon-OS Modules**

---

</div>

## Organization Architecture

<img src="https://raw.githubusercontent.com/aethon-aero/.github/main/assets/org-architecture.svg" alt="Organization Architecture" width="100%">

---

## Aircraft Programs

<table>
<tr>
<td align="center" width="33%">

### Aethon-C
**Blended Wing Body Cargo**

![MTOW](https://img.shields.io/badge/MTOW-220t-607D8B?style=flat-square)
![Range](https://img.shields.io/badge/Range-5,200nm-607D8B?style=flat-square)
![Phase](https://img.shields.io/badge/Phase-Preliminary_Design-FF6F00?style=flat-square)

FAR/CS-25 + Special Conditions
FAA (primary) · EASA (validation)

</td>
<td align="center" width="33%">

### Aethon-P
**Passenger Aircraft**

![Phase](https://img.shields.io/badge/Phase-Concept_Design-9E9E9E?style=flat-square)
![Status](https://img.shields.io/badge/Status-Feasibility_Study-78909C?style=flat-square)

FAR/CS-25
Market analysis active

</td>
<td align="center" width="33%">

### Aethon-X
**Experimental Demonstrators**

![TRL](https://img.shields.io/badge/TRL-3--5-FF6F00?style=flat-square)
![Type](https://img.shields.io/badge/Type-Tech_Demonstrator-333333?style=flat-square)

Subscale flight test vehicles
Technology pipeline for C and P

</td>
</tr>
</table>

---

## Aethon-OS Platform

The **Aethon-OS** is our software-defined aviation backbone — an event-driven microservices platform that provides the digital thread connecting design, manufacturing, certification, and fleet operations across all programs.

| Module | Purpose | Tech Stack |
|--------|---------|-----------|
| [`aethon-os-core`](https://github.com/aethon-aero/aethon-os-core) | API gateway, digital thread, event bus | Python, TypeScript, FastAPI, GraphQL |
| [`aethon-os-data-platform`](https://github.com/aethon-aero/aethon-os-data-platform) | Data ingestion, ETL, analytics serving | Python, Parquet, Arrow, PostgreSQL |
| [`aethon-os-certification-spine`](https://github.com/aethon-aero/aethon-os-certification-spine) | Evidence packaging, compliance tracking | Python, DO-178C, ARP4754A |
| [`aethon-os-fleet-intelligence`](https://github.com/aethon-aero/aethon-os-fleet-intelligence) | Predictive maintenance, health monitoring | Python, ML, Time-Series |
| [`aethon-os-digital-manufacturing`](https://github.com/aethon-aero/aethon-os-digital-manufacturing) | QA vision, SPC, production analytics | Python, OpenCV, AS9100D |

---

## Engineering Tooling

| Repository | Domain | Capabilities |
|-----------|--------|-------------|
| [`aethon-cfd-automation`](https://github.com/aethon-aero/aethon-cfd-automation) | Aerodynamics | OpenFOAM, SU2, HPC orchestration, mesh automation |
| [`aethon-fea-automation`](https://github.com/aethon-aero/aethon-fea-automation) | Structures | Nastran, Abaqus, composites, fatigue and DT |
| [`aethon-mbse-tooling`](https://github.com/aethon-aero/aethon-mbse-tooling) | Systems | SysML 2.0, Capella, ICD generation, N2 diagrams |
| [`aethon-flight-sciences-tools`](https://github.com/aethon-aero/aethon-flight-sciences-tools) | Flight Sciences | Aero DB, S&C, loads, OpenVSP, PANAIR |
| [`aethon-performance-trades`](https://github.com/aethon-aero/aethon-performance-trades) | Performance | Sizing, MDO, payload-range, trade studies |
| [`aethon-requirements-traceability`](https://github.com/aethon-aero/aethon-requirements-traceability) | Requirements | DOORS, V&V, compliance matrix, bidirectional trace |

---

## Quality and Certification

| Repository | Purpose | Standards |
|-----------|---------|-----------|
| [`aethon-quality-systems`](https://github.com/aethon-aero/aethon-quality-systems) | QMS tooling (NCR, CAPA, FAI, SPC) | AS9100D, ISO 9001 |
| [`aethon-certification-evidence-tools`](https://github.com/aethon-aero/aethon-certification-evidence-tools) | Evidence packaging and audit prep | DO-178C, DO-254, ARP4754A |
| [`aethon-test-rig-software`](https://github.com/aethon-aero/aethon-test-rig-software) | Iron bird, HIL, integration bench | DO-160G, DO-178C |
| [`aethon-supplier-interface-tools`](https://github.com/aethon-aero/aethon-supplier-interface-tools) | Supplier data exchange and validation | AS9100D, ITAR |

---

## Governance

| Repository | Purpose |
|-----------|---------|
| [`org-policies`](https://github.com/aethon-aero/org-policies) | Org setup scripts, permission matrix, labels, CODEOWNERS |
| [`repo-templates`](https://github.com/aethon-aero/repo-templates) | README, PR, issue templates for all repos |
| [`engineering-handbook`](https://github.com/aethon-aero/engineering-handbook) | Branching strategy, code review, naming conventions |
| [`aethon-docs`](https://github.com/aethon-aero/aethon-docs) | Architecture docs, procedures, onboarding guides |
| [`aethon-devsecops-platform`](https://github.com/aethon-aero/aethon-devsecops-platform) | CI/CD, SAST/DAST, SBOM, secret scanning |

---

## Repository Standards

Every repository in this organization includes:

<table>
<tr>
<td width="50%">

**Governance and Documentation**
- Production-grade README with Mermaid architecture diagrams
- CONTRIBUTING.md with branch strategy and PR process
- CHANGELOG.md (Keep a Changelog format)
- CODE_OF_CONDUCT.md
- SECURITY.md with vulnerability reporting procedures
- LICENSE (Proprietary with export control clauses)
- CODEOWNERS (team-specific review routing)

</td>
<td width="50%">

**Engineering Infrastructure**
- GitHub Actions CI pipeline (lint, test, security, build)
- Dependabot for automated dependency updates
- Makefile with standard development commands
- .editorconfig for consistent formatting
- pyproject.toml (ruff + mypy + pytest)
- .env.example with documented variables
- Domain-specific directory scaffolds

</td>
</tr>
<tr>
<td>

**Issue Templates**
- Bug report
- Feature request
- Architecture decision (ADR)
- Certification finding
- Nonconformance report (NCR)
- Security concern

</td>
<td>

**Platform Repos Additionally**
- Multi-stage Dockerfile (non-root, healthcheck)
- docker-compose.yml (Postgres + Redis)
- .dockerignore (security-hardened)
- Full CI with container build and push

</td>
</tr>
</table>

---

## Classification System

| Class | Visibility | Access | Repos |
|-------|-----------|--------|-------|
| **Class B** | Internal Private | Engineering teams | 21 repos |
| **Class C** | Restricted Private | Cert + DevSecOps only | 2 repos (cert-spine, devsecops) |
| **Class D** | Controlled External | Supplier interface | 1 repo (supplier-interface-tools) |

---

## Applicable Standards

| Standard | Scope |
|----------|-------|
| **FAR Part 25 / CS-25** | Airworthiness — transport category aircraft |
| **DO-178C** | Software considerations in airborne systems |
| **DO-254** | Design assurance for airborne electronic hardware |
| **ARP4754A** | Development of civil aircraft and systems |
| **ARP4761** | Safety assessment process for civil aircraft |
| **DO-160G** | Environmental conditions and test procedures |
| **AS9100D** | Quality management system — aerospace |
| **DO-326A** | Airborne system information security |
| **NIST SP 800-171** | CUI protection (CMMC L2) |

---

## Engineering Teams

| Team | Domain | Key Repos |
|------|--------|-----------|
| `platform-engineering` | Governance, DevOps, infrastructure | org-policies, devsecops, supplier-interface |
| `air-vehicle-engineering` | Program architecture, systems integration | aethon-c/p/x-program, aethon-docs |
| `aethon-os` | Digital thread platform | all aethon-os-* repos |
| `flight-sciences` | Aerodynamics, performance, CFD | cfd-automation, flight-sciences, perf-trades |
| `structures-composites` | Structural analysis, materials | fea-automation |
| `systems-safety` | MBSE, requirements, safety | mbse-tooling, requirements-traceability |
| `certification-airworthiness` | Type certificate, evidence | cert-spine, cert-evidence-tools |
| `manufacturing-quality` | Production, QMS, test rigs | quality-systems, test-rig-software |
| `devsecops` | Security, CI/CD, compliance | devsecops-platform |

---

## Quick Start

```bash
# Prerequisites: GitHub CLI authenticated with org access
gh auth status

# Clone any repo
gh repo clone aethon-aero/<repo-name>
cd <repo-name>

# Set up development environment
make dev

# Run the full CI pipeline locally
make ci

# For platform services — start the local stack
docker compose up -d
```

---

<div align="center">

<img alt="Aethon" src="https://raw.githubusercontent.com/aethon-aero/.github/main/assets/logo-light.png" width="120">

**Aethon Aerospace** — Building the future of aviation

[`org-policies`](https://github.com/aethon-aero/org-policies) ·
[`engineering-handbook`](https://github.com/aethon-aero/engineering-handbook) ·
[`aethon-docs`](https://github.com/aethon-aero/aethon-docs)

*Proprietary and Confidential — All Rights Reserved*

</div>
