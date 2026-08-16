# Awesome-Warehouse-Slotting-Optimization

## Top Crew Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Airline & Maritime Crew Planning, Rostering, Pairing, Legality/FTL Compliance, Qualifications Tracking & Workforce Optimization*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Crew Management**. These systems handle crew pairing, rostering, duty/rest legality (FTL/MLC), qualifications and certifications, training tracking, disruption recovery, and operational assignment for airlines, business aviation, and maritime fleets.

**Examples** include Jeppesen Crew Tracking, NAVBLUE N-Crew, Leon Software, CrewLounge, AIMS Airline Software, Lufthansa Systems NetLine, CrewLogic, Sabre Crew Manager, IBS iFlight Crew, Merlot Aero, Adonis HR, DNV Navigator, COMPAS Crew Management, MESPAS, OCS HR, MarineCFO, Helm CONNECT, SeaTab, SoftTeam Crew, AMOS Crew, and related aviation/maritime solutions (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for crew rostering, shift scheduling, airline pairing optimization, maritime workforce tools, and constraint-based planning libraries — ideal for operators, researchers, and developers seeking transparent foundations in a highly regulated domain.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
### Aviation / Airline Crew Management
- **[Jeppesen Crew Management / Crew Tracking](https://www.jeppesen.com/)**  
  Enterprise crew planning, pairing, rostering, and tracking platform from Boeing/Jeppesen used by major network carriers for optimization at scale and legality compliance.

- **[NAVBLUE N-Crew / Crew solutions](https://www.navblue.aero/)**  
  Airbus group crew management offerings covering planning, rostering, and operational crew support integrated with broader flight operations tools.

- **[Leon Software](https://leon.aero/)**  
  Flexible operations and crew management platform popular with charter, business aviation, and regional operators for duty planning, FTL compliance, and mobile crew access.

- **[AIMS Airline Software](https://www.aims.aero/)**  
  Comprehensive airline operations suite including crew planning, rostering, real-time control, training, and qualification tracking.

- **[Lufthansa Systems NetLine / NetLine Crew](https://www.lhsystems.com/)**  
  Integrated crew planning and tracking within the NetLine operations suite for mid-to-large airlines.

- **[Sabre Crew Manager / AirCentre Crew](https://www.sabre.com/)**  
  Crew management solutions within Sabre’s airline operations portfolio, supporting pairing, rostering, and disruption handling.

- **[IBS iFlight Crew](https://www.ibsplc.com/)**  
  Crew management module within the iFlight suite covering planning, operations, and integration with broader airline systems.

- **[Merlot Aero](https://www.merlotaero.com/)**  
  Airline crew and operations management software focused on rostering, compliance, and operational efficiency.

- **[CrewLounge / CrewLogic and similar](https://)**  
  Specialized crew scheduling, tracking, and communication tools used by various operators.

### Maritime Crew Management
- **[Adonis HR](https://www.adonishr.com/)**  
  Leading maritime HR and crew management platform covering planning, payroll, certifications, MLC compliance, and crew change processes.

- **[AMOS Crew (SpecTec)](https://spectec.net/)**  
  Integrated crew and staff management within the AMOS fleet management ecosystem, supporting planning, work/rest hours, and competency control.

- **[Helm CONNECT](https://www.helmoperations.com/)**  
  Modular maritime operations platform including personnel, crew scheduling, certifications, and compliance features.

- **[DNV Navigator / related solutions](https://www.dnv.com/)**  
  Maritime software and services supporting crew and operational compliance needs.

- **[MESPAS, OCS HR, MarineCFO, SeaTab, SoftTeam Crew and others](https://)**  
  Specialized maritime crew, HR, and fleet personnel management systems used across ship management companies.

## Open-Source GitHub Projects
- **[Crew Rostering Open Source (OR-Tools CP-SAT)](https://github.com/jonaspoelmans/crew_rostering_open_source)**  
  Open-source airline crew rostering implementation using Google OR-Tools CP-SAT solver with regulatory constraint support.

- **[CrewML](https://github.com/mani-mal/crewml)**  
  Open-source Python package for airline crew pairing optimization and assignment using machine-learning approaches on generated pairing data.

- **[pyworkforce](https://github.com/rodrigo-arenas/pyworkforce)**  
  Practical open-source Python library for workforce planning, shift scheduling, rostering, and break optimization under constraints.

- **[DutyDock](https://github.com/dutydock/dutydock)**  
  Open-source shift planning and rostering software designed for teams with complex scheduling constraints.

- **[SmartCrew and academic airline schedulers](https://github.com/)**  
  AI-powered or rule-based flight crew scheduling systems developed in research and educational contexts.

- **[Aviation operations suites with crew modules](https://github.com/)**  
  Emerging open-source or white-label aviation management projects that include crew assignment, compliance, and scheduling components.

- **[General rostering and constraint solvers](https://github.com/)**  
  Applications of OR-Tools, OptaPlanner, or similar open solvers to crew pairing and roster generation problems.

- **[Maritime workforce and certification trackers](https://github.com/)**  
  Community tools for tracking seafarer certifications, work/rest hours, and basic crew planning (often lighter-weight than commercial MLC systems).

- **[Custom FTL/MLC rule engines](https://github.com/)**  
  Open implementations or rule sets that encode flight-time limitations or maritime labour convention constraints for validation.

- **[Integration of open HR cores with domain rules](https://github.com/)**  
  Extensions of open-source HR or ERP systems (Odoo, etc.) adapted for crew qualifications and rotation planning.

### Additional Strong Open-Source Options
- Google OR-Tools, OptaPlanner, and other constraint-programming libraries applied to pairing and rostering.
- Time-series and calendar libraries for duty/rest visualization.
- Self-hosted document and certificate management for crew qualifications.
- Mobile-friendly PWA or simple portals for crew self-service roster views.
- Research codes for fatigue risk and disruption recovery modeling.

**Frameworks for building custom systems**: Use constraint solvers (**OR-Tools CP-SAT**, **pyworkforce**, or similar) for pairing and roster generation, encode regulatory rules (EASA/FAA FTL or MLC 2006) as hard/soft constraints, store crew master data and qualifications in a secure database, expose self-service views for crew, and integrate with flight/voyage schedules. Open BI tools can provide utilization and compliance dashboards. Local LLMs can assist with disruption explanations and rule interpretation support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Crew management is safety-critical and heavily regulated (aviation FTL, maritime MLC/STCW, etc.). Open-source components are valuable for research, prototyping, and non-critical support functions but do not replace certified commercial systems, airline/maritime operational approvals, or formal compliance processes.
- Any system handling crew data must meet strict security, audit, and data-protection requirements applicable to the operator’s jurisdiction and regulator.

---
**Made for airline and maritime operations teams, crew planners, and technologists exploring open approaches to workforce scheduling.**
Let's make crew management more transparent, optimizable, and collaboratively improved where regulation allows.
