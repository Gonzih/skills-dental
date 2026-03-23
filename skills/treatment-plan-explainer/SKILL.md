---
name: treatment-plan-explainer
description: Explains a dental treatment plan in clear, patient-friendly language covering what's needed, why, sequence, cost overview, and what to expect.
triggers: ["explain treatment plan", "patient-friendly treatment", "help patient understand treatment"]
---

# Treatment Plan Explainer

## What this skill does
Takes a clinical dental treatment plan and rewrites it in plain language a patient can understand. It covers what procedures are recommended, why each is necessary, the recommended sequence, a general cost overview, and what the patient should expect before, during, and after treatment.

## How to invoke
/treatment-plan-explainer [paste or describe the treatment plan]

## Workflow steps

### Step 1 — Parse the treatment plan
Identify all procedures listed (CDT codes or plain descriptions), the tooth or area involved, and any urgency notes. Group related procedures (e.g., extractions, restorations, periodontal treatment).

### Step 2 — Translate to patient language
Rewrite each procedure in everyday English. Avoid jargon; when a clinical term is necessary, define it in parentheses. Explain *why* each procedure is recommended and what happens if it is deferred.

### Step 3 — Sequence and prioritize
Present procedures in the order they will be performed. Briefly explain why that order matters (e.g., "We address the infection first so your mouth is healthy before placing the crown").

### Step 4 — Cost and insurance overview
Provide a plain-language summary of estimated costs, insurance coverage concepts (if applicable), and any payment options to mention. Use ranges rather than exact figures unless specifics are provided.

### Step 5 — What to expect
For each major procedure, add a short "what to expect" note: preparation steps, what happens chairside, recovery time, and any post-op instructions to anticipate.

## Example outputs
A friendly, section-by-section breakdown titled "Your Personalized Treatment Plan" with headers for each procedure, a numbered sequence, a cost summary box, and a "Questions to ask your dentist" section at the end.

## Live Data Sources
- **ADA CDT Code Lookup** — ada.org/publications/cdt (official Current Dental Terminology code definitions and descriptions)
- **ClinicalTrials.gov** — clinicaltrials.gov (dental research studies for evidence-based treatment rationale)
- **PubMed Clinical Dentistry Literature** — pubmed.ncbi.nlm.nih.gov (peer-reviewed clinical dentistry research and systematic reviews)
