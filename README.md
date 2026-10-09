# Awesome-Telecom-CRM

## Top Telecom CRM Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Subscriber Management, BSS/OSS Integration & Self-Hosted Telecom CRM*  

**Last updated: October 2026**



This repository tracks notable **commercial telecom CRM platforms** and **open-source projects** that manage subscriber lifecycles, integrate BSS/OSS workflows, and support telecom-specific operations — from billing and provisioning to number portability and SIM inventory management.



**Examples** include Salesforce Communications Cloud, Amdocs CRM, Netcracker CRM, Oracle Communications, Ericsson Telecom CRM, CSG Systems, Hansen Technologies, Comarch CRM, Cerillion, and Subex (the category leaders).



**Open-source emphasis**: Telecom CRM is anchored by **BillRun CRM** as the most complete open-source CRM designed specifically for telecoms — built on SuiteCRM with OSS interface, subscriber management, and telecom inventory modules . **NMS Prime** delivers a modular CRM, BSS, and OSS platform for telcos and ISPs with provisioning across DOCSIS, FTTH, and WiFi . **Discobole** provides a TM Forum-compliant cloud-native BSS suite deployed at Orange subsidiaries . **Ubilling** offers 15+ years of proven billing and subscriber management for ISPs . **ASTPP** brings an integrated BSS/OCS platform for VoIP and telecom operators . **Romashka Telecom** demonstrates a microservices-based telecom CRM with real-time rating . **BSS-OSS-Rust-Ecosystem** is building a next-generation TM Forum Open API-compliant ecosystem in Rust . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Communications Cloud](https://www.salesforce.com/)**  

  **Salesforce's telecom industry CRM** — subscriber management, order capture, and service assurance built on the Salesforce platform. **Best for telecom operators already in the Salesforce ecosystem**.



- **[Amdocs CRM](https://www.amdocs.com/)**  

  **Communications and media industry software** — CRM, billing, and operations for telecom and media providers. **The enterprise standard for telecom CRM** .



- **[Netcracker CRM](https://www.netcracker.com/)**  

  **Telecom BSS/OSS suite** — CRM, order management, and revenue management for communications service providers.



- **[Oracle Communications](https://www.oracle.com/communications/)**  

  **Enterprise telecom software** — CRM, billing, and network solutions for CSPs.



- **[Ericsson Telecom CRM](https://www.ericsson.com/)**  

  **Ericsson's telecom CRM** — subscriber management and customer care for mobile operators.



- **[CSG Systems](https://www.csgi.com/)**  

  **Telecom revenue management** — billing, CRM, and customer care for telecom operators.



- **[Hansen Technologies](https://www.hansencx.com/)**  

  **Telecom billing and CRM** — customer care and revenue management for utilities and telecom.



- **[Comarch CRM](https://www.comarch.com/)**  

  **Telecom CRM and BSS** — customer management, billing, and analytics for telecom operators.



- **[Cerillion](https://www.cerillion.com/)**  

  **Telecom BSS/OSS suite** — CRM, billing, and convergent charging for CSPs.



- **[Subex](https://www.subex.com/)**  

  **Telecom analytics and revenue assurance** — business optimization and risk management for CSPs.



## Open-Source GitHub Projects



### Telecom-Specific CRM & BSS Platforms



- **[BillRun CRM](https://github.com/BillRun/CRM)**  

  **An open-source CRM designed specifically for telecoms**, based on SuiteCRM . **Built from the ground up for DSPs and operators** — added new modules for OSS interface, subscriber management, and telecom inventory . **Customized SuiteCRM modules** to fit the specific needs of telecom operators . **Integrated with BillRun billing and BillRun Customer Self-Care Portal** to create a robust agile BSS . **Acts as your system of record (SOR)** for managing the full life cycle of customers . **Key features**: manage accounts, customers, and subscription details; provision workflow by interacting with OSS elements (initiating, activating, suspending); manage telecom assets (SIM cards, phones, routers) including stock, shipping, delivery, and returns; bridge to number portability gateway; integrate with payment gateways, IVR systems, and ERP systems . **Best for telecom operators and DSPs wanting a complete open-source CRM+BSS**.



- **[NMS Prime](https://github.com/cablelabs/os-provisioning)**  

  **A modular CRM, BSS, and OSS platform for telcos and ISPs** — built from ISPs, for ISPs . **Community Edition delivers complete OSS Provisioning layer** — technology- and vendor-agnostic service activation and CPE management for **DOCSIS, FTTH, FTTx, DSL, WiFi**, and other access technologies . **Enterprise modules add CRM, BSS, billing, dunning, workforce management**, and more . **Built on Laravel with PHP 8** and modern Bootstrap front end . **Integrates proven open-source infrastructure**: ISC DHCP, Kea, Icinga2, Prometheus, Grafana, Cacti, and more . **Network management capabilities**: CMTS, Router, OLT, and Switch management via SNMP or TR-069; real-time topographic maps; cable ingress detection; generic SNMP GUI creator . **Tested and developed under Rocky 9 (RHEL 9)** . **Best for ISPs wanting full control over provisioning, billing, and customer care**.



- **[Discobole](https://www.ow2.org/)**  

  **Cloud-native BSS (Business Support System) suite compliant with TM Forum standards** . **Supports the full Order to Bill lifecycle** — catalog, configuration, order management, inventory, orchestration, and supporting services like security and notifications . **Selected for deployment in 2026 in an Orange subsidiary in Europe and another in the MEA region** . **Recommended within Orange as an open source solution** with several deployment scenarios — complete suite or individual components . **Addresses convergent mobile and FTTH offerings for B2C customers** . **B2B offerings for Digital Twin use cases being tested** with aeronautics and academic partners . **Showcased at TMF international events and OW2con** . **Best for large telecom operators wanting TM Forum-compliant open-source BSS**.



- **[ASTPP](https://github.com/astpp)**  

  **Open-source VoIP billing and softswitch platform** trusted by telecom operators, ITSPs, and resellers worldwide . **Launched integrated BSS & OCS platform for real-time billing** (June 2026) . **Combines customer lifecycle management, billing, service provisioning, rate management, and online charging** in a centralized environment . **Supports prepaid, postpaid, and hybrid billing models** . **Real-time charging with instant prepaid balance updates** and immediate postpaid usage recording — improves billing accuracy, reduces disputes, and maintains revenue control . **Multi-tenant account management** . **Best for VoIP providers, MVNOs, ISPs, and wholesale carriers**.



### Telecom Subscriber Management & Billing



- **[Ubilling](https://github.com/nightflyza/Ubilling)**  

  **Free, open-source billing and automation system designed for Internet Service Providers (ISPs)** offering fixed broadband access . **Over 15 years of market presence** . **Comprehensive tools for subscriber management, network monitoring, service accounting, and business analytics** . **Allows control and monitoring of a wide range of network equipment** . **Can be easily extended with custom functionality** . **181 GitHub stars and 141 forks** . **Best for ISPs wanting proven billing and subscriber management**.



- **[Romashka Telecom](https://github.com/OlgaRhythm/romashka-telecom)**  

  **Microservices-based telecom CRM and billing system** modeled after a mobile operator . **Four core services**: CDR Generator (generates call events and sends via RabbitMQ), BRT (Billing Real Time — stores call/subscriber info, calculates costs, deducts balances), HRS (High-performance Rating Server — calculates call costs based on tariff type), and CRM (manages subscribers and salon managers — balance top-up, tariff changes, registration, info viewing) . **Tech stack**: Java 17, Spring Boot, Spring Security, PostgreSQL, RabbitMQ, Docker . **Best for learning microservices-based telecom CRM architecture**.



- **[Telecom Subscriber Management System](https://github.com/Mrcaptain-00/python-sql-databse-project)**  

  **Python-MySQL subscriber management system** inspired by TRAI (Telecom Regulatory Authority of India) . **Mini-CRM-like interface for telecom operations** . **Features**: add/update subscriber details (name, phone, network provider, network type); manage identity records (IMSI, MCC, MSIN, ICCID); search by ID, name, phone, or MCC code; data visualization with Pandas; delete subscriber data; menu-driven CLI with user authentication . **Tech stack**: Python, MySQL, Pandas, Matplotlib . **Best for learning telecom subscriber management fundamentals**.



- **[Telecom Subscription System (SQL)](https://github.com/MohamedAtef721/Telecom-Management-System-sql-Project)**  

  **End-to-end telecom database system built with Microsoft SQL Server** . **Manages customers, SIM cards, service plans, subscriptions, usage records (calls, SMS, data), payments, complaints, employees, and departments** . **Business analytics including**: customer activity monitoring, over-usage and churn risk detection, revenue performance analysis, service plan profitability, customer acquisition/retention, and operational performance tracking . **SQL implementation**: functions (business calculations), views (analytics layer), stored procedures (KPIs including ARPU, churn impact, over-usage rate), triggers (auto-payment on subscription activation), indexes (performance optimization), and cursors (operational monitoring) . **Best for learning telecom database design and business intelligence**.



### Next-Generation Telecom Platforms



- **[BSS-OSS-Rust-Ecosystem](https://github.com/rabbittrix/BSS-OSS-Rust-Ecosystem)**  

  **Building an open, secure, and high-performance BSS/OSS ecosystem in Rust**, fully compliant with **TM Forum Open APIs** . **Modular, interoperable, and community-driven foundation for telecom operators worldwide** . **Implemented APIs include**: TMF678 (Billing Management), TMF635 (Usage Management), TMF668 (Party Role Management), TMF632 (Party Management), TMF669 (Identity & Credential Management) . **Revenue management features**: real-time charging integration, usage aggregation and rating (Flat, Tiered, Volume, Time-based), billing cycle management (Monthly, Quarterly, Annually, Weekly), and partner settlement workflows . **Security features**: OAuth 2.0/OIDC with PKCE, MFA (TOTP, SMS, Email, backup codes), RBAC, and comprehensive audit logging . **Best for organizations wanting a modern, TM Forum-compliant BSS/OSS foundation in Rust**.



### Additional Strong Open-Source Options



- **openCRX** — Enterprise-class open-source CRM suite with telecommunications industry focus. Java-based with XML, HSQL, JDBC, Oracle, MySQL, PostgreSQL, IBM DB2, and Microsoft SQL Server support .

- **ICTCRM** — Unified communications integrated CRM built on SuiteCRM with ICTContact for voice, messaging, IVR, and real-time surveys. Multi-tenant and white-label capable. Open source, on-premises Linux deployment .

- **ISP Management Systems** — 21+ public repositories on GitHub for ISP billing, Radius servers, MikroTik integration, and subscriber management .

- **SalesLinkCRM** — Open-source CRM tailored for residential and commercial telecom dealers and sales representatives with carrier qualification tools and sales dashboards .



**Frameworks for building custom telecom CRM solutions**: Combine **BillRun CRM** for complete telecom-specific CRM with OSS integration and subscriber management . Use **NMS Prime** for modular CRM/BSS/OSS with multi-technology provisioning (DOCSIS, FTTH, WiFi) . Deploy **Discobole** for TM Forum-compliant BSS at scale . Integrate **ASTPP** for VoIP billing and real-time charging . Choose **Ubilling** for proven ISP billing and subscriber management . Note that true enterprise telecom CRM with managed infrastructure, carrier-grade billing, and vendor-supported SLAs (Amdocs, Netcracker, Oracle Communications) remain primarily commercial territory; open-source stacks provide strong subscriber management, BSS/OSS integration, and telecom-specific workflows that require integration for complete telecom CRM deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Telecom CRM platforms handle sensitive subscriber data and may involve regulatory compliance obligations (GDPR, telecom-specific privacy regulations). Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Telecom-specific requirements**: Number portability, SIM inventory management, OSS provisioning integration, and real-time charging are often mandatory. Open-source CRM platforms may require significant customization for these workflows .

- **License considerations**: BillRun CRM is built on SuiteCRM (AGPL-3.0) , NMS Prime is open-source , Discobole is an OW2 project , Ubilling is open-source , and ASTPP is open-source . Verify licensing against your use case before committing.

- **System requirements vary**: BillRun CRM requires SuiteCRM infrastructure; NMS Prime needs Rocky 9 (RHEL 9) ; Romashka Telecom requires Docker and RabbitMQ .

- The open-source ecosystem provides strong subscriber management, BSS/OSS integration, and telecom-specific workflows, but **carrier-grade billing, managed infrastructure, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for telecom operators, ISPs, MVNOs, and organizations seeking telecom CRM sovereignty.**  

Let's make telecom CRM more open, transparent, and subscriber-centric.
