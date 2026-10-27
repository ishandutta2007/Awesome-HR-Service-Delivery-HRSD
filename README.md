# Awesome-HR-Service-Delivery-HRSD
<<<<<<< HEAD

=======
>>>>>>> 1ee8573662c03764a5a25d3b81a8cbfc2340d7aa
# Top HR Service Delivery (HRSD) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on HR Case Management, Employee Service Experience & HR Operations Automation*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **HR Service Delivery (HRSD)**. These tools enable HR teams to manage employee inquiries, automate HR workflows (onboarding, offboarding, leave, benefits), deliver self-service experiences, and maintain compliance—treating HR services with the same operational discipline as IT service management.

**Examples** include ServiceNow HR Service Delivery, Workday HCM, SAP SuccessFactors, BambooHR, Rippling, Zenefits, ADP Workforce Now, Oracle Fusion Cloud HCM, UKG Pro, and Personio (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted HR management systems, case management, and employee self-service—ideal for organizations building sovereign HRSD infrastructure without per-employee licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow HR Service Delivery](https://www.servicenow.com/)**  
  Enterprise HRSD on the Now Platform with HR Case Management organized by Centers of Excellence (COEs) such as Benefits, Payroll, Employee Relations, and Onboarding; the December 2025 release adds AI-generated resolution notes on case closure, image attachment summarization via DocIntel, skill sensing in Learning, and alumni experience features including a new Alumni Center portal . Global implementations use a standardized COE → Topic Category → Topic Detail → HR Service hierarchy with country-specific HR Services for localized workflows .

- **[Workday HCM](https://www.workday.com/)**  
  Enterprise cloud HCM platform unifying core HR, payroll, recruiting, talent management, learning, and workforce planning; features Skills Cloud (an intelligent skills foundation) and AI agents that operate on unified people data .

- **[SAP SuccessFactors](https://www.sap.com/)**  
  Cloud Human Experience Management (HXM) suite with Employee Central for global master data, Onboarding, Performance & Goals, Compensation, Learning, and Story Reports analytics; built on the BizX platform with shared data model and integrated Joule AI agent .

- **[BambooHR](https://www.bamboohr.com/)**  
  HRIS for small to mid-sized businesses with employee records, time-off tracking, onboarding, and document management; users consistently praise ease of use and clean interface, though reporting depth and pricing increases are noted concerns .

- **[Rippling](https://www.rippling.com/)**  
  All-in-one HCM built on a single data model (the Employee Graph), covering HR, payroll, benefits, time tracking, and compliance across 180+ countries; automates onboarding/offboarding and flags compliance risks with 650+ integrations .

- **[Zenefits](https://www.zenefits.com/)**  
  Consolidated HR platform for small businesses combining payroll, benefits, onboarding, and time tracking in a single app; users note it is useful but could be more intuitive .

- **[ADP Workforce Now](https://www.adp.com/)**  
  Payroll and HCM platform with the ADP WorkForce Suite (integrated from WorkForce Software acquisition) adding global time and attendance, scheduling, absence management, and predictive workforce analytics across 140+ countries .

- **[Oracle Fusion Cloud HCM](https://www.oracle.com/)**  
  Global HR platform with Workforce Deployment, Enterprise Profile, Legal Structures, Organization Structures, Absence Management, Time and Labor, and HCM Data Loader for bulk operations .

- **[UKG Pro](https://www.ukg.com/)**  
  All-in-one HCM suite (Gartner Magic Quadrant Leader for 1000+ employee enterprises) integrating HR, payroll, talent, timekeeping, scheduling, and compliance with AI-assisted analytics; includes UKG Wallet for earned wage access .

- **[Personio](https://www.personio.com/)**  
  European HR platform for SMBs with Core HR, Payroll, Performance & Development, Surveys, and Analytics; the AI Assistant now enables employee self-service, with AI-powered payslip parsing and career frameworks added in 2025 .

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
