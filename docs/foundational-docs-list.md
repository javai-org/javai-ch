# Foundational Documents for Enterprise AI Compliance in Europe

For an enterprise trying to use AI lawfully in Europe, the documents separate into three groups: foundational EU-wide documents, privacy/data-protection documents, and sector-specific supervisory documents. The single most important starting point is the EU AI Act itself, because it is the binding text that sets the risk-based framework and the core obligations around risk management, data governance, technical documentation, logging, human oversight, and accuracy/robustness/cybersecurity for high-risk systems.

---

## 1) Foundational EU Documents Every Enterprise Should Know

### 1. Regulation (EU) 2024/1689 — the AI Act

This is the anchor document. For enterprise use, the most operationally important parts are the provisions on high-risk AI systems and deployer obligations. In practice, this is where you get the legal basis for lifecycle risk management, testing, logging, post-market monitoring, human oversight, and declared accuracy metrics.

### 2. Commission Guidelines on Prohibited AI Practices

Published in February 2025, these help enterprises determine whether a proposed use case is outright forbidden under the Act. This matters before any governance or control design work, because some ideas should simply be stopped at intake.

### 3. Commission Guidelines on the AI System Definition

Also published in February 2025, these are essential for scope analysis. Many enterprises first need to answer: "Is this actually an AI system under the Act?" This guidance is the practical document for that threshold question.

### 4. AI Literacy Q&A

This is more important than it looks. Article 4 already applies, and the Commission's Q&A makes clear that providers and deployers need measures to ensure staff have sufficient AI literacy. For enterprise roll-outs, this is one of the earliest compliance duties to operationalise.

### 5. Guidelines on the Scope of Obligations for Providers of General-Purpose AI Models

If your enterprise builds, substantially modifies, or places GPAI models on the market, this is key. It clarifies who counts as a GPAI provider and what the obligations are, including technical documentation, copyright policy, training-data summaries, and — where systemic risk is involved — risk assessment, mitigation, incident reporting, and cybersecurity.

### 6. General-Purpose AI Models in the AI Act — Q&A

This is a useful companion to the GPAI guidelines. It is not the legal text, but it helps enterprises interpret how the Commission currently reads the GPAI regime in practice.

### 7. AI Act Service Desk Materials on Articles 9, 12, 13, 15 and 26

These are not themselves binding law, but they are among the best official implementation aids for enterprise teams. In particular:

- **Article 9** for continuous risk management and testing
- **Article 12** for automatic logging and traceability
- **Article 13** for instructions, limitations, and performance information
- **Article 15** for accuracy, robustness, cybersecurity, and lifecycle consistency
- **Article 26** for deployer monitoring, oversight, logging retention, and incident handling

---

## 2) Documents Most Relevant to Testing, Monitoring, and Performance Assurance

If your specific interest is enterprise controls around thresholds, validation, drift, monitoring, traceability, and operational performance, the most important European documents are these:

### AI Act, Articles 9, 12, 13, 14, 15 and 26

Taken together, these create the closest thing the EU currently has to an enterprise AI assurance spine: risk management, record-keeping, transparency to deployers, human oversight, declared performance characteristics, and deployer-side monitoring.

### Commission Implementation Guidance Pipeline (announced December 2025)

The Commission announced further guidance on high-risk classification, high-risk requirements, provider/deployer obligations, serious incident reporting, substantial modification, FRIA templates, post-market monitoring templates, and simplified QMS for SMEs. For enterprise compliance teams, this tells you where the most practical future documentation will emerge.

### Code of Practice / Transparency Materials for AI-Generated Content

These matter if your enterprise deploys chatbots, content generators, or deepfake-adjacent tooling. They help operationalise Article 50 transparency obligations.

---

## 3) Key Privacy and Data-Protection Documents from European Regulators

For most enterprises, AI compliance is not just "AI Act compliance." It is also GDPR / ePrivacy / public-sector data-protection compliance. These documents are therefore central.

### 8. EDPB Opinion 28/2024 on AI Models and Personal Data

This is one of the most important European data-protection documents on AI. It addresses when AI models may be considered anonymous, whether legitimate interests can support model development or use, and the consequences of unlawful personal-data processing in model development. If you use personal data anywhere in model development, fine-tuning, or deployment, this is core reading.

### 9. EDPB Report of the ChatGPT Taskforce

This is valuable because it shows how EU data-protection authorities think operationally about generative AI services. It is not a general enterprise AI manual, but it is highly instructive for governance, transparency, lawful basis, accuracy, and safeguards.

### 10. EDPB Paper: AI Privacy Risks & Mitigations — Large Language Models

This is especially useful for enterprises deploying LLM-based systems. It gets closer to practical risk treatment than high-level legal texts and explicitly discusses deployer responsibilities in relation to provider risk treatment, fine-tuning, and retraining.

### 11. EDPS Guidance for Risk Management of Artificial Intelligence Systems

Although formally addressed to EU institutions, bodies, offices and agencies, it is still one of the best official European documents on structured AI risk management. It is highly relevant for enterprise governance design because it frames AI use through accountability, procurement, deployment, and risk controls.

### 12. EDPS Material on Human Oversight of Automated Decision-Making

This is particularly relevant where enterprises want to rely on "human in the loop" as a control. The EDPS explicitly notes the need for standardised frameworks and metrics to assess whether human oversight is actually effective, which is very important for testing and monitoring claims.

---

## 4) Sector-Specific Documents (Regulated Financial Services)

If the enterprise is in banking, investment services, or insurance, the horizontal AI Act documents are not enough.

### 13. ESMA Statement on AI in Investment Services

Issued in May 2024, this gives initial guidance to firms using AI in investment services for retail clients. It is the clearest sectoral supervisory document for firms in securities/investment markets.

### 14. EIOPA Opinion on Artificial Intelligence Governance and Risk Management

For insurers, this is a major document. It clarifies supervisory expectations and applies a risk-based, proportionate approach to AI governance and use in insurance.

### 15. EBA AI Act: Implications for the EU Banking and Payments Sector

This is highly relevant to banks and payment institutions because it maps the AI Act against banking-sector obligations and supervisory structures.

### 16. EBA Special Topic and Related AI Adoption Reports

These are not the primary binding texts, but they are useful for understanding how banking supervisors see actual market adoption and associated control issues.

---

## 5) Recommended Reading Order

If you want the shortest serious stack:

1. AI Act (EU 2024/1689)
2. Commission guidelines on prohibited practices
3. Commission guidelines on the AI system definition
4. AI Literacy Q&A
5. AI Act Service Desk pages for Articles 9, 12, 13, 15, 26
6. EDPB Opinion 28/2024 on AI models
7. EDPS Risk Management Guidance
8. GPAI obligations guidelines and GPAI Q&A
9. ESMA / EBA / EIOPA sector documents if you are in regulated finance

---

## 6) Subset Most Useful for Enterprise Testing and Monitoring

If narrowed to the documents most aligned with performance thresholds, empirical validation, monitoring, logging, human oversight, and drift/risk control, the top set is:

- AI Act Articles 9, 12, 13, 15, 26
- EDPS Guidance for Risk Management of AI systems
- EDPB Opinion 28/2024 on AI models
- EDPB AI Privacy Risks & Mitigations — LLMs
- Sectoral statements from ESMA / EIOPA / EBA where applicable
