[README.md](https://github.com/user-attachments/files/31393158/README.md)
# Online Property Tax Payment Portal — E-Governance Internship

Project work for the **Junior Web Developer – E-Governance & Digital Services** internship
(29 Jul 2026 – 26 Aug 2026), prepared by **Priyam Bhowmik**.

Repo: [github.com/Priym1/Online-Property-Tax-Payment-Portal](https://github.com/Priym1/Online-Property-Tax-Payment-Portal)

This repo tracks the planning, design, and (upcoming) build artifacts for a citizen-facing
e-governance digital service: an **Online Property Tax Payment Portal** that lets property
owners search their property, view tax dues, pay online, and receive a digital receipt.

## Contents

```
docs/
  Week1-Project-Plan-Report.docx     Week 1 — Planning & Requirements Analysis
  Week2-Responsive-Prototype-Report.docx   Week 2 — Responsive Wireframes & Design Rationale
wireframes/
  week1-process-flow.png             Citizen payment process flow (6 steps)
  week1-user-journey.png             Citizen user journey map (emotions per stage)
  desktop-wireframes.png             High-fidelity desktop wireframes (4 core screens)
  mobile-wireframes.png              Responsive mobile wireframes (3 key screens)
  site-flow.png                      Site navigation / user flow diagram
```

## Week 1 — Planning & Requirements Analysis

Defines the project vision, functional and non-functional requirements, stakeholder
analysis (with two user personas), a risk register, proposed technology stack, and a
4-week project roadmap. See `docs/Week1-Project-Plan-Report.docx`.

## Week 2 — Responsive Web Prototype

Translates the Week 1 plan into a high-fidelity, responsive UI:

- **Core screens:** Login/Registration, Property Search & Bill View, Payment, Receipt/Confirmation
- **Responsive behaviour:** two-column desktop layouts collapse into single-column mobile
  layouts, with a hamburger nav and full-width touch targets
- **Design rationale:** colour palette, typography, card-based layout and status-feedback
  choices, each with reasoning

See `docs/Week2-Responsive-Prototype-Report.docx` for the full write-up.

## Proposed Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js / Express REST API |
| Database | PostgreSQL / MySQL |
| Payments | PCI-DSS compliant gateway (UPI, cards, net banking) |
| Auth | OTP-based login |
| Hosting | Cloud (AWS/Azure) with auto-scaling |

## Roadmap

| Week | Focus |
|---|---|
| 1 | Planning & Requirements Analysis ✅ |
| 2 | UI/UX Design & Responsive Wireframing ✅ |
| 3 | Core Development (search, bill calculation, payment integration) |
| 4 | Testing, Deployment & Handover |
