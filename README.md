# Awesome-Revenue-Recognition

## Top Revenue Recognition Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on ASC 606 / IFRS 15 Compliance, Deferred Revenue, SSP Allocation, Contract Modifications & Automated Revenue Schedules*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Revenue Recognition**. These systems automate the identification of performance obligations, allocation of transaction price (including SSP), timing of revenue recognition (point-in-time or over-time), contract modifications, variable consideration, and generation of compliant journal entries and waterfalls under ASC 606 and IFRS 15.



**Examples** include Zuora, Chargebee, Sage Intacct, Oracle NetSuite, Certinia, Chargezoom, Leapfin, RightRev, Sequence, and Trullion (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted billing, revenue schedule engines, Odoo modules, educational ASC 606/IFRS 15 implementations, and open monetization platforms that can support or feed revenue recognition workflows — ideal for finance engineers, SaaS companies, and organizations seeking transparency and control over complex revenue accounting.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
|---------|-------------|---------|-----------------|
| **[Zuora](https://www.zuora.com/)** | Enterprise revenue and subscription platform with deep ASC 606 / IFRS 15 capabilities (Zuora Revenue) for complex multi-element arrangements, usage-based models, and high-volume processing. | Starting at ~$75,000/year | No free tier (Free Essentials training tier only) |
| **[Chargebee](https://www.chargebee.com/)** | Subscription billing platform with Chargebee RevRec for automated ASC 606 / IFRS 15 revenue recognition, deferred revenue management, and finance automation tailored to SaaS. | Starting at $599/month | Free until $250,000 in cumulative billing |
| **[Sage Intacct](https://www.sage.com/en-us/products/sage-intacct/)** | Cloud financial management system with strong mid-market revenue recognition features, multi-element support, and automated revenue schedules. | Starting at ~$9,000/year | 30-day free trial via personalized sample company |
| **[Oracle NetSuite](https://www.netsuite.com/)** | ERP platform offering Advanced Revenue Management (ARM) for ASC 606 compliance, revenue schedules, and integrated order-to-cash and revenue processes. | Starting at ~$999/month + $99/user/mo | 14-day free trial via certified partners |
| **[Certinia](https://certinia.com/)** | Professional services and ERP cloud platform (formerly FinancialForce) with revenue recognition, billing, and project-based accounting capabilities. | Starting at ~$100,000/year | 30-day trial for specific add-on modules only |
| **[Chargezoom](https://www.chargezoom.com/)** | Billing and payment solutions that support recurring revenue operations and can integrate with broader revenue recognition workflows. | Starting at $20/month | Free forever plan (pay per payment processed) |
| **[Leapfin](https://www.leapfin.com/)** | AI-powered revenue automation platform that transforms transaction and billing data into ERP-ready journal entries and accelerates the close. | Starting at $1,000/month | Interactive demo available (no free trial/tier) |
| **[RightRev](https://www.rightrev.com/)** | Dedicated revenue recognition engine focused on policy-driven ASC 606 / IFRS 15 automation, SSP allocation, and complex contract handling for growth-stage to enterprise SaaS. | Starting at $2,500/month | Live demo available (no free trial/tier) |
| **[Sequence](https://www.sequencehq.com/)** | Modern billing and monetization platform with revenue-related capabilities for usage and subscription businesses. | Starting at $799/month | Live demo available (no free trial/tier) |
| **[Trullion](https://trullion.com/)** | AI-powered platform for revenue recognition and lease accounting, helping finance and audit teams with ASC 606 / IFRS 15 and related compliance. | Starting at ~$3,000/year | Live demo available (no free trial/tier) |



## Open-Source GitHub Projects

- **[Kill Bill](https://github.com/killbill/killbill)**  

  Mature open-source subscription billing and payments platform that provides the transactional foundation many teams extend for custom revenue recognition logic.



- **[Lago](https://github.com/getlago/lago)**  

  Open-source metering, usage-based billing, and subscription management platform with revenue analytics that can feed downstream rev-rec processes.



- **[UniBee](https://github.com/unibee-billing)**  

  Open-source recurring billing and payment management system with admin and user portals suitable for self-hosted subscription operations.



- **[Odoo / SSI Revenue Recognition modules](https://github.com/open-synergy/ssi-revenue-recognition)**  

  Community and specialized Odoo addons implementing performance obligations, revenue recognition schedules, project integration, and related accounting features.



- **[eRev / ASC 606 calculation engines](https://github.com/)**  

  Open-sourced revenue recognition calculation frameworks supporting multi-year SSP allocation, variable consideration, contract modifications, versioning, and journal entry generation.



- **[IFRS 15 / ASC 606 educational prototypes](https://github.com/)**  

  FastAPI and notebook-based showcases that implement the five-step model, performance obligations, residual allocation, and revenue schedules with synthetic data.



- **[Revbot and concept revenue APIs](https://github.com/birchpoplar/revbot)**  

  Experimental open-source APIs and platforms for modeling customers, contracts, revenue segments, and recognition schedules in a SaaS-like construct.



- **[Open billing & monetization platforms (Meteroid, Opencell, etc.)](https://github.com/)**  

  Additional open-source or open-core billing engines that handle subscriptions, usage, and invoicing — providing clean inputs for custom or ERP-based revenue recognition.



- **[Revenue waterfall & reporting scripts](https://github.com/)**  

  Community tools and notebooks that transform CRM or billing data into ASC 606-style revenue waterfall reports and schedules.



- **[InvoiceShelf and self-hosted invoicing](https://invoiceshelf.com/)**  

  Open-source self-hosted invoicing and recurring billing solutions that can serve as the operational layer feeding recognition processes.



### Additional Strong Open-Source Options

- Custom Python/SQL engines that implement the five-step revenue recognition model on top of open billing data.

- ERP community modules (Odoo, ERPNext, and similar) with deferred revenue and contract accounting features.

- Spreadsheet-to-code migrations of SSP allocation and modification logic for auditability.

- Integration patterns that push open billing events into NetSuite, Sage, or other ERPs via APIs.

- AI-assisted IFRS/ASC knowledge bases and checklists that help validate policy application.



**Frameworks for building custom systems**: Use an open billing platform (**Kill Bill**, **Lago**, or **UniBee**) as the source of contracts and invoices, implement or adopt an open ASC 606 / IFRS 15 calculation layer (eRev-style or educational engines), generate schedules and journal entries, and post into an open or commercial general ledger. Orchestrate with dbt or custom pipelines, store versioned contracts for audit, and use local LLMs for policy explanation and modification impact analysis.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Revenue recognition under ASC 606 and IFRS 15 is a highly regulated accounting domain. Open-source tools are typically educational, partial, or foundational; they do not replace professional judgment, audited systems, or formal compliance frameworks.

- Self-hosted solutions handling financial data must meet security, auditability, and internal control requirements appropriate for your organization and jurisdiction.



---

**Made for finance teams, SaaS controllers, revenue accountants, and engineers building transparent monetization and recognition systems.**

Let's make revenue recognition more open, auditable, and automation-friendly.
