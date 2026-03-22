# skills-dental

Claude Code skill suite for dentists, dental hygienists, and practice managers.

## Install

```bash
npx @gonzih/skills-dental
```

Or install globally:

```bash
npm install -g @gonzih/skills-dental
```

Then restart Claude Code.

## Skills

### `/treatment-plan-explainer`
Explain a dental treatment plan in patient-friendly language. Covers what's needed, why, the sequence, cost overview, and what to expect at each appointment.

**Usage:**
```
/treatment-plan-explainer D3 #14 needs crown due to cracked cusp, D1 #18-19 composite restorations, periodontal scaling full mouth
```

---

### `/patient-recall-letter`
Write a warm recall or reactivation letter for patients overdue for a visit. Friendly tone, benefit-focused copy, and a clear call to action to schedule.

**Usage:**
```
/patient-recall-letter Patient: Jane Smith, last seen 18 months ago, due for hygiene + perio follow-up
```

---

### `/insurance-narrative`
Write a clinical narrative for a dental insurance pre-authorization. Includes diagnosis, clinical findings, medical necessity argument, and CDT code summary.

**Usage:**
```
/insurance-narrative Tooth #30, D2740 crown, recurrent decay under existing restoration, radiographic evidence of decay to DEJ, CDT D2740
```

---

### `/consent-form-draft`
Draft an informed consent form for a dental procedure. Covers procedure description, material risks, alternatives (including no treatment), and a patient signature block.

**Usage:**
```
/consent-form-draft Surgical extraction #17 impacted mandibular third molar with IV sedation
```

---

## Notes

- All skill outputs are drafts. Clinical and legal review is required before patient use.
- Insurance narratives should be reviewed by the treating provider before submission.
- Consent forms must be reviewed by an attorney licensed in your jurisdiction before clinical use.

## License

MIT
