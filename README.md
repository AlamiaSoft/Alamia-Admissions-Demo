# Alamia AdmissionsOS — Interactive Prototype Demo

> **Live public demonstration portal for Alamia AdmissionsOS prototypes, generated in Google Stitch and refined per institutional design partner feedback.**

---

## 1. Demo Applications

This repository hosts static interactive UI prototypes for the two core user experiences:

### 1. [Adviser Operations Console](apps/adviser-console/overview-dashboard/code.html)
A high-density desktop workspace (optimized for 1280px+) for admissions coordinators, case evaluators, and academic directors:
- **Overview Dashboard:** Operational triage queue, urgent blocker alerts, and corridor metrics.
- **Student Case Detail:** Candidate dossier for Ahmed Khan (`DEMO-STD-001`), with explicit evidence tracking.
- **Requirements & Evidence:** Credential adjudication ledger, source provenance, and conflict reconciliation.
- **Multi-Application Cases:** Decoupled candidate vault vs multi-institution application matrix.
- **Requirement Governance:** Institutional rule definitions vs candidate applicability & exception dockets.
- **Workflow & Dependencies:** Parallel milestone progression and non-linear case DAG.

### 2. [Student Companion PWA](apps/student-companion/home/code.html)
A mobile-first progressive web application (optimized for 390px mobile viewport) for international university applicants:
- **Home:** Action-oriented dashboard separating student tasks from internal adviser processing.
- **My Journey:** Configurable milestone progression without rigid, misleading timelines.
- **Document Centre:** Clear document lifecycle states (Uploaded, Attestation Required, Verified).
- **Messages:** Direct 1:1 communication between candidate and adviser with thread sanitization.
- **Offer & Status:** Conditional offer terms without false API sync or unconfirmed partner claims.

---

## 2. Interactive Navigation & Local Preview

Open [`index.html`](index.html) in any browser or launch a static server:

```bash
# Using Python
python -m http.server 8080

# Or using Node
npx serve .
```

- Portal Home: `http://localhost:8080/index.html`
- Adviser Console: `http://localhost:8080/apps/adviser-console/`
- Student Companion: `http://localhost:8080/apps/student-companion/`

---

## 3. Prototype Disclaimers & Governance

- **Evaluative Environment:** All applicant details (Ahmed Khan `DEMO-STD-001`) and institutional responses are synthetic illustrations for design and operational evaluation.
- **Independent Coordination:** Alamia AdmissionsOS is an independent admissions coordination workspace and does not claim official university partnership, endorsement, or direct institutional API registry integration.


## Guided walkthroughs

The public portal provides two clickable, step-by-step tours:

- **Adviser walkthrough:** worklist → candidate dossier → requirements & evidence → multiple applications → requirement governance → workflow dependencies.
- **Student walkthrough:** home → journey → documents → messages → application status.

Both follow the same fictional Ahmed Khan case. Use the **Guided demo** control on any screen to restart the current tour. This static prototype has no production backend; actions are illustrative only. See [Demo Scenario & Data Notes](docs/DEMO-SCENARIO.md) for canonical facts, personas and presentation rules.
