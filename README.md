# National Skill Development Data Standard (NSDDS)

## Project Overview

This repository hosts the **Common Data Standard for Skill Training Outcomes**—an open, version-controlled schema designed to unify reporting across India's diverse skill development ecosystem. Under the aegis of the National Skill Development Mission (NSDM), this standard aims to break down data silos between Industrial Training Institutes (ITIs), PMKVY training centers, private apprenticeship partners, and other stakeholders.

By providing a consistent format for capturing key training and placement outcomes, the standard enables:

*   **Seamless data aggregation** for national‑level analysis.
*   **Evidence‑based policy‑making** by linking training inputs with labor‑market results.
*   **Transparent monitoring** of scheme performance (PMKVY, apprenticeship programs, etc.).
*   **Interoperability** with future labor‑market information systems and job portals.

## Why This Standard Matters

Currently, training providers report outcomes in disparate formats, making it difficult to compare, benchmark, or derive actionable insights. A unified schema addresses these challenges by:

1.  **Ensuring Consistency** – Every training record follows the same structure, regardless of the provider.
2.  **Facilitating Automation** – Machine‑readable JSON Schema allows for automated validation and ingestion.
3.  **Enabling Longitudinal Tracking** – Standardized identifiers (trainee, partner, course) support tracking of individuals over time and across programs.
4.  **Promoting Open Governance** – The schema is developed and evolved through public consultation on this platform, embodying the principles of open government and collaborative policy‑making.

## Repository Structure

*   `schema‑v1.json` – The core JSON Schema definition of the data standard.
*   `README.md` – This file, explaining the project and how to contribute.
*   `docs/` – (Future) Detailed documentation, use‑case examples, and implementation guides.
*   `examples/` – (Future) Sample data files that validate against the schema.

## How to Contribute

We invite all stakeholders—training partners, industry associations, researchers, government agencies, and concerned citizens—to help shape the standard. Contributions can take several forms:

### 1. **Provide Feedback via Issues**
   *   Browse the [Issues](https://github.com/lawirit/skill-outcomes-data-standard/issues) tab to see ongoing discussions.
   *   Open a new issue to propose a new field, suggest changes to existing definitions, or raise questions about the schema.

### 2. **Propose Changes via Pull Requests**
   *   Fork this repository to your own GitHub account.
   *   Create a new branch (e.g., `feature/add‑new‑field`).
   *   Edit the schema or documentation files in your branch.
   *   Submit a pull request (PR) that clearly describes the change and references any related issues.

### 3. **Participate in Reviews**
   *   Review open pull requests and leave inline comments on specific lines of code.
   *   Help ensure that changes are well‑reasoned, backward‑compatible, and aligned with the standard’s objectives.

### 4. **Spread the Word**
   *   Share this repository with other stakeholders who should be involved.
   *   Use the standard in pilot implementations and report back on your experience.

## Development Workflow

1.  **Draft Phase** – The core team publishes an initial draft of the schema (`schema‑v1.json`).
2.  **Public Consultation** – GitHub Issues are used to collect structured feedback on specific aspects of the schema.
3.  **Iteration** – Based on feedback, changes are made via feature branches and merged through pull requests.
4.  **Release** – Once a version is stable, it is tagged as a GitHub Release (e.g., `v1.0`), creating a citable artifact for official adoption.

## Governance

This project is managed by the **Skill Development Data Standards Committee**, a cross‑functional group comprising representatives from the Ministry of Skill Development and Entrepreneurship (MSDE), NSDC, state skill missions, and industry bodies. The committee oversees the evolution of the standard, ensures alignment with national policy goals, and ultimately approves each official release.

## Contact

For official inquiries related to the standard, please contact the **Skill Development Data Standards Committee** via the Ministry of Skill Development and Entrepreneurship.

---

*This repository is a living document. Its content will evolve through public consultation and collaborative refinement. Thank you for helping build a more data‑driven skill ecosystem for India.*