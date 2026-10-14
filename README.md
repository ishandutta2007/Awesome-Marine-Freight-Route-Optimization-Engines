# Awesome-Marine-Freight-Route-Optimization-Engines

## Top Marine Freight Route Optimization Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Weather Routing, Fuel Consumption Optimization & Voyage Analytics*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Marine Freight Route Optimization**. These tools help ship operators, charterers, and maritime analysts optimize vessel routes based on weather conditions, ocean currents, and fuel consumption — reducing costs, emissions, and voyage time for commercial shipping.



**Examples** include Sofar Ocean, Bearing AI, Spire Global, Nautilus Labs, ZeroNorth, Windward, Portcast, MarineTraffic, Shipfix, and Veson Nautical (the category leaders).



**Open-source emphasis**: This section is expanded with every major active project for self-hosting, custom routing algorithms, and transparent weather data integration — ideal for maritime engineers prioritizing data sovereignty, developers building routing pipelines, and smaller operators avoiding enterprise per-vessel pricing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Sofar Ocean](https://www.sofarocean.com/)**  

  Ocean intelligence platform with Wayfinder routing, Spire weather forecasts, and Spotter buoy data for fuel-efficient voyage optimization.



- **[Bearing AI](https://www.bearing.ai/)**  

  AI-powered maritime optimization platform for fleet routing, emissions reduction, and voyage performance analytics.



- **[Spire Global](https://spire.com/)**  

  Maritime intelligence platform with AIS vessel tracking, weather data, and route optimization services.



- **[Nautilus Labs](https://nautiluslabs.com/)**  

  AI-powered vessel performance optimization and decarbonization platform with route optimization and fuel efficiency analytics.



- **[ZeroNorth](https://zeronorth.com/)**  

  Digital shipping platform with voyage optimization, fuel efficiency, and emissions reduction tools.



- **[Windward](https://windward.ai/)**  

  Maritime AI platform with vessel tracking, risk analytics, and route intelligence.



- **[Portcast](https://www.portcast.io/)**  

  Predictive supply chain visibility platform with port congestion and maritime route analytics.



- **[MarineTraffic](https://www.marinetraffic.com/)**  

  Global AIS vessel tracking and maritime intelligence platform with route and port analytics.



- **[Shipfix](https://www.shipfix.com/)**  

  Maritime and commodity intelligence platform with voyage analytics and cargo matching.



- **[Veson Nautical](https://www.veson.com/)**  

  Commercial maritime software with voyage management, freight trading, and route optimization.



## Open-Source GitHub Projects



- **[WeatherRoutingTool (52North)](https://github.com/52North/WeatherRoutingTool)**  

  **Open-source ship weather routing tool performing route optimization based on fuel consumption in different weather conditions.** Actively maintained (48 GitHub stars), with documentation at 52north.github.io/WeatherRoutingTool . The WRT-sandbox provides an evaluation environment .



- **[WindMar](https://github.com/windmar-nav)**  

  **Open-source maritime route optimization platform for commercial shipping** with weather routing, voyage planning, and fuel efficiency analysis. Apache 2.0 licensed . Features A* and Dijkstra optimizers, Copernicus weather pipeline, and Holtrop-Mennen vessel modeling . Core platform is React + FastAPI; standalone Docker distribution available for local evaluation .



- **[SIMROUTE](https://marine.copernicus.eu/)**  

  **Comprehensive open-source ship weather routing system using Copernicus Marine products.** Powered by Universitat Politecnica de Catalunya (UPC-BarcelonaTech) . Provides optimized route and minimum distance route together with modules for ship emission and safety monitoring . Uses A* algorithm with Copernicus Marine wave predictions . Used for STCW competence-based maritime education and benchmarking .



- **[gweatherrouting](https://github.com/dakk/gweatherrouting)**  

  **Open-source sailing routing and navigation software** written in Python and Gtk4 . Features multi-point sailing weather routing, boat/polar integrated database, Grib1 and Grib2 support with OpenSkiron and NOAA downloaders, GPX import/export, session manager, chart rendering (GeoJSON, GSHHS basemap, KAP, GeoTiff, OpenSeaMap), NMEA instruments support, AIS rendering, and customizable routing calculator .



- **[Weather Routing plugin for OpenCPN](https://github.com/rgleason/weather_routing_pi)**  

  **Weather routing plugin for OpenCPN** with optimal routing subject to weather data constraints and automatic boat polar computation . GPL-3.0 licensed .



- **[bywind](https://github.com/Anvoker/bywind)**  

  **Naval pathfinding with Particle Swarm Optimization over GRIB2 data** . Features wind data from NOAA's GFS S3 bucket, landmass avoidance via signed-distance field, ensemble search for forecast uncertainty robustness, and both GUI (bywind-viz) and CLI (bywind-cli) frontends .



- **[SSRS (Ship Safety and Routeing System)](https://github.com/Hamzawp/SSRS-Ship_Safety_and_Routeing_System)**  

  **Ship routing algorithm to minimize fuel consumption and CO2 emissions** in the Indian Ocean . Uses CMEMS ocean dataset, Dijkstra with cost matrix, and self-improving algorithm based on past ship incidents . Claims potential 48–60% CO2 reduction through route and speed optimization .



- **[cms_routing (jsten07)](https://repos.ecosyste.ms/topics/ship-routing)**  

  **Ship routing algorithms for Just-In-Time and energy-efficient voyages using genetic algorithms.** Two specifications: constant engine power and variable engine power over the route . Python-based.



### Additional Strong Open-Source Options



- **HALEM** — Python package for optimizing shipping routes with hydrodynamic algorithms .

- **libweatherrouting** — Sailing weather routing library .

- **ShipRouteRL** — Ship route planning with reinforcement learning (Q-learning) .

- **WindMar Demo** — Standalone Docker distribution for local evaluation of the WindMar platform .

- **Weather-Routing Benchmark** — Open benchmark dataset for ship weather routing research: 12 routes across all major ocean basins, four seasons, two years, three benchmark hulls (S175 containership, KVLCC2 VLCC tanker, JBC capesize bulk carrier) under ERA5 reanalysis weather .



**Frameworks for building custom systems**: Combine **WeatherRoutingTool** or **SIMROUTE** for A*-based weather routing, **WindMar** for full-stack route optimization with Copernicus data, **gweatherrouting** for sailing-specific routing with GRIB support, and **bywind** for PSO-based naval pathfinding with ensemble forecast robustness to build a complete self-hosted marine route optimization stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Marine route optimization tools must comply with maritime safety regulations (SOLAS, COLREGS), environmental requirements (MARPOL), and port authority rules. **Optimized routes must be validated by qualified navigating officers before execution** — weather forecasts contain uncertainty, and routing algorithms may not account for all navigational hazards.

- Self-hosted open-source solutions require proper weather data access (GRIB downloads, Copernicus API credentials), vessel performance modeling (polar diagrams, Holtrop-Mennen coefficients), and validation against actual voyage data.



---



**Made for maritime engineers, fleet operators, voyage optimization analysts, and developers building marine routing platforms.**  

Let's make marine freight route optimization more open, fuel-efficient, and emissions-conscious.
