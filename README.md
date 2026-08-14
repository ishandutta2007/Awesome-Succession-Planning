# 🚚 Awesome Route Optimization Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed1c88387b76e60417255b632b02/media/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)

> 📍 A curated directory of top **Route Optimization Platforms**, Vehicle Routing Problem (VRP/CVRP/VRPTW) solvers, last-mile delivery dispatchers, multi-depot planning engines, distance matrix services, and self-hosted logistics stacks.

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Route Optimization Platform Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Route-Optimization-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Route-Optimization-Platform?style=flat-square&color=gold" alt="GitHub Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Route-Optimization-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Route-Optimization-Platform?style=flat-square" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Route-Optimization-Platform/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Route-Optimization-Platform?style=flat-square&color=blue" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🧭 Table of Contents

- [🏢 Commercial & SaaS Hosted Platforms](#-commercial--saas-hosted-platforms)
- [⚡ Open-Source GitHub Projects](#-open-source-github-projects)
- [🧩 Routing Toolkits & Building Blocks](#-routing-toolkits--building-blocks)
- [🎯 Quick Start Recommendations](#-quick-start-recommendations)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🏢 Commercial & SaaS Hosted Platforms

Below is a curated comparison of leading commercial route optimization, fleet dispatch, and last-mile logistics orchestration platforms. *Sorted by Company Scale / Valuation / Revenue (Descending).*

| Platform 🚀 | Company Scale & Valuation 📊 | Overview & Key Strengths 📝 | Starting Tier Pricing 💰 | Free Tier & Free Trial Limits 🎁 |
| :--- | :--- | :--- | :--- | :--- |
| **[Bringg](https://www.bringg.com/)** | **~$1.0B Valuation (Unicorn)** / ~$190M+ Total Funding / ~$40.8M ARR | Enterprise-grade delivery and fulfillment orchestration platform supporting mixed internal and 3PL fleets, dynamic route optimization, and omnichannel last-mile operations. | Enterprise contracts start at **~$10,000 – $20,000 / year** (~$833 – $1,666/month); modular Delivery Hub tiers | **30-day free trial** for the Delivery Hub module; guided pilot evaluations for the core enterprise platform (no permanent free tier). |
| **[FarEye](https://fareye.com/)** | **~$150M+ Revenue** / ~$152M Total Funding / ~$80M–$100M Valuation | Global enterprise delivery management platform offering embedded multi-stop route optimization, multi-carrier management, real-time tracking, and customer experience workflows. | Enterprise tier starts at **~$50,000 / year** (~$4,166/month base + ~$0.50/transaction via AWS Marketplace / contracts) | **14-day guided proof-of-concept / evaluation trial** upon demo consultation with solutions engineering (no public self-serve free plan). |
| **[Circuit](https://getcircuit.com/)** *(Spoke)* | **~$43.6M ARR** / Bootstrapped & Capital Efficient Growth | Intuitive, high-speed route planning and stop sequencing tool for solo delivery couriers and fleets (rebranded to Spoke Dispatch for teams). | Solo: **$20 / month**; Teams (Spoke Dispatch): **$125 / month** (includes 1,000 stops/month, $0.04/stop overage) | Solo: **Free-forever plan** up to **10 stops per route** (unlimited routes); Teams: **14-day free trial** (no credit card required). |
| **[Onfleet](https://onfleet.com/)** | **~$35M ARR** / ~$45M Total Funding (Series B) / ~$100M+ Valuation | Premium last-mile delivery management platform featuring automated route optimization, real-time driver dispatch, proof of delivery, and branded customer live tracking. | **$550 / month** (billed annually) or $619/mo (monthly) for Launch tier (includes up to 2,500 delivery tasks/month) | **14-day free trial** with full feature access and up to 2,500 tasks (no credit card required). |
| **[NextBillion.ai](https://nextbillion.ai/)** | **~$34.25M Total Funding** (Series B) / ~$15M+ ARR *(Velocitor)* | Developer-centric mapping and routing platform offering scalable Route Optimization APIs, distance matrices, large fleet solvers, and turn-by-turn navigation SDKs. | Starter tier starts at **$499 / month** (covers up to 5,000 tasks/orders; driver app add-on at $19/driver/month) | **14-day free evaluation trial** with solutions engineering support; includes free online web calculation and matrix tools. |
| **[BeatRoute](https://www.beatroute.io/)** | **~$29M Valuation** / ~$9.7M Annual Revenue / $180K Seed | AI-powered field sales and distribution enablement platform with intelligent territory routing, beat planning, and customer visit scheduling. | Starter Pack starts at **$8.50 / user / month** (or ₹349–₹599/user/month on annual agreements) | **14-day guided trial / pilot** via Startup Program (for growing fleets with <50 sales reps / <500 customers; no self-serve free plan). |
| **[OptimoRoute](https://optimoroute.com/)** | **~$7.1M ARR** / ~$10.7M Total Funding | Highly configurable multi-stop route optimization platform supporting time windows, vehicle load capacities, multi-day scheduling, skills-based matching, and live order injection. | **$35.10 / driver / month** (billed annually) or $39/mo (monthly) for Lite tier; Pro at $44.10/mo | **30-day free trial** with full feature access and no credit card required (no permanent free tier). |
| **[Routific](https://routific.com/)** | **~$5.4M ARR** / Seed & Bootstrapped Growth | User-friendly route optimization and dispatch solution engineered for local delivery businesses, featuring proprietary sequencing algorithms, driver mobile apps, and automated ETA alerts. | **$150 / month** (covers 101–1,000 orders/month; $0.15/order overage) | **Free-forever plan** for up to **100 orders/month** (unlimited drivers & dispatchers); plus **7-day free trial** of paid plans. |
| **[Track-POD](https://www.track-pod.com/)** | **~$7.3M Valuation** / ~$2.4M ARR | Paperless delivery management and route optimization solution offering automated route planning, live GPS tracking, electronic proof of delivery (ePOD), and vehicle check. | **$35 / driver / month** (billed annually) or $39/mo (monthly) for Standard; or from **$285 / month** (order-based tier) | **7-day free trial** (up to 14 days upon request) supporting up to 2 drivers and core optimization (no credit card required). |
| **[MyRouteOnline](https://www.myrouteonline.com/)** | **~$1.5M–$2.0M ARR** / Unfunded & Bootstrapped since 2009 | Straightforward, accessible multi-stop route planner for small to mid-sized fleets needing rapid batch address optimization and map-based dispatch export. | **$19 / month** (subscription includes 50 address credits/month) or Pay-As-You-Go from $24 (20 credits) | **Free-forever tier** up to **6 addresses per route**; free trial with credit reload available without credit card. |

---

## ⚡ Open-Source GitHub Projects

*Curated open-source solvers, high-performance routing engines, distance matrix generators, and vehicle routing libraries. Sorted by GitHub Stars (Descending).*

- **[Google OR-Tools](https://github.com/google/or-tools)** [![Stars](https://img.shields.io/github/stars/google/or-tools?style=social&color=white)](https://github.com/google/or-tools/stargazers)  
  🧠 Google's comprehensive, award-winning mathematical optimization suite featuring world-class Vehicle Routing Problem (VRP) solvers with constraint programming, capacity constraints, time windows, and multi-depot support.

- **[GraphHopper](https://github.com/graphhopper/graphhopper)** [![Stars](https://img.shields.io/github/stars/graphhopper/graphhopper?style=social&color=white)](https://github.com/graphhopper/graphhopper/stargazers)  
  🚀 Fast, memory-efficient Java road routing engine based on OpenStreetMap data, providing turn-by-turn navigation, isochrones, matrix calculations, and embedded vehicle routing capabilities.

- **[Valhalla](https://github.com/valhalla/valhalla)** [![Stars](https://img.shields.io/github/stars/valhalla/valhalla?style=social&color=white)](https://github.com/valhalla/valhalla/stargazers)  
  🌐 Open-source, tiled routing engine and transit engine written in C++ that supports multi-modal routing, dynamic costing, time-distance matrices, and map matching.

- **[OSRM (Open Source Routing Machine)](https://github.com/Project-OSRM/osrm-backend)** [![Stars](https://img.shields.io/github/stars/Project-OSRM/osrm-backend?style=social&color=white)](https://github.com/Project-OSRM/osrm-backend/stargazers)  
  ⚡ Ultra-fast C++ routing engine using Contraction Hierarchies and Multi-Level Dijkstra on OpenStreetMap data, calculating distance matrices and shortest paths in microseconds.

- **[VROOM](https://github.com/VROOM-Project/vroom)** [![Stars](https://img.shields.io/github/stars/VROOM-Project/vroom)?style=social&color=white](https://github.com/VROOM-Project/vroom/stargazers)  
  🏎️ High-performance open-source Vehicle Routing Open-source Optimization Machine in C++ that solves complex real-world VRP variants (CVRP, VRPTW, PDPTW, multi-depot) in milliseconds.

- **[OpenRouteService](https://github.com/GIScience/openrouteservice)** [![Stars](https://img.shields.io/github/stars/GIScience/openrouteservice?style=social&color=white)](https://github.com/GIScience/openrouteservice/stargazers)  
  🗺️ Spatial routing API service built on OpenStreetMap with isochrones, time-distance matrices, elevation data, and integrated VROOM optimization endpoints.

- **[pgRouting](https://github.com/pgRouting/pgrouting)** [![Stars](https://img.shields.io/github/stars/pgRouting/pgrouting?style=social&color=white)](https://github.com/pgRouting/pgrouting/stargazers)  
  🐘 Geospatial routing extension for PostgreSQL / PostGIS providing Dijkstra, A*, Traveling Salesperson (TSP), and network analysis directly within SQL queries.

- **[jsprit](https://github.com/jsprit/jsprit)** [![Stars](https://img.shields.io/github/stars/jsprit/jsprit?style=social&color=white)](https://github.com/jsprit/jsprit/stargazers)  
  ☕ Lightweight, flexible Java library for solving rich Traveling Salesman Problems (TSP) and Vehicle Routing Problems (VRP) with metaheuristic optimization.

- **[Leaflet Routing Machine](https://github.com/perliedman/leaflet-routing-machine)** [![Stars](https://img.shields.io/github/stars/perliedman/leaflet-routing-machine?style=social&color=white)](https://github.com/perliedman/leaflet-routing-machine/stargazers)  
  📍 Interactive Leaflet control for building browser-based route planning maps, waypoint dragging, and turn-by-turn directions using OSRM, GraphHopper, or Valhalla.

- **[Timefold Solver](https://github.com/TimefoldAI/timefold-solver)** [![Stars](https://img.shields.io/github/stars/TimefoldAI/timefold-solver?style=social&color=white)](https://github.com/TimefoldAI/timefold-solver/stargazers)  
  ⏱️ Leading open-source AI constraint satisfaction and planning solver (fork of OptaPlanner) in Java/Python for complex vehicle routing, shift rostering, and resource dispatch.

- **[PyVRP](https://github.com/PyVRP/PyVRP)** [![Stars](https://img.shields.io/github/stars/PyVRP/PyVRP?style=social&color=white)](https://github.com/PyVRP/PyVRP/stargazers)  
  🐍 State-of-the-art Hybrid Genetic Search VRP solver for Python with C++ acceleration, winning multiple international VRP competitions on large-scale benchmarks.

- **[vrp (Rust Solver)](https://github.com/reinterpretcat/vrp)** [![Stars](https://img.shields.io/github/stars/reinterpretcat/vrp?style=social&color=white)](https://github.com/reinterpretcat/vrp/stargazers)  
  🦀 High-performance Vehicle Routing Problem solver written in pure Rust with support for multiple job types, capacity limits, time windows, and reload stops.

- **[RoutingKit](https://github.com/RoutingKit/RoutingKit)** [![Stars](https://img.shields.io/github/stars/RoutingKit/RoutingKit?style=social&color=white)](https://github.com/RoutingKit/RoutingKit/stargazers)  
  ⚡ Fast C++ routing library focused on clean graph algorithms and custom contraction hierarchies for calculating travel times across large road networks.

- **[pyvroom](https://github.com/VROOM-Project/pyvroom)** [![Stars](https://img.shields.io/github/stars/VROOM-Project/pyvroom?style=social&color=white)](https://github.com/VROOM-Project/pyvroom/stargazers)  
  📦 Python bindings for the VROOM optimization machine, providing frictionless integration into Python data science and logistics pipelines.

---

## 🧩 Routing Toolkits & Building Blocks

| Category 📂 | Description 📝 | Key Technologies & Repositories 🎯 |
| :--- | :--- | :--- |
| **High-Speed Routing Engines** | Microsecond shortest path calculation and time-distance matrix generators. | **OSRM**, **Valhalla**, **GraphHopper**, **RoutingKit** |
| **Metaheuristic & Exact Solvers** | Algorithms for CVRP, VRPTW, pickup-and-delivery, and multi-depot planning. | **Google OR-Tools**, **VROOM**, **PyVRP**, **Timefold Solver**, **jsprit** |
| **Spatial Databases & GIS** | Database-native graph topology, isochrones, and spatial route queries. | **PostGIS**, **pgRouting**, **H3 Spatial Index**, **GeoPandas** |
| **Interactive Map Frontends** | Web map visualization, draggable waypoints, and fleet telemetry dashboards. | **Leaflet Routing Machine**, **MapLibre GL**, **Deck.gl**, **OpenLayers** |
| **GPU-Accelerated Routing** | Massively parallel heuristic solvers and tensorized constraint optimization. | **NVIDIA cuOpt**, **RAPIDS cuGraph**, **CUDA VRP Acceleration** |

---

## 🎯 Quick Start Recommendations

| Use Case 🎯 | Recommended Starting Point 🚀 |
| :--- | :--- |
| **Best Free & Open-Source VRP Solver (Production-Ready)** | **[VROOM](https://github.com/VROOM-Project/vroom)** + **[OSRM](https://github.com/Project-OSRM/osrm-backend)** |
| **Best Python Solver for Complex Constraints** | **[PyVRP](https://github.com/PyVRP/PyVRP)** or **[Google OR-Tools](https://github.com/google/or-tools)** |
| **Best Java Enterprise Optimization Stack** | **[Timefold Solver](https://github.com/TimefoldAI/timefold-solver)** or **[GraphHopper](https://github.com/graphhopper/graphhopper)** |
| **Best Enterprise Full-Scale Orchestration Platform** | **[Bringg](https://www.bringg.com/)** or **[FarEye](https://fareye.com/)** |
| **Best Developer-First Routing & Matrix API** | **[NextBillion.ai](https://nextbillion.ai/)** or **[OpenRouteService](https://github.com/GIScience/openrouteservice)** |
| **Best Last-Mile Dispatch & Proof-of-Delivery SaaS** | **[Onfleet](https://onfleet.com/)** or **[Track-POD](https://www.track-pod.com/)** |
| **Best Mid-Market & SME Delivery Planning** | **[OptimoRoute](https://optimoroute.com/)** or **[Routific](https://routific.com/)** |
| **Best Solo Courier & Driver Mobile App** | **[Circuit / Spoke](https://getcircuit.com/)** |
| **Best Spatial SQL Routing in Database** | **[pgRouting](https://github.com/pgRouting/pgrouting)** (PostgreSQL) |

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Route-Optimization-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Route-Optimization-Platform&type=date&legend=top-left)

---

## 🤝 How to Contribute

Contributions, updates, and new platform additions are warmly welcome!
1. Fork this repository.
2. Add or update entries in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Route-Optimization-Platform/README.md) following the existing table and badge conventions.
3. Ensure all links are active, descriptions are factual, and categories are properly sorted.
4. Submit a Pull Request with a clear description of changes.

⭐ Star the repository if you find it helpful!

---

## ⚠️ Disclaimer

- This repository is a **community-curated index** for informational and educational purposes — not an endorsement.
- Route optimization performance depends on accurate speed profiles, realistic traffic models, and correct constraint definitions; validate solutions against physical fleet operations.
- Self-hosted open-source solvers require adequate compute resources and continuous matrix updates for large fleet deployments.

---

**Made with ❤️ for logistics teams, delivery operators, fleet managers, and developers building the future of intelligent route optimization.**

