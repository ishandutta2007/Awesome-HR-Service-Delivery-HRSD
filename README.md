# Awesome-HR-Service-Delivery-HRSD

## Top HR Service Delivery (HRSD) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on HR Case Management, Employee Service Experience & HR Operations Automation*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **HR Service Delivery (HRSD)**. These tools enable HR teams to manage employee inquiries, automate HR workflows (onboarding, offboarding, leave, benefits), deliver self-service experiences, and maintain compliance—treating HR services with the same operational discipline as IT service management.

**Examples** include ServiceNow HR Service Delivery, Workday HCM, SAP SuccessFactors, BambooHR, Rippling, Zenefits, ADP Workforce Now, Oracle Fusion Cloud HCM, UKG Pro, and Personio (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted HR management systems, case management, and employee self-service—ideal for organizations building sovereign HRSD infrastructure without per-employee licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description & Key Capabilities | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[ServiceNow HR Service Delivery](https://www.servicenow.com/)** | Enterprise HRSD on the Now Platform featuring HR Case Management organized by Centers of Excellence (COEs: Benefits, Payroll, Employee Relations, Onboarding). Includes AI-generated resolution notes, DocIntel attachment summarization, skill sensing in Learning, and an Alumni Center portal. Localized workflows use a COE → Topic Category → Topic Detail hierarchy. | **~$100 – $180 per fulfiller/agent/month** (or ~$6 – $12 per employee/month for employee self-service access) on HRSD Standard/Professional; enterprise contracts typically require a minimum annual commitment of **$20,000 – $30,000/year** (typically 3-year agreement). | **No production free trial.** Offers a free **Personal Developer Instance (PDI)** via the ServiceNow Developer Program (1 sandbox instance, auto-reclaimed after 10 days of inactivity; restricted to non-production dev/testing of HRSD plugins without SLA or production support), plus untimed interactive guided web tours. |
| **[Workday HCM](https://www.workday.com/)** | Enterprise cloud HCM platform unifying core HR, payroll, recruiting, talent management, learning, and workforce planning. Features Skills Cloud (intelligent skills foundation) and AI agents that operate across unified employee data. | **~$34 – $42 per employee/month (PEPM)** for baseline Core HCM (annualized at ~$96 – $504/employee/year depending on bundled modules), with enterprise annual contract minimums starting around **$100,000/year** (typically 3-to-5-year agreement terms). | **No self-service free trial for core HCM.** Provides free interactive, agent-led simulated workflow demos on workday.com (covering HR and payroll journeys) and customized 1-on-1 sales demos. (Note: A separate 30-day trial is restricted solely to Workday Adaptive Planning). |
| **[SAP SuccessFactors](https://www.sap.com/)** | Cloud Human Experience Management (HXM) suite with Employee Central for global master data, Onboarding, Performance & Goals, Compensation, Learning, and Story Reports analytics; built on BizX platform with shared data models and integrated Joule AI agent. | **$6.30 – $8.00 per employee/month (PEPM)** (~£4.70/user/month on G-Cloud) for Employee Central; direct enterprise contracts enforce a minimum purchase quantity of **1,000 users/employees** (~$75,600/year baseline software commitment). | **30-day free trial** available on sap.com. Access is granted to a shared cloud tenant pre-populated with sample demo data (limited to core HR self-service, org chart browsing, time-off requests, and goal setting; English only, no administrative configuration, integrations, or data export; extended 28-day practice sandbox available via SAP Learning Hub). |
| **[BambooHR](https://www.bamboohr.com/)** | HRIS designed for small to mid-sized businesses with employee records, automated onboarding/offboarding, time-off tracking, document management, and employee self-service portal. | **$250/month flat fee** for up to 25 employees, or **$10.00 – $10.25 per employee/month (PEPM)** for companies with >25 employees on the Core tier. (Payroll, Benefits, and Time Tracking sold as modular add-ons). | **7-day free trial** (no credit card required). Includes full access to a Core HR sandbox pre-populated with demo sample data, employee directories, onboarding checklists, time-off tracking, and mobile app; live payroll processing and benefits administration add-ons are excluded. |
| **[Rippling](https://www.rippling.com/)** | All-in-one HCM built on a unified data layer (Employee Graph) covering HR, payroll, benefits, time tracking, and compliance across 180+ countries; automates onboarding/offboarding and flags compliance risks across 650+ integrations. | **$8 per employee/month (PEPM)** plus a **$35/month base platform fee** for the Unity Core HR platform (covers employee directory, onboarding, and document management; payroll and time tracking are additional modular add-ons). | **No general free trial for full core HR/payroll suite.** Offers untimed browser-based interactive click-through demo sandboxes and a **14-day free trial limited specifically to the Rippling IT Cloud module** (device & identity management); full platform evaluation requires a scheduled guided demo. |
| **[Zenefits](https://www.zenefits.com/)** | Consolidated HR platform (TriNet Zenefits) for SMBs combining automated onboarding, employee management, scheduling, time tracking, and benefits administration in a single dashboard. | **$8 per employee/month (PEPM)** billed annually (or **$10 PEPM** billed monthly) on the Essentials tier; subject to a mandatory **5-employee minimum billing threshold** ($40/month minimum; payroll is an optional $6 PEPM add-on). | **No self-service free trial or free-for-ever plan** (legacy 14-day trial discontinued). Offers free interactive guided tour walkthroughs and scheduled live sales demos; accounts require the 5-seat minimum billing upon signup. |
| **[ADP Workforce Now](https://www.adp.com/)** | Enterprise payroll and HCM platform for mid-market and enterprise businesses, featuring ADP WorkForce Suite with global time & attendance, absence management, scheduling, and predictive workforce analytics across 140+ countries. | **~$18 – $30 per employee/month (PEPM)** on the Select baseline tier (covers core payroll and HR management; typically for 50+ employees); one-time implementation fee typically runs 10% – 20% of first-year contract value. | **No self-service free trial or free-for-ever tier.** Provides free self-guided interactive video tours and scenario click-paths on adp.com (demonstrating payroll runs and workforce analytics), plus personalized live sales demos. |
| **[Oracle Fusion Cloud HCM](https://www.oracle.com/)** | Global enterprise HR platform covering Workforce Deployment, Enterprise Profiles, Legal and Organizational Structures, Absence Management, Time and Labor, and HCM Data Loader for bulk operations. | **$13.00 – $15.00 per hosted employee/month (PEPM)** list price for Global Human Resources (Core HR), typically subject to a **500 – 1,000 employee minimum purchase requirement** and 3-year contract term (enterprise negotiated discounts typically 30% – 50% off list). | **No self-service SaaS free trial.** Offers untimed interactive browser-based guided tours on oracle.com; structured 14-to-30-day proof-of-concept (PoC) sandboxes available upon request via sales; standard Oracle Cloud Free Tier ($300 credits / 30 days) covers OCI infrastructure only. |
| **[UKG Pro](https://www.ukg.com/)** | Enterprise HCM and workforce management suite (Gartner Magic Quadrant Leader) integrating HR, payroll, talent, advanced scheduling, timekeeping, and compliance with AI-assisted analytics and UKG Wallet earned-wage access. | **~$26 – $41 per employee/month (PEPM)** for enterprise core HCM and workforce management packages (commonly for 1,000+ employees; multi-year 3–5 year agreements); implementation fees typically add 40% – 70% of first-year software fees. | **No public self-service free trial or free tier.** Prospective clients evaluate via scheduled personalized live demos conducted by sales solution engineers, alongside recorded feature walkthrough sessions. |
| **[Personio](https://www.personio.com/)** | European all-in-one HR platform for SMBs with Core HR, Payroll, Performance & Development, Surveys, and Analytics; features an AI Assistant for employee self-service, payslip parsing, and career frameworks. | **€7.60 per employee/month (PEPM)** for companies with 50+ employees (Core plan); **€14.00 per employee/month (PEPM)** for companies with 10–49 employees (Core + Payroll bundle); subject to a 12-month minimum contract and tiered implementation fee. | **14-day free trial** (no credit card required). Full access to Core HR sandbox with sample/uploaded employee data; capped at 3 e-signature requests, 50 survey participants, 5MB document storage per employee; external job board publishing and payroll processing disabled. |

## Open-Source GitHub Projects

- **[Horilla HRMS](https://github.com/horilla/horilla-hr)**  
  Comprehensive open-source HRMS (v2.0, Docker-deployable) covering the full employee lifecycle: Employee Management with LDAP integration, Recruitment, Onboarding/Offboarding workflows, Attendance with biometric integration, Leave Management with policy enforcement, Payroll automation, Performance Management, Asset Management, and a centralized HR Helpdesk ticketing system . This is the most complete open-source HRSD-adjacent platform, with active v2.0 development and a published Docker image (`horilla/horilla-hr:2.1.5`).

- **[OrangeHRM](https://github.com/orangehrm/orangehrm)**  
  Long-established open-source HRM system (GPL-3.0, since 2005) with modules for Personnel Information Management, Leave/Time-off, Time and Attendance, Performance Management, Recruitment (ATS), and On/Off-boarding . The Starter edition is free and self-hostable; Advanced adds API access and advanced reporting . Suitable for organizations wanting a proven, modular HR foundation with community support.

- **[Frappe HRMS](https://github.com/frappe/hrms)**  
  Open-source HR and Payroll software built on the Frappe Framework (the same stack as ERPNext), with ~9k GitHub stars; covers employee records, leave, attendance, payroll, and performance within a modern Python/Vue stack that integrates naturally with Frappe-based ERP deployments .

- **[HRKit](https://github.com/AnitChaudhry/HRKit)**  
  Lightweight, local-first HR application (MIT, Python + SQLite) with 11 modules including Documents, Leave, Attendance, Payroll, Performance, Onboarding, Exits, and Recruitment with AI scoring; brings your own OpenAI-compatible AI key; per-employee folder layout makes backup trivial; runs entirely on your own machine with no hosted SaaS version . Best for small teams or privacy-focused deployments wanting a simple, auditable HR tool.

### Additional Strong Open-Source Options

- **Sentrifugo** — Open-source HRMS with modules for employee management, leave, time tracking, and performance; referenced in HR software comparisons but with less recent activity than Horilla or OrangeHRM .
- **Odoo HR** — HR module within the Odoo ERP ecosystem covering employee directory, leave management, recruitment, and appraisals; benefits from integration with Odoo's accounting and project modules.

**Frameworks for building custom systems**: Combine **Horilla HRMS** for full lifecycle HR operations with helpdesk ticketing, **OrangeHRM** for a proven modular HR foundation with recruitment and performance, and **HRKit** for lightweight local-first deployments with AI-assisted workflows in a self-hosted HRSD stack; integrate with **Frappe/ERPNext** if an ERP-linked HR system is required.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- HRSD platforms handling employee personal data must comply with applicable privacy regulations (GDPR, CCPA, etc.) and labor laws; access controls and audit trails are essential for sensitive HR records.
- Self-hosted open-source solutions vary in depth—Horilla and OrangeHRM provide broad HR operations coverage, but full HRSD case management with COE structures, knowledge bases, and SLA-driven workflows typically requires configuration or commercial platforms like ServiceNow.
- Verify license terms for commercial use; OrangeHRM Starter uses GPL-3.0 , HRKit uses MIT , and Horilla and Frappe HRMS are open-source (check repositories for specific licenses).

---

**Made for HR operations teams, people managers, HRIS administrators, and employee experience leaders.**  
Let's make HR service delivery more open, employee-centric, and operationally efficient.
