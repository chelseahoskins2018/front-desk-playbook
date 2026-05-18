# Front Desk Playbook
### A Dispensary Knowledge Management System

**Built by Chelsea Hoskins** · Knowledge Architect & Instructional Designer

---

## About This Project

This is a fully interactive, web-based knowledge management system designed from scratch for a licensed cannabis dispensary front desk operation. It serves two distinct user groups simultaneously:

- **New hire onboarding** — step-by-step procedural guidance for staff learning the role
- **Performance support** — a quick-reference tool for experienced staff rotating through the front desk

The system was built without direction or existing documentation — it was identified as a compliance gap, scoped, designed, and delivered entirely on the author's own initiative. After internal review, it was escalated to area leadership and adopted company-wide.

---

## What's Inside

### 10 Check-In Procedure Playbooks
Organized by a dual-taxonomy navigation system designed around **how users think in the moment**, not how the underlying system is structured:

| Patient / Customer Type | No Online Order | With Online Order |
|---|---|---|
| Medical Caregiver | ✅ | ✅ |
| New Medical Patient | ✅ | ✅ |
| Returning Medical Patient | ✅ | ✅ |
| New Recreational Customer | ✅ | ✅ |
| Returning Recreational Customer | ✅ | ✅ |

### 3 Issue Resolution Supplements
Standalone reference pages for compliance edge cases, cross-linked inline from relevant procedure steps:

- **Address Mismatch Protocol** — 4 scenario paths for OHMM/ID address discrepancies
- **Problematic ID Handling** — decision table covering 8 ID types with scripted responses
- **Expired Medical Card Protocol** — age-based decision matrix with compassionate service scripts

---

## Design Principles

**User-centered navigation.** The home page offers two entry points — "I need to check in a..." and "I need help with a..." — because a stressed front desk employee searches by *situation*, not by system category.

**Consistent page structure.** Every procedure page follows the same format: Objective → Core Principle → Prerequisites → Numbered steps with a Screenshot/Link/Tip column. This structure reduces cognitive load for users under time pressure.

**Inline cross-linking.** Supplement pages are linked directly within the step where they become relevant — not in a sidebar or footer. A staff member handling a cracked ID doesn't have to navigate away; the link is right there at step 2.

**Compliance-first content.** Warnings, STOP notices, and compliance notes are surfaced prominently within the step table — not buried in footnotes. Critical information must be impossible to miss in a legally sensitive environment.

---

## The Compliance Environment

This system was built for one of the most legally complex retail environments that exists:

- **HIPAA** — protected health information handled at every interaction
- **PII** — personally identifiable information across all patient and customer types
- **Ohio State Cannabis Regulations** — strict dispensing rules, card verification requirements, registry compliance
- **Dual-use environment** — medical and adult-use recreational customers in the same facility

Every procedure was researched and documented to reflect the specific legal requirements of this environment. Where state law and store protocol diverge, both are noted explicitly.

---

## Technical Details

Built with semantic HTML5, CSS custom properties, and vanilla JavaScript — no frameworks, no dependencies. Fully responsive. Designed to load instantly on any device, including the tablets and shared computers common in retail dispensary environments.

```
playbook/
├── index.html                  # Home page with interactive navigation
├── shared.css                  # Unified design system
├── caregiver-oo.html           # Medical Caregiver (Online Order)
├── caregiver-noo.html          # Medical Caregiver (No Online Order)
├── nmp-oo.html                 # New Medical Patient (Online Order)
├── nmp-noo.html                # New Medical Patient (No Online Order)
├── rmp-oo.html                 # Returning Medical Patient (Online Order)
├── rmp-noo.html                # Returning Medical Patient (No Online Order)
├── nrc-oo.html                 # New Recreational Customer (Online Order)
├── nrc-noo.html                # New Recreational Customer (No Online Order)
├── rrc-oo.html                 # Returning Recreational Customer (Online Order)
├── rrc-noo.html                # Returning Recreational Customer (No Online Order)
├── address-mismatch.html       # Issue: Address Mismatch Protocol
├── problematic-id.html         # Issue: Problematic ID Handling
└── expired-medical-card.html   # Issue: Expired Medical Card Protocol
```

---

## Related Portfolio Work

This project is part of a broader knowledge management and instructional design portfolio:

- **Ohio Cannabis Compliance Training** — A 4-section eLearning module built in Articulate Rise 360, covering Ohio regulatory requirements for dispensary employees. Includes scenario-based application and embedded knowledge checks. *(Available upon request)*
- **Case Study** — A full written case study documenting the problem, approach, design decisions, and impact of this Playbook is available upon request.

---

## About the Author

**Chelsea Hoskins** is a knowledge management specialist, instructional designer, and regulatory research professional based in Goshen, Ohio.

She brings a rare combination of:
- **Federal regulatory expertise** — 3+ years as a Wage & Investment Account Manager at the IRS, resolving 100+ complex business tax accounts weekly
- **Knowledge architecture** — designing multi-page, cross-linked information systems for regulated environments
- **Instructional design** — building training tools for dual audiences (new hire onboarding and performance support) using Articulate Rise 360 and SharePoint
- **Compliance research** — translating complex regulatory frameworks into clear, actionable documentation

📩 **Open to remote opportunities** in Knowledge Management, Instructional Design, Regulatory Research, and Compliance Analysis.

**Contact:** chelsea.hoskins2018@gmail.com · [LinkedIn](https://www.linkedin.com/in/chelsea-hoskins-4b22a8234)

---

*This repository contains a portfolio demonstration version of the Playbook. Proprietary system screenshots and internal identifiers have been removed or anonymized.*
