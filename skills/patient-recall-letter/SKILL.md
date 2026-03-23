---
name: patient-recall-letter
description: Writes a warm, personalized patient recall or reactivation letter explaining why they're overdue, what the appointment will cover, and making it easy to schedule.
triggers: ["recall letter", "reactivation letter", "patient overdue letter", "bring patient back"]
---

# Patient Recall Letter

## What this skill does
Generates a warm, professional recall or reactivation letter for patients who are overdue for a hygiene visit or have not been seen in an extended period. The letter explains why regular care matters, what the appointment will include, and provides a clear, easy call-to-action to schedule. Tone is friendly and caring — never guilt-inducing.

## How to invoke
/patient-recall-letter [patient name, time since last visit, any relevant notes e.g. "needs perio follow-up"]

## Workflow steps

### Step 1 — Gather context
Identify the patient's name, time elapsed since last visit, the type of recall (routine hygiene, perio maintenance, incomplete treatment, post-op check), and any personal details to include (e.g., treatment previously discussed).

### Step 2 — Open with warmth
Begin with a friendly greeting that acknowledges the patient by name and expresses genuine care. Reference how long it has been without making them feel judged.

### Step 3 — Explain why it matters
In 2–3 sentences, remind the patient why regular dental visits are important for their specific situation. Keep it benefit-focused ("catch small issues early") rather than fear-based.

### Step 4 — Describe what the visit will include
Briefly outline what their appointment will cover: exam, cleaning, X-rays if due, any follow-up items. This reduces anxiety by setting clear expectations.

### Step 5 — Clear call to action
End with a single, frictionless CTA: phone number, online booking link placeholder, or reply-to-this-letter option. Offer flexible scheduling. Close warmly with the practice name and provider signature block.

## Example outputs
A 200–300 word letter with a subject line, personalized greeting, 3–4 short paragraphs, and a bolded scheduling CTA. Suitable for print mail or email with minimal edits.

## Live Data Sources
- **ADA Evidence-Based Clinical Practice Guidelines** — ada.org/resources/research/science-and-research-institute/evidence-based-dental-research (recall interval and preventive care recommendations)
- **AAPD Periodontal Classification System** — American Academy of Pediatric Dentistry guidelines for recall frequency based on caries risk and periodontal status
- **PubMed Recall Interval Research** — pubmed.ncbi.nlm.nih.gov (peer-reviewed studies on optimal recall intervals and patient reactivation outcomes)
