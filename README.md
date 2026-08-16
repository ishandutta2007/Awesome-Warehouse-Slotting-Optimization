# Awesome-Warehouse-Slotting-Optimization

## Top Warehouse Slotting Optimization Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on SKU-to-Location Assignment, Velocity-Based Slotting, Pick-Path Efficiency, Cube Utilization, Dynamic Re-Slotting & Warehouse Labor Productivity*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Warehouse Slotting Optimization**. These tools determine the optimal storage locations for SKUs based on demand velocity, product affinity, size/weight constraints, pick-path travel, and replenishment patterns to reduce picker travel time, improve throughput, and maximize space utilization.

**Examples** include Lucas Systems, Hopstack, Easy Metrics, Blue Yonder Warehouse Slotting, Körber Slotting, Manhattan Slotting, Logiwa AI Slotting, Made4net Slotting, Extensiv WMS Slotting, and Infios Slotting (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for warehouse slotting algorithms, layout optimization, open WMS/WCS components, and operations-research tools for SKU placement — ideal for warehouse operators, industrial engineers, and developers seeking transparent, customizable slotting logic.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Lucas Systems (Dynamic Slotting)](https://www.lucasware.com/)**  
  AI-powered dynamic slotting that continuously adjusts SKU locations using real-time data and voice-picking integration to minimize travel and improve productivity.

- **[Hopstack](https://www.hopstack.io/)**  
  Modern warehouse execution and optimization platform that includes intelligent slotting and inventory placement capabilities for fulfillment centers.

- **[Easy Metrics](https://www.easymetrics.com/)**  
  Labor and warehouse performance platform that supports engineered standards and insights useful for slotting and productivity analysis.

- **[Blue Yonder Warehouse Slotting](https://blueyonder.com/)**  
  Advanced slotting module within Blue Yonder WMS that uses machine learning for predictive placement based on demand, velocity, and seasonality.

- **[Körber / Infios Slotting](https://www.koerber-supplychain.com/)**  
  Slotting optimization capabilities integrated with Körber (now Infios) warehouse management solutions for ABC classification, family grouping, and forward/reserve balancing.

- **[Manhattan Slotting / Active WM](https://www.manh.com/)**  
  Built-in AI-driven slotting optimization within Manhattan Active Warehouse Management that unifies location assignment with picking workflows.

- **[Logiwa AI Slotting](https://www.logiwa.com/)**  
  Cloud WMS with AI-assisted slotting features designed for high-velocity e-commerce and omnichannel fulfillment operations.

- **[Made4net Slotting](https://www.made4net.com/)**  
  Warehouse management and optimization tools that include slotting functionality for efficient product placement and labor reduction.

- **[Extensiv WMS Slotting](https://www.extensiv.com/)**  
  Cloud WMS platform offering slotting and inventory optimization capabilities for 3PLs and multi-client warehouses.

- **[Infios Slotting](https://www.infios.com/)**  
  Slotting and warehouse optimization solutions (evolving from Körber heritage) focused on complex distribution environments.

## Open-Source GitHub Projects
- **[Warehouse Slotting Optimizer (De Koster methodology)](https://github.com/virbahu/warehouse-slotting-optimizer)**  
  Open-source Python optimizer that assigns SKUs to slots using demand velocity, cube utilization, and pick-path efficiency to minimize travel time.

- **[Warehouse Slotting ML](https://github.com/virbahu/warehouse-slotting-ml)**  
  ML-driven open-source slotting optimization that leverages order frequency patterns and academic methodology for enterprise-scale SKU placement.

- **[openWCS](https://openwcs.ai/)**  
  Open-source Warehouse Control System with configurable slotting and replenishment rules for ASRS, AMR, AutoStore, and conventional layouts.

- **[GABAK / Warehouse Layout Design System](https://github.com/)**  
  Open-source computational system for designing order-picking warehouse layouts, including product allocation (slotting) and picker routing optimization.

- **[Slotting-Tool and planogram generators](https://github.com/)**  
  Community projects that consume warehouse data to calculate and visualize slotting plans, heatmaps, and productivity impacts.

- **[WMS optimization with ACO / metaheuristics](https://github.com/)**  
  Research and practical tools applying Ant Colony Optimization, genetic algorithms, or other OR methods to warehouse location and routing problems.

- **[Open WMS / warehouse-operations platforms](https://github.com/)**  
  Event-driven or modular open-source warehouse management components that include location directives and pick-path logic adaptable to slotting.

- **[Inventory & location management cores](https://github.com/)**  
  Self-hosted open-source inventory systems that track bins, locations, and movements and can serve as foundations for custom slotting rules.

- **[OR-Tools / PyVRP applications to warehousing](https://github.com/)**  
  Uses of open constraint solvers and vehicle-routing libraries adapted to picker routing and multi-objective slotting problems.

- **[Academic and research slotting codes](https://github.com/)**  
  Implementations of classic velocity-based, class-based, and correlated slotting algorithms from operations-research literature.

### Additional Strong Open-Source Options
- Open-source WMS projects (Odoo Inventory, ERPNext, custom forks) that support location hierarchies and can host custom slotting logic.
- Python libraries for ABC analysis, demand forecasting, and affinity clustering that feed into slotting models.
- Simulation frameworks (SimPy, etc.) for evaluating slotting scenarios before physical moves.
- Visualization tools (Plotly, Matplotlib, or GIS layers) for heatmaps of pick frequency and travel distance.
- Integration of open BI (Metabase, Superset) for monitoring post-slotting KPIs.

**Frameworks for building custom systems**: Start with a velocity- or ML-based slotting engine (**warehouse-slotting-optimizer** or **warehouse-slotting-ml**), feed it historical order and SKU master data, constrain placements by size/weight/hazard rules, evaluate resulting pick paths with open routing solvers, and push recommended moves into an open or commercial WMS via API. Use **openWCS** for real-time execution in automated environments. Combine with open dashboards for continuous monitoring and re-slotting triggers.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Warehouse slotting directly affects safety, labor costs, and service levels. Open-source algorithms are excellent for analysis, prototyping, and custom optimization but typically require integration with a production WMS, validation against real constraints (weight, temperature, hazmat, equipment reach), and controlled change management before physical re-slotting.
- Always pilot recommendations in a limited zone and measure travel-time and productivity impact before full-warehouse rollout.

---
**Made for warehouse engineers, supply-chain technologists, and operations teams seeking better product placement.**
Let's make warehouse slotting more open, data-driven, and continuously optimizable.
