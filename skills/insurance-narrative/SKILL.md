---
name: insurance-narrative
description: Writes a clinical narrative for a dental insurance pre-authorization including diagnosis, clinical findings, medical necessity, and CDT codes.
triggers: ["insurance narrative", "pre-auth narrative", "prior authorization dental", "clinical narrative insurance"]
---

# Insurance Narrative

## What this skill does
Generates a concise, clinically accurate narrative letter for dental insurance pre-authorization requests. It documents the diagnosis, relevant clinical findings, why the proposed treatment is medically necessary, and references the appropriate CDT codes. Written in the formal, objective language payers expect.

## How to invoke
/insurance-narrative [procedure, tooth number(s), diagnosis, clinical findings, CDT code(s), any prior treatment history]

## Workflow steps

### Step 1 — Collect clinical data
Extract or prompt for: patient age/gender (optional), tooth number(s) and surface(s), diagnosis (e.g., recurrent decay, irreversible pulpitis, periodontal disease stage/grade), clinical findings (pocket depths, bleeding on probing, radiographic findings, symptoms), CDT code(s) being submitted, and any prior treatment attempted.

### Step 2 — State the diagnosis clearly
Open with a direct clinical statement: tooth number, diagnosis, and duration or progression. Reference objective findings (radiographic evidence, probing depths, vitality test results) that support the diagnosis.

### Step 3 — Describe clinical findings
List relevant objective data in a structured format. Use clinical terminology appropriate for a dental reviewer. Include radiographic findings (periapical pathology, bone loss percentage, caries depth), periodontal measurements, or other supporting data.

### Step 4 — Establish medical necessity
Explain why the proposed treatment is the appropriate, necessary course of action. Address why less invasive alternatives are not indicated. Reference clinical guidelines where applicable (AAE, AAP, ADA).

### Step 5 — CDT code summary and closing
List each CDT code with a one-line description and the tooth/surface it applies to. Close with the treating provider's name and credentials placeholder and a request for expedited review if urgent.

## Example outputs
A formal 250–400 word narrative on practice letterhead (placeholder), structured with labeled sections: Diagnosis, Clinical Findings, Medical Necessity, Proposed Treatment, and Provider Attestation.

## Live Data Sources
- **CDT-to-ICD-10 Crosswalk Tables** — ADA and CMS published crosswalk references mapping CDT procedure codes to ICD-10 diagnosis codes
- **ADA Claim Form Requirements** — ada.org (ADA Dental Claim Form J430D specifications and payer guidelines)
- **State Medicaid Dental Coverage Schedules** — state Medicaid agency portals (covered procedures, fee schedules, and prior authorization requirements by state)
- **Delta Dental Fee Schedules** — publicly available fee patterns and coverage tier documentation from Delta Dental plan resources
