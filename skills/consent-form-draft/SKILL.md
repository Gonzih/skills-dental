---
name: consent-form-draft
description: Drafts an informed consent form for a dental procedure covering procedure description, risks, alternatives, and patient acknowledgment.
triggers: ["consent form", "informed consent dental", "draft consent", "patient consent form"]
---

# Consent Form Draft

## What this skill does
Generates a complete informed consent form for a specified dental procedure. The form covers a plain-language description of the procedure, material risks and complications, available alternatives (including no treatment), and a patient acknowledgment and signature block. Output is suitable as a starting draft for attorney or compliance review before clinical use.

## How to invoke
/consent-form-draft [procedure name, any specific risks or patient factors to highlight]

## Workflow steps

### Step 1 — Identify the procedure
Determine the procedure type (e.g., extraction, implant placement, root canal, periodontal surgery, sedation, orthodontic treatment). Identify whether the consent covers a single visit or an ongoing treatment phase.

### Step 2 — Write the procedure description
Describe the procedure in clear, patient-readable language (6th–8th grade reading level). Explain what will be done, in what area of the mouth, and approximately how long it takes. Avoid unnecessary clinical jargon; define terms when used.

### Step 3 — List risks and potential complications
Enumerate material risks specific to the procedure: common risks (e.g., soreness, swelling), less common but serious risks (e.g., nerve involvement, sinus communication, implant failure), and risks of anesthesia or sedation if applicable. Include a statement that no guarantee of outcome is made.

### Step 4 — Present alternatives
List clinically reasonable alternatives to the proposed treatment, including the alternative of no treatment and its likely consequences. The patient must understand they have a choice.

### Step 5 — Acknowledgment and signature block
Draft a patient acknowledgment section confirming they have read the form, had the opportunity to ask questions, understand the information, and consent voluntarily. Include fields for: patient name (print), patient signature, date, guardian name/signature (if minor), and provider/witness signature.

## Example outputs
A 400–600 word form with a practice name placeholder header, numbered sections, a risks checklist, an alternatives paragraph, and a formatted signature block. Includes a disclaimer that the form is a template requiring professional and legal review before use.

## Live Data Sources
- **MedlinePlus Dental Health Topics** — medlineplus.gov/api (NIH consumer health information on dental procedures, risks, and patient education)
- **AAP and ADA Patient Education Materials** — American Academy of Periodontology and ADA patient-facing procedure guides and risk information
- **CDC Oral Health Data and Statistics** — cdc.gov/oralhealth (population-level oral health statistics to contextualize procedure risks and outcomes)
