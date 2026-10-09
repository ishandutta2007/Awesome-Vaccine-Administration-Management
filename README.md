# Awesome-Vaccine-Administration-Management

## Top Vaccine Administration Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Immunization Registries, Clinical Decision Support & Self-Hosted Vaccination Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial vaccine administration platforms** and **open-source projects** that manage immunization records, forecast vaccine schedules, and orchestrate large-scale vaccination campaigns — from fully managed cloud services to self-hosted digital public goods.



**Examples** include Salesforce Vaccine Cloud, Microsoft Vaccine Management, Epic Systems, Cerner Immunization, CareConnect, Curative, AccuVax, VaxCare, Athenahealth, and WellSky (the category leaders).



**Open-source emphasis**: Vaccine administration management is one of the strongest open-source domains in digital health. **HLN's Immunization Calculation Engine (ICE)** leads as the state-of-the-art open-source clinical decision support system used in Immunization Information Systems (IIS), EHRs, and PHRs worldwide . **OpenSRP2** provides a comprehensive Electronic Immunization Register (EIR) for frontline health workers with offline capability and HL7 FHIR interoperability . **OpenLMIS** delivers an award-winning vaccine supply chain module rated "Fully Compliant" with GAVI's Target Software Standards . **Sunbird RC** and **DIVOC** enable verifiable vaccination credentials at national scale . **ODK** serves as the global standard for offline data collection in immunization campaigns . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Vaccine Cloud](https://www.salesforce.com/)**  

  **Salesforce's vaccine management platform** — appointment scheduling, inventory management, and public health workflows built on Salesforce. **Best for organizations already in the Salesforce ecosystem**.



- **[Microsoft Vaccine Management](https://www.microsoft.com/)**  

  **Microsoft's vaccine management solution** — built on Azure and Microsoft Cloud for Healthcare. **Best for Microsoft-centric healthcare organizations** .



- **[Epic Systems](https://www.epic.com/)**  

  **Leading EHR with immunization query interfaces** — Epic's VXQ/VXR interfaces connect to 35+ state registries and 1 city registry, sending **over 200 million queries annually** . **Best for large health systems** .



- **[Cerner Immunization](https://www.oracle.com/health/)**  

  **Cerner's immunization tracking** — integrated with Cerner Millennium EHR. **Best for Cerner users** .



- **[Curative](https://curative.com/)**  

  **Public health testing and vaccination platform** — large-scale testing and vaccination administration. **Best for public health agencies** .



- **[VaxCare](https://vaxcare.com/)**  

  **Vaccine inventory and administration platform** — manages vaccine supply and billing for healthcare providers. **Best for private practices** .



- **[Athenahealth Immunization](https://www.athenahealth.com/)**  

  **Immunization tracking within athenahealth EHR** — registry reporting and forecasting. **Best for athenahealth users** .



- **[WellSky Vaccine Registry](https://wellsky.com/)**  

  **Vaccine management for post-acute and community care** . **Best for home health and community care** .



## Open-Source GitHub Projects



### Clinical Decision Support & Forecasting



- **[HLN Immunization Calculation Engine (ICE)](https://github.com/HLNConsulting/ICE)**  

  **State-of-the-art open-source clinical decision support for immunizations**, Apache-2.0 licensed . **Used in Immunization Information Systems (IIS), EHRs, and PHRs worldwide** — provides CDS for vaccine forecasting and schedules . **Version 2.46.1** (2025) includes MenB-4C dosing updates, MenABCWY (Penmenvy) support, and COVID-19 seasonal refinements . **Tracks ACIP meeting outcomes** for ongoing vaccine group updates (Pneumococcal, Adult RSV) . **The de facto open-source immunization forecaster** . **Best for clinical decision support in immunization systems** .



- **[VCQI (Vaccination Coverage Quality Indicators)](https://github.com/ropensci/vcqiR)**  

  **Flexible open-source tool for vaccination coverage survey data analysis**, developed by WHO and PAHO . **Calculates indicators for access, coverage, continuity, and quality of vaccination** . **Generates tables and charts directly copyable into reports and presentations** . **Supports DHS, MICS, and EPI surveys** . **Available as Stata scripts (since 2015) and R package vcqiR (since 2025)** . **Best for vaccination coverage survey analysis** .



- **[imuGAP](https://github.com/ACCIDDA/imuGAP)**  

  **Bayesian hierarchical models of vaccine coverage by location, birth cohort, and age**, MIT licensed, published on CRAN (v0.2.0, September 2026) . **Decomposes coverage into lifetime propensity to vaccinate and time-varying force of vaccination** . **Hierarchical spatial structure** (state, county, school) with partial pooling via random effects . **Implemented in Stan and fit via rstan** . **Provides helpers to validate input data and predict coverage from fitted models** . **Best for vaccine coverage modeling and projection** .



### Electronic Immunization Registries



- **[OpenSRP2](https://github.com/opensrp/fhircore)**  

  **Open-source mobile health platform for frontline health workers**, Apache-2.0 licensed . **Electronic Immunization Register (EIR) tracks individual immunization records, schedules follow-ups, and ensures adherence to vaccination schedules** . **Supports multiple languages** (English, Spanish, French) and integrates with analytics dashboards . **HL7 FHIR standard-based interoperability** — can be adapted to national immunization guidelines and integrated with existing health systems . **Part of the Global Goods Product Suite for Immunization** including DHIS2, RapidPro, OpenHIM, and OpenLMIS . **Best for community health worker immunization tracking** .



- **[DIVOC (Digital Infrastructure for Verifiable Open Credentialing)](https://github.com/egovernments/DIVOC)**  

  **Open-source platform for large-scale health campaigns and verifiable certification** . **Manages vaccines, facilities, and vaccinators systematically across geographies** . **Generates digitally verifiable certificates compliant with international standards** . **Modular design** — components can be used together or standalone . **Used for COVID-19 vaccination certification in India** . **Best for national-scale vaccination campaign management** .



- **[Sunbird RC](https://github.com/Sunbird-RC/sunbird-rc-core)**  

  **Open-source framework for building electronic registries and issuing verifiable credentials**, part of the Sunbird Digital Public Good . **Cryptographically signed credentials with keys managed in Vault** . **Built for national scale** — independent microservices on Kubernetes scale from single registry to millions of records . **W3C Verifiable Credentials and DIDs** — no vendor lock-in . **Registries without code** — define schema, get APIs and attestation workflows automatically . **Instant verification via QR code, even offline** . **Best for vaccination credentialing and registries** .



### Supply Chain & Logistics



- **[OpenLMIS](https://github.com/OpenLMIS/openlmis-ref-distro)**  

  **Open-source electronic logistics management information system (LMIS)**, rated **"Fully Compliant" with GAVI's Target Software Standards** . **Vaccine Module (v3)** manages logistics processes at **10,000+ health facilities across 8 geographies** . **Key features**: cold chain equipment (CCE) inventory, temperature monitoring via RTM integration, vaccine stock management with vial wastage tracking, requisitions, order fulfillment, and analytics/reporting . **Microservices architecture** for flexibility and extensibility . **Integrates with DHIS2, OpenSRP, and ERP/WMS systems** . **Best for vaccine supply chain management** .



- **[ODK (Open Data Kit)](https://github.com/getodk)**  

  **Global standard for offline mobile data collection**, recognized as a Digital Public Good . **Used for vaccination monitoring, microplanning, counterfeit detection, vaccination status verification, and safety monitoring** . **Offline-first with barcode scanning, geographic data capture, and multimedia support** . **Integrates with external systems via API** . **Best for field data collection in immunization campaigns** .



### Master Patient Index & Interoperability



- **[SantéMPI](https://github.com/santedb/santernpi)**  

  **Master Patient Index/Client Registry platform**, Apache License 2.0 . **Overcomes barriers to leveraging person-centered data** — unique identity for data consolidation, harmonization, and sharing . **Supports OpenHIE specification, HL7 FHIR, and HL7V2** . **Online/offline capability** for large-scale registration programs including COVID-19 vaccination . **Integrated with immunization information systems in Tanzania and Myanmar** . **Best for patient identity management in immunization systems** .



- **[OpenHIM (Open Health Information Mediator)](https://github.com/jembi/openhim-core)**  

  **Middleware for secure, standards-based health data exchange** . **Facilitates interoperability between immunization systems** including OpenSRP, DHIS2, and OpenLMIS . **Best for health information exchange in immunization programs** .



### Additional Strong Open-Source Options



- **Kids-Vaccination-Management-System** — Flask/MySQL web application for managing children's vaccination records with inventory management and hospital integration (GitHub, January 2025) .

- **Infant-immunization** — React/Node.js/MongoDB platform for healthcare providers to manage infant and maternal immunization schedules (GitHub, August 2025) .

- **mVax** — Duke University project for routine immunization data in Honduras with offline storage and sync (GitHub) .

- **immunify** — Single open-source, country-owned solution for comprehensive immunization supply chain management covering cold chain, vaccine management, and temperature monitoring .

- **DHIS2** — Health Information System for tracking immunization coverage and generating dashboards (recognized Digital Public Good) .

- **RapidPro** — Client-facing SMS reminder system for upcoming vaccinations .



**Frameworks for building custom vaccine administration management solutions**: Combine **HLN ICE** for clinical decision support and vaccine forecasting . Use **OpenSRP2** for electronic immunization registers with offline capability . Deploy **OpenLMIS** for vaccine supply chain and cold chain management . Integrate **DIVOC** or **Sunbird RC** for verifiable vaccination credentials . Choose **ODK** for field data collection in immunization campaigns . Use **SantéMPI** for patient identity management across immunization systems . Integrate **VCQI** or **imuGAP** for coverage analysis and modeling . Note that true enterprise vaccine administration with managed infrastructure, EHR integration, and vendor-supported SLAs (Epic, Cerner, Salesforce Vaccine Cloud) remains primarily commercial territory; open-source stacks provide strong clinical decision support, immunization registries, and supply chain foundations that require integration for complete vaccine administration management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Vaccine administration platforms handle protected health information (PHI) and must comply with HIPAA, GDPR, and applicable public health regulations. Self-hosted solutions require proper security hardening, access controls, and audit logging.

- **Immunization clinical logic requires continuous updates** — vaccine schedules change frequently based on ACIP recommendations. HLN ICE releases updates regularly to maintain clinical accuracy .

- **License considerations**: HLN ICE uses Apache-2.0 , OpenSRP2 uses Apache-2.0 , OpenLMIS uses open-source license , DIVOC is open-source , Sunbird RC is open-source , and SantéMPI uses Apache-2.0 . Verify licensing against your use case before committing.

- **Interoperability is critical** — immunization systems must integrate with EHRs, IIS registries, and supply chain systems using HL7 FHIR and other standards .

- The open-source ecosystem provides strong clinical decision support, immunization registries, and supply chain foundations, but **managed infrastructure, EHR integration, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for public health officials, immunization program managers, and healthcare technologists seeking vaccine administration sovereignty.**

Let's make vaccine administration management more open, transparent, and accessible.
