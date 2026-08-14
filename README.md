# Awesome-Weather-Intelligence

## Top Weather Intelligence Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Weather APIs, Forecasting, Historical Data, Hyperlocal Intelligence & Climate Insights*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Weather Intelligence**. These systems deliver real-time observations, short- and medium-range forecasts, historical reanalysis, hyperlocal data, severe weather alerts, and specialized datasets (air quality, maritime, energy, agriculture) via APIs and platforms.

**Examples** include Tomorrow.io, The Weather Company API, OpenWeather, Meteomatics, Weatherbit, DTN, Visual Crossing, AccuWeather API, Climacell (legacy/Tomorrow.io roots), and Ambee (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for free/open weather APIs, numerical weather prediction access, AI weather models, and self-hosted forecasting stacks — ideal for developers, researchers, energy traders, logistics teams, and organizations seeking transparent, high-quality weather data without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description & Key Focus | Starting Tier Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Tomorrow.io](https://www.tomorrow.io/)** *(formerly ClimaCell)* | Hyperlocal forecasting, proprietary sensing, AI-driven weather resilience & automated severe alerts for aviation, insurance, logistics. | **$0/mo** (Free plan); Paid API tiers start at **$50/mo** (Hobby/Builder tier) | **Free forever plan**: 500 requests/day (max 25 req/hr, 3 req/sec), 5-day forecast horizon, 24h historical data. |
| **[OpenWeather](https://openweathermap.org/)** | Global weather API with current conditions, hourly/daily forecasts, historical archives, radar maps, and weather alerts. | **$0/mo** (Free tier); One Call API at **$0.0015/call**; Developer subscription at **$40/mo** (Startup tier) / **$180/mo** (Developer tier) | **Free forever plan**: 1,000 calls/day for One Call API 3.0; 60 calls/min (up to 1,000,000 calls/mo) for standard Free Weather API. |
| **[Visual Crossing](https://www.visualcrossing.com/)** | Weather data engine emphasizing historical records (1970+), sub-hourly weather observations, and analytics/BI integrations. | **$0/mo** (Free plan); Pay-as-you-go at **$0.0001/record**; Professional (Pro) plan starts at **$35/mo** | **Free forever plan**: 1,000 records/day (resets daily, commercial use allowed in small projects). |
| **[Weatherbit](https://www.weatherbit.io/)** | High-performance weather API providing forecasts, historical data, air quality (AQI), severe weather alerts, and soil/ag datasets. | **$0/mo** (Free plan); Starter plan starts at **$35/mo** (2,500 calls/day); Business plans from **$160/mo** | **Free forever plan**: 500 calls/day (non-commercial use, current weather & 7-day forecast); 14-day Business trial (1,500 calls/day). |
| **[AccuWeather API](https://developer.accuweather.com/)** | Enterprise-grade forecasting, MinuteCast® minute-by-minute precipitation, severe warnings, and global radar. | Starter tier at **$2/mo** (~15,000 calls/mo); Standard tier at **$25/mo** (225,000 calls/mo) | **14-day free trial**: 500 calls/day (Core Weather API) and 50 calls/day (MinuteCast®). *(Permanent free tier retired)* |
| **[The Weather Company API (IBM)](https://www.ibm.com/products/weather-company-data-packages)** | High-resolution global forecast system (GRAF), severe weather alerts, clean energy & aviation decision support. | Standard production tier starts at **$500/mo** (~1,000,000 API calls/mo); Environmental Intelligence Suite Essentials from **$500/mo** | **30-day free trial**: Trial API key with up to 50,000 calls/day (capped at 100 calls/minute for internal testing/evaluation). |
| **[Meteomatics](https://www.meteomatics.com/)** | High-resolution API combining 100+ global sources, historical data from 1940, 1km downscaling, and aviation/energy models. | Starter API packages / Data Shop downloads start from **~$150/mo**; MetX / Enterprise customized quotes | **Free Basic Weather Account**: 500 queries/day (50 queries/min, 10 parallel queries, 10-day forecast); plus **14-day free trial** for high-res API. |
| **[DTN (ClearAg / Weather API)](https://www.dtn.com/)** | Industry-specialized weather intelligence for agriculture, energy trading, transportation, and marine navigation. | Professional API feeds start from **~$300–$500/mo** via AWS Marketplace & direct packages; Consumer tools from **$9.99/mo** | **30-day trial access**: Available upon consultation/request via ClearAg Viewer & trial API credentials. |
| **[Ambee](https://www.getambee.com/)** | Environmental & weather intelligence API tracking hyperlocal weather, air quality (AQI), pollen counts, fire, and climate risk. | Starter developer packages start from **$29–$49/mo** (or AWS Marketplace pay-as-you-go) | **15-day free trial**: 100 API calls/day (Weather, Air Quality, Pollen); Geocoding free tier up to 3,000 requests/mo. |

## Open-Source GitHub Projects
- **[Open-Meteo](https://github.com/open-meteo/open-meteo)**  
  Free, open-source weather API aggregating 30+ models from national weather services (ECMWF, NOAA, DWD, etc.), historical data from 1940, no API key required for non-commercial use.

- **[Pirate Weather](https://pirateweather.net/)**  
  Modern open-source, developer-centric weather API designed as a Dark Sky alternative, with extensive documentation and GFS/HRRR/NBM data access.

- **[ECMWF AIFS & open AI models](https://www.ecmwf.int/)**  
  Open AI weather forecasting models (AIFS) and tools allowing users to run state-of-the-art AI forecasts using ECMWF open data.

- **[GraphCast / WeatherNext / GenCast (Google DeepMind)](https://github.com/google-deepmind/weathernext)**  
  Open implementations and related code for advanced AI weather models including GraphCast and subsequent WeatherNext generations.

- **[NVIDIA Earth-2](https://github.com/NVIDIA/earth2studio)**  
  Fully open accelerated family of AI weather and climate models, libraries, and frameworks for medium-range forecasting and data assimilation.

- **[ai-models (ECMWF community)](https://github.com/ecmwf-lab/ai-models)**  
  Tools and plugins to run leading AI weather models (Pangu-Weather, FourCastNet, GraphCast, FuXi, Aurora, etc.) on open data.

- **[NOAA / NCEP open model data pipelines](https://github.com/)**  
  Community downloaders, processors, and catalogs for GFS, GEFS, HRRR, NAM, and other publicly available NOAA numerical weather prediction outputs.

- **[awesome-weather-models](https://github.com/rebase-energy/awesome-weather-models)**  
  Curated catalog of AI-based weather forecasting models with details on openness, weights, and operational data availability.

- **[Weather data downloaders & processors](https://github.com/DWesl/weather-data-downloader)**  
  Open tools for retrieving and handling NWP model output from NOAA and ECMWF Thredds/NOMADS sources.

- **[Terminal & CLI weather tools](https://github.com/)**  
  Collection of open-source terminal clients (wttr.in, wego, ansiweather, etc.) that consume free weather APIs for quick forecasts.

### Additional Strong Open-Source Options
- **ERA5 / WeatherBench2** reanalysis datasets and Zarr-based access patterns on public clouds.
- Community **GFS/ICON/IFS** post-processing and bias-correction pipelines.
- Open radar and nowcasting projects (MRMS, etc.).
- Self-hosted forecast servers and map visualizations built on Open-Meteo or direct model data.
- Academic and research repositories implementing ensemble post-processing, downscaling, and verification metrics.

**Frameworks for building custom systems**: Use **Open-Meteo** or **Pirate Weather** as the primary free API layer, ingest raw **NOAA/ECMWF** model data for custom post-processing, run open AI models (**GraphCast**, **AIFS**, **Earth-2**) via available inference stacks, store results in Zarr/NetCDF, and serve via FastAPI or similar. Combine with local LLMs for natural-language weather briefings and alert generation.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Weather data and forecasts have inherent uncertainty; always validate critical decisions against official meteorological services and appropriate risk frameworks.
- Self-hosted open-source solutions and AI models require computational resources, proper data licensing attribution, and ongoing validation against observations.

---
**Made for developers, data scientists, energy & logistics teams, researchers, and organizations that need reliable, open weather intelligence.**
Let's make weather data more accessible, transparent, and actionable.
