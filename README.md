# nhs-ckd-risk-calculator
Agile XP group project (Team 33): CKD risk calculator for NHS-style client. My role: Project Manager (planning, UML, testing. demo).

 NHS CKD Risk Calculator (Agile XP Project)

Team 33 – “NephroTrack” | Kingston University**  
Client-style project to design a **CKD (Chronic Kidney Disease) risk calculator** for NHS use.  
I served as **Project Manager**, focusing on **planning, stakeholder comms, UML, testing coordination, and demo delivery**.

 Transparency: This is a **group project**. My coding input was limited; this repo showcases **process, artefacts, and delivery** rather than source code.

---

  Goals & Outcome
- Deliver a **lightweight risk calculator** concept to support early CKD identification.
- Run a **full XP/Agile lifecycle**: user stories, iterations, testing, and a live demo.
- Produce stakeholder-friendly **documentation** (UML, user manual, risks, privacy notes).

 Quick links:
- `diagrams/` – Use Case, Activity, Sequence diagrams  
- `testing/` – Test plan & cases (black-box, acceptance)  
- `docs/` – Requirements, Security & Privacy (GDPR context), User Manual  
- `slides/` – Client pitch / demo deck  

---

 My Role (Project Manager)
- **Planning & Coordination:** Iteration planning, Jira boards, burndown tracking, daily stand-ups.
- **UML & Documentation:** Use Case, Activity, and Sequence diagrams; user manual structure.
- **Testing Lead:** Wrote acceptance criteria, coordinated test execution, logged defects, re-tests.
- **Stakeholder Comms:** Prepared client-facing slide deck, demo narrative, and Q&A handling.
- **Risk & Privacy:** Drafted notes on data minimisation, consent, and Article 32 “security by design”.

---

 System Overview (Concept)
- **Inputs:** Demographics + clinical values (e.g., eGFR, creatinine, ACR, BP)
- **Logic:** Rule-based risk bands (Low/Moderate/High) + clinician guidance text
- **Outputs:** Risk category, suggested next steps, printable summary

*(No patient data in this repo. Any screenshots use synthetic values.)*

---

 Testing Approach
- **Acceptance tests** against user stories (Given/When/Then).
- **Black-box tests** for input validation & risk banding.
- **Usability checks** for clinician readability.

See `testing/`.

---

 Security & Privacy (High-level)
- GDPR-aligned **data minimisation**, no unnecessary identifiers.
- **Role-based access** (clinician vs patient views) in concept.
- **Logging** only for clinical audit, not analytics of personal data.
- outlines in `docs/security_privacy_notes.md` (to be added).

---

 Tools
Jira • Lucidchart • UML • MS Office/Google Docs • 

---

 Artefacts
- **Diagrams:** `diagrams/` (PNG/PDF)  
- **Pitch deck:** `slides/NephroTrack_Pitch.pdf`  
- **User Manual (excerpt):** `docs/User_Manual_Short.pdf`

---

 Credits
Team 33 – NephroTrack (XP) — Role: **Project Manager**  
University project (educational use).

---

 Contact
**Joe Coffee** – London, UK  
`josephcoffeecyber@gmail.com` • [LinkedIn](https://www.linkedin.com/in/joe-coffee1993/)
