# Relational State Safety

**Relational State Safety (RSS)** is a longitudinal safety framework for conversational and agentic AI.

It focuses on safety problems that emerge across an evolving human-system relationship rather than within a single model response. The central design question is:

> **Does the system keep the user's world larger than the interaction?**

RSS proposes privacy-bounded relational state, explicit models of dangerous transitions, pathway-specific intervention, preserved exits, and repair and re-entry after protective action.

## Read the work

### Two-page design brief

A concise overview of the framework, architecture, safety pathways, and evaluation approach.

[Download the RSS Design Brief v0.3.2](Relational-State-Safety-Design-Brief-v0.3.2.pdf)

### Full working specification

**Relational State Safety for Conversational and Agentic AI: A Working Specification for Longitudinal Detection, Pathway-Specific Intervention, and Re-entry**

* [SSRN](https://ssrn.com/abstract=7296738)
* [DOI: 10.2139/ssrn.7296738](https://doi.org/10.2139/ssrn.7296738)

## Core design principles

RSS is built around several distinctions:

* **Trajectory over isolated output.** A response can be locally acceptable while contributing to a dangerous longitudinal pattern.
* **Transitions over identities.** Attachment, intensity, high use, spirituality, roleplay, neurodivergent communication, and distress are not danger states by themselves.
* **Observation over diagnosis.** Safety state should preserve source, uncertainty, contradictory evidence, provenance, expiry, and user correction rather than assigning clinical labels.
* **Preserved exits.** Systems should protect access to outside reality, other people, alternative interpretations, time, bodily context, reversible action, and re-entry.
* **Pathway-specific intervention.** Epistemic frame loss and fatal narrowing require different protective responses.
* **Relational continuity matters.** A refusal or safety pivot is not necessarily a completed intervention. Repair and re-entry are part of the safety problem.
* **Authorization remains independent.** Relational confidence or conversational momentum must never substitute for explicit permission to take consequential external action.

## Current research direction

The next stage of the work focuses on **matched longitudinal trajectory evaluation**.

The basic method holds the current user message constant while varying the preceding interaction history. This makes it possible to test whether a system responds to meaningful longitudinal state rather than simply reacting to surface features in the latest message.

Evaluation should measure both:

* failure to respond when a trajectory has become dangerous
* unnecessary escalation, pathologizing, refusal, or relational rupture in matched benign controls

Future evaluation materials, trajectory cases, scoring rubrics, and implementation artifacts may be published in this repository.

## Status

RSS v0.3.2 is a **working engineering specification and conceptual safety framework**.

It is not a validated clinical instrument, diagnostic system, standard of care, or established industry standard. The proposed state model, pathway definitions, intervention logic, and evaluation methods require empirical testing, clinical and technical critique, and adversarial review.

## Citation

Calen, J. (2026). *Relational State Safety for Conversational and Agentic AI: A Working Specification for Longitudinal Detection, Pathway-Specific Intervention, and Re-entry*. Working Paper v0.3.2. SSRN 7296738. https://doi.org/10.2139/ssrn.7296738

## Author

**Jeb Calen**
Independent Researcher

* [ORCID](https://orcid.org/0009-0000-3916-0413)
* [SSRN author page](https://ssrn.com/author=12627988)
* [Holding Both Truths](https://holdingbothtruthsai.substack.com)
* Contact: [tetsu96@gmail.com](mailto:tetsu96@gmail.com)
