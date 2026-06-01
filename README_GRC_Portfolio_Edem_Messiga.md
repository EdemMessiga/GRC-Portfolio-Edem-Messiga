# GRC Portfolio Edem Messiga

**ISO 27001 Certified Lead Auditor | Cybersecurity GRC | Bilingual EN/FR | Ottawa, Canada**

> ISO 27001 Certified Lead Auditor with 12 years of enterprise risk governance experience, now bringing executive-level audit discipline to cybersecurity GRC. Hands-on compliance portfolio spanning nine frameworks across eight industries PCI-DSS v4.0, SOC 2, ISO 27001, NIST CSF 2.0, COBIT 2019, PIPEDA, Quebec Law 25, HIPAA, and SOX in financial services, healthcare, government, retail, energy, and health technology. Former CFO and EU program manager. Bilingual EN/FR.

---

## Portfolio at a Glance

| Repository | Framework | Industry | Entity | Key Finding |
|---|---|---|---|---|
| [GRC-PCI-DSS-v4-MapleFinancial](#1-pci-dss-v40--maple-financial-corp) | PCI-DSS v4.0 | Financial Services | Maple Financial Corp | SSH MFA bypass on 6 production servers Critical |
| [GRC-SOC2-TypeI-CareSync](#2-soc-2-type-i--caresync-technologies) | SOC 2 Type I + PHIPA | Healthcare SaaS | CareSync Technologies | Unauthorized PHI sharing with AI vendor Critical breach risk |
| [GRC-ISO27001-GovTech-Ontario](#3-iso-270012022--govtech-ontario) | ISO 27001:2022 | Government | GovTech Ontario | Major NC certification at risk, 90-day closure deadline |
| [GRC-NIST-CSF-NovaSaaS](#4-nist-csf-20--novasaas-inc) | NIST CSF 2.0 | SaaS / Technology | NovaSaaS Inc. | 2.1/5.0 maturity 18-month enterprise readiness roadmap |
| [GRC-PIA-PIPEDA-CanRetail](#5-pia-pipeda--quebec-law-25--canretail-group) | PIPEDA + Quebec Law 25 | Retail | CanRetail Group | 6 Critical findings platform cannot launch as designed |
| [GRC-HIPAA-CrossBorder](#6-hipaa-security-rule--crossborder-health-analytics) | HIPAA Security Rule | Health Technology | CrossBorder Health Analytics | BAA execution blocked 14 prerequisites unmet |
| [GRC-SOX-NorthernPower](#7-sox-section-404--northernpower-energy-corp) | SOX Section 404 | Energy and Utilities | NorthernPower Energy Corp. | Material Weakness undocumented financial report parameter change |
| [GRC-COBIT2019-PacificTrust](#8-cobit-2019--pacifictrust-financial-group) | COBIT 2019 | Financial Services (Trust) | PacificTrust Financial Group | 2.1/5.0 governance maturity OSFI B-13 review in Q4 2026 |

---

## About This Portfolio

Every project in this portfolio simulates a real-world GRC engagement at a fictional Canadian organization. Each project includes:

- A full **Excel workbook** with control assessment, risk register, and remediation or improvement plan
- A formal **Word report** written at a professional audience level suitable for a CISO, Audit Committee, or external auditor
- A **GitHub README** explaining the industry context, regulatory framework, key findings, and lessons learned

All findings are realistic and nuanced compensating controls, recurring vulnerabilities, vendor dependencies, multi-jurisdiction complexity, and regulatory crosswalks appear throughout. The goal is to demonstrate how a GRC practitioner thinks, not just what frameworks they know.

---

## 1. PCI-DSS v4.0 | Maple Financial Corp

**Framework:** PCI-DSS v4.0 (mandatory from March 31, 2024)
**Industry:** Financial Services | Canadian Regional Bank (Tier 1 Merchant, 2.1M card transactions per month)
**Assessment Type:** Internal Gap Assessment (pre-QSA engagement) | OSFI B-10 and B-13 crosswalk

**What this project demonstrates:**
- PCI-DSS v4.0 control assessment across 10 requirements and 25 controls
- Risk-stratified audit sampling with documented rationale
- Compensating control design and PCI-DSS Appendix B documentation
- OSFI regulatory cross-referencing in a Canadian federally regulated bank context
- Pre-QSA readiness opinion writing

**Critical finding:** SSH key-based authentication on 6 production payment servers bypasses MFA entirely. Any compromised SSH key provides direct privileged access to systems processing 2.1M card transactions per month.

**Deliverables:** Excel audit workbook (25 controls, 15 CAPs, engagement overview) | Word gap assessment report (8 sections, OSFI crosswalk, pre-QSA opinion)

---

## 2. SOC 2 Type I | CareSync Technologies

**Framework:** AICPA Trust Services Criteria (SOC 2 Type I) + PHIPA integration
**Industry:** Healthcare SaaS | Cloud EHR platform serving 47 hospitals and 4.2M patient records
**Assessment Type:** SOC 2 Type I readiness (pre-CPA firm engagement) | PHIPA agent obligations throughout

**What this project demonstrates:**
- SOC 2 Type I methodology across all five Trust Services Criteria
- PHIPA legislative analysis integrated with SOC 2 control assessment
- Healthcare AI governance and PHI de-identification standards (Ontario IPC guidance)
- PHIPA breach risk assessment framework (Real Risk of Significant Harm analysis)
- SOC 2 Type I readiness opinion writing for a healthcare SaaS context

**Critical finding:** PHI shared with ClinicalAI Corp for AI model training without BAA, without Privacy Officer approval, and using a pseudonymization method that does not meet Ontario IPC de-identification standards a potential PHIPA breach requiring mandatory IPC notification assessment.

**Deliverables:** Excel controls workbook (32 controls, 12 exceptions, engagement overview) | Word readiness report (8 sections, breach escalation notice, PHIPA-SOC 2 analysis)

---

## 3. ISO 27001:2022 | GovTech Ontario

**Framework:** ISO/IEC 27001:2022 + GO-ITS Government Security Standards
**Industry:** Government | Provincial Crown agency (Ontario.ca citizen portal, 8.3M citizens, 47 services)
**Assessment Type:** Year 2 Annual Surveillance Audit | BSI Group Canada (fictional certification body)

**What this project demonstrates:**
- ISO 27001:2022 ITGC assessment across IAM, change management, logging, cryptography, and supplier risk
- PCAOB-equivalent NC classification (Major NC, Minor NC, OFI) applied to ISO 27001
- Dual-standard analysis ISO 27001 Annex A and Ontario GO-ITS standards simultaneously
- Major NC escalation procedure with 90-day closure deadline and certification suspension risk
- Positive observations section alongside deficiency findings

**Major NC finding:** Access review failed to detect a role change 86 days prior stale entitlements for a government employee with PROTECTED B citizen data access. Certification at risk.

**Deliverables:** Excel ITGC workbook (24 controls, 13 NCs and OFIs, certification impact column) | Word surveillance audit report (9 sections, GO-ITS regulatory framework, remediation timeline)

---

## 4. NIST CSF 2.0 | NovaSaaS Inc.

**Framework:** NIST Cybersecurity Framework 2.0 (NIST, February 2024) | Crosswalked to COBIT 2019, CIS Controls v8, ISO 27001:2022
**Industry:** SaaS / Technology | Series C Canadian B2B SaaS (280 employees, first Fortune 500 client)
**Assessment Type:** Cybersecurity Maturity Assessment and 18-Month Improvement Roadmap

**What this project demonstrates:**
- NIST CSF 2.0 assessment across all 6 functions including the new Govern function
- CMMI-aligned maturity scoring with evidence basis for each subcategory
- Multi-framework crosswalk (COBIT, CIS, ISO 27001) for all findings
- 18-month improvement roadmap with CAD cost estimates and board-level business case
- Quebec Law 25 and PIPEDA regulatory context for a Canadian SaaS company

**Current maturity:** 2.1 / 5.0 overall. SSH MFA gap and 47 unmanaged developer laptops are Critical. No SIEM. No approved cybersecurity strategy. CAD $2.4M enterprise bank contract at stake.

**Deliverables:** Excel maturity workbook (35 subcategories, 13 roadmap initiatives with CAD estimates) | Word maturity report (7 sections, function scorecard, framework crosswalk, board approval page)

---

## 5. PIA PIPEDA + Quebec Law 25 | CanRetail Group

**Framework:** PIPEDA (federal) + Quebec Law 25 / Bill 64 + CASL
**Industry:** Retail | Canadian national retailer (847 locations, 6.8M loyalty members, 2.1M in Quebec)
**Assessment Type:** Privacy Impact Assessment (PIA) | Connected Loyalty Platform launch | Mandatory Law 25 s.3.3 CAI filing

**What this project demonstrates:**
- PIPEDA Ten Principles and Quebec Law 25 dual-framework assessment
- Privacy-by-Default requirement (Law 25 s.9.1) product architecture implications
- AI decision-making disclosure obligations (Law 25 s.12.1) for four AI use cases
- Biometric data governance and necessity test under Law 25 s.12
- Mandatory CAI PIA filing requirements and pre-consultation strategy

**Critical finding:** Privacy-by-Default violations (geolocation and AI profiling enabled by default), bundled consent for sensitive data categories, unauthorized CPG data licensing secondary use, and missing CAI PIA filing. Platform cannot launch in its current state 14 of 17 remediation actions are go-live blockers.

**Deliverables:** Excel PIA workbook (23 assessment items, 17 remediation actions, dual PIPEDA and Law 25 status columns) | Word PIA report (8 sections, consent architecture redesign table, AI governance analysis, CAI filing guidance)

---

## 6. HIPAA Security Rule | CrossBorder Health Analytics

**Framework:** HIPAA Security Rule (45 CFR Part 164, Subpart C) | HITECH Act (2009)
**Industry:** Health Technology | Canadian SaaS company acting as Business Associate for US hospital networks
**Assessment Type:** Internal HIPAA Security Rule Gap Assessment (pre-BAA execution)

**What this project demonstrates:**
- HIPAA Security Rule assessment across all 5 safeguard domains
- Required vs Addressable specification distinction applied throughout
- HITECH breach notification obligations (4-factor test, 60-day CE notification)
- Subcontractor BA chain requirements and BAA execution prerequisites
- HIPAA-PHIPA-PIPEDA three-framework alignment for a Canadian Business Associate

**Key finding:** BAA execution blocked. CrossBorder has been receiving US ePHI since March 2026 without a completed risk analysis, breach notification procedure, or subcontractor BAAs and HIPAA obligations are already active.

**Deliverables:** Excel HIPAA workbook (28 controls, 12 risks with NIST SP 800-30 scoring, 17 remediation actions with BAA blocker column) | Word gap assessment report (8 sections, HHS OCR enforcement context with CMP tiers, HIPAA-PHIPA-PIPEDA alignment table)

---

## 7. SOX Section 404 | NorthernPower Energy Corp.

**Framework:** US SOX Section 302 and 404 | PCAOB AS 2201 | NI 52-109 (Canadian equivalent)
**Industry:** Energy and Utilities | Canadian dual-listed company (TSX and NYSE) | Natural gas, renewables, energy trading
**Assessment Type:** Internal SOX ITGC Pre-Assessment (pre-KPMG fieldwork)

**What this project demonstrates:**
- SOX Section 404 ITGC methodology across Logical Access, Change Management, Computer Operations, Financial Reporting Systems, and IT Risk
- PCAOB AS 2201 deficiency classification Material Weakness, Significant Deficiency, Control Deficiency
- Aggregation risk analysis for Control Deficiencies
- SAP S/4HANA ITGC controls (GRC, Transport Management, SAP BW, RAR module)
- SOX and NI 52-109 dual-framework compliance for a Canadian dual-listed company

**Material Weakness:** SAP cash flow statement report parameter changed in Q3 2025 without a documented change control record affecting 3 consecutive quarters of financial statement presentations. Immediate Audit Committee escalation required.

**Deliverables:** Excel ITGC workbook (22 controls, 16 deficiencies with aggregation risk column, 14 management actions with Audit Committee escalation column) | Word pre-assessment report (9 sections, MW escalation notice, aggregation risk table, SOX-NI 52-109 crosswalk, KPMG readiness timeline)

---

## 8. COBIT 2019 | PacificTrust Financial Group

**Framework:** COBIT 2019 (ISACA, 2018) | All 5 domains, 35 governance and management objectives
**Industry:** Financial Services (Trust and Wealth Management) | BCFSA and OSFI dual-regulated
**Assessment Type:** IT Governance Maturity Assessment | OSFI B-13 Readiness Baseline

**What this project demonstrates:**
- COBIT 2019 capability level assessment across EDM, APO, BAI, DSS, and MEA domains
- OSFI B-13 (Technology and Cyber Risk) regulatory alignment throughout
- Governance vs management distinction board-level accountability vs operational execution
- AI governance risk in a trust company context (estate planning documents)
- Multi-framework crosswalk COBIT 2019 to ISO 27001, NIST CSF, SOX, and OSFI B-13

**Overall maturity:** 2.1 / 5.0. Six critical governance gaps including no board-approved IT governance charter, AI pilot on client estate documents without governance approval, SOC operating Monday to Friday only, and two T24 core banking specialists approaching retirement with no succession plan.

**Deliverables:** Excel governance workbook (35 objectives with capability levels, 12 risks with formula-driven scoring, 12 improvement initiatives with OSFI B-13 impact) | Word governance report (8 sections, OSFI B-13 thematic crosswalk, multi-framework alignment table, board-level improvement roadmap)

---

## Framework and Industry Coverage

| Framework | Canadian Regulatory Crosswalk | Industry |
|---|---|---|
| PCI-DSS v4.0 | OSFI B-10, B-13 | Financial Services |
| SOC 2 Type I | PHIPA (Ontario), PIPEDA | Healthcare SaaS |
| ISO 27001:2022 | GO-ITS 25.0, 25.20, 25.30, 25.50 (Ontario Government) | Government |
| NIST CSF 2.0 | PIPEDA, Quebec Law 25, OSFI B-13 (indirect) | SaaS / Technology |
| PIPEDA + Quebec Law 25 | CAI (Commission d'acces a l'information), OPC | Retail |
| HIPAA Security Rule | PHIPA, PIPEDA, HITECH | Health Technology |
| SOX Section 404 | PCAOB AS 2201 | NI 52-109 (OSC) | Energy and Utilities |
| COBIT 2019 | OSFI B-13, BCFSA Digital Operational Resilience | Financial Services (Trust) |

---

## Certifications

- **ISO 27001 Certified Lead Auditor** | GRC Mastery (2025)
- **Cybersecurity Governance, Risk and Compliance** | GRC Mastery (2025)
- **Google Cybersecurity Certificate** | (2025)
- **Cybersecurity Program (Diploma)** | Conestoga College | In Progress

---

## Connect

**LinkedIn:** [linkedin.com/in/edem-messiga](https://linkedin.com/in/edem-messiga)
**Email:** messigaedemf@gmail.com
**Location:** Ottawa, ON, Canada

---

> All entities, individuals, systems, and regulatory findings across all projects in this portfolio are entirely fictional and created for professional development purposes only. No real organizations, client data, or security incidents are represented.
