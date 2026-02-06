# Balancing Rights to Privacy with the Protection of the Society

MSc Project / Academic Research  
Aalborg University — Cybersecurity  
Academic Year: 2025


## Supervisor
- Qiongxiu Li (Jane)
  
## Students
- Kamrul Islam
- Khagendra Thakurathi
- Mohamod Sahil Ansari
- Newton Sharma
- Rajeev Thapa


## Overview

This repository contains the **full LaTeX source code** of our academic research project that examines the **structural tension between collective cybersecurity and individual privacy** in contemporary digital systems. The project analyzes how **technical architectures, regulatory frameworks, governance mechanisms, and ethical considerations** interact when security measures are deployed at scale, often affecting fundamental rights.Rather than treating security and privacy as opposing goals, this work argues for **integrated, privacy-preserving security design**, supported by adaptive regulation and transparent governance.

---

## Research Objectives

- Analyze how cybersecurity measures can unintentionally undermine individual privacy  
- Evaluate existing **technical, regulatory, and normative safeguards**  
- Assess real-world case studies where this balance succeeded or failed  
- Identify systemic risks such as **mission creep**, **supply-chain compromise**, and **mass surveillance**  
- Propose **design, governance, and policy recommendations** that preserve both security and privacy  

---

## Key Research Questions

- How can cybersecurity systems be designed without eroding fundamental privacy rights?
- What regulatory gaps exist in governing large-scale security technologies?
- When do security measures become disproportionate or structurally unsafe?
- How do transparency and trust influence the effectiveness of security systems?
- Can Privacy-Enhancing Technologies (PETs) reconcile security needs with data protection?

---

## Case Studies Analyzed

### 1. British Airways Data Breach (Magecart Supply-Chain Attack)
- Third-party JavaScript compromise
- GDPR Articles 5(1)(f), 32, and 33 implications
- Accountability of data controllers
- Trade-offs between operational efficiency and security oversight

### 2. COVID-19 Contact-Tracing Applications
- Centralized vs decentralized architectures
- Apple/Google Exposure Notification System (ENS)
- Privacy by Design and PET adoption
- Role of trust, transparency, and voluntary participation

### 3. Facial Recognition Technology in Law Enforcement
- Biometric surveillance risks
- Algorithmic bias and misidentification
- GDPR special category data implications
- EU AI Act and high-risk system classification

### 4. EU Chat Control Proposal (CSAR)
- Mandatory client-side scanning
- Impact on end-to-end encryption
- Proportionality and necessity concerns
- Security risks (model poisoning, hash manipulation)
- Function creep and long-term governance risks

---

## Repository Structure

```
.
├── main.tex
├── setup/
│   ├── preamble.tex
│   └── macros.tex
├── sections/
│   ├── Introduction.tex
│   ├── Literature_review.tex
│   ├── Methodology.tex
│   ├── Threat_landscape_that_impacts_privacy.tex
│   ├── Technical_solutions_and_standards.tex
│   ├── Legal_&_regulatory_analysis.tex
│   ├── Communication_governance_and_trust.tex
│   ├── Case_studies_and_evaluation.tex
│   ├── Recommendations.tex
│   ├── Conclusion.tex
│   └── Use_of_Generative_AI.tex
└── front_pages/
    ├── frontpage.tex
    ├── titlepages.tex
    └── abbreviations.tex
```

---

## Methodology

This project follows a **qualitative analytical methodology**, combining:

- Regulatory and legal analysis (GDPR, AI Act, NIS2, CSAR)
- Technical threat modeling and architectural assessment
- Case-based evaluation of real-world incidents
- Ethical and governance analysis

No personal data was collected or processed.

---

## Key Themes

- Privacy by Design & Default  
- Privacy-Enhancing Technologies (PETs)  
- Zero Trust Architecture  
- Supply-chain security  
- Client-side scanning risks  
- Governance, transparency, and trust  

---

## Recommendations Summary

- Integrate **Privacy by Design** at system architecture level
- Strengthen third-party and supply-chain controls
- Prefer decentralized, PET-based designs where feasible
- Improve transparency and public communication
- Enforce proportionality limits on surveillance technologies
- Develop adaptive, technology-aware regulation

---

## Conclusion

The findings show that **security and privacy failures are rarely purely technical**.  
They are deeply linked to governance decisions, regulatory design, and ethical trade-offs.

Sustainable digital security requires:
- Integrated technical safeguards
- Transparent and accountable governance
- Strong regulatory oversight
- Protection of fundamental rights

---

## Further Research

Future research directions include:

- Hybrid privacy-security architectures
- Advanced differential privacy techniques
- Federated learning under adversarial conditions
- Empirical evaluation of NIS2 implementation
- AI governance and supply-chain security risks

---

## Use of Generative AI Tools

Generative AI tools (GPT-4 family, OpenAI) were used **only** to assist drafting, rephrasing, and structural refinement.

All AI-generated content was:
- Reviewed and edited by the authors
- Fact-checked against primary sources

No confidential or personal data was shared.  
The authors retain full responsibility for the content.

---

## Build Instructions

To compile the document:

```bash
pdflatex main.tex
```

Ensure a full LaTeX distribution (TeX Live or MiKTeX) is installed.

---

## License and Academic Use

This repository is intended for **academic and educational purposes**.

- Not legal advice
- Not an official policy document
- Cite the compiled report when referencing this work
