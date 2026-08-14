# 🌤️ Awesome Weather Intelligence [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed1c88387b76e60417255b632b02/media/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)

> A curated directory of top **Weather Intelligence** platforms, AI-driven meteorological forecasting engines, numerical weather prediction (NWP) pipelines, hyperlocal weather APIs, global climate reanalysis archives, and radar analytics systems.

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Weather Intelligence Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Weather-Intelligence/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Weather-Intelligence?style=flat-square&color=gold" alt="GitHub Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Weather-Intelligence/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Weather-Intelligence?style=flat-square" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Weather-Intelligence/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Weather-Intelligence?style=flat-square&color=blue" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 📖 Table of Contents
- [🌐 SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source Weather & AI Forecasting Projects](#-open-source-weather--ai-forecasting-projects)
- [🧩 Meteorological Toolkits & Building Blocks](#-meteorological-toolkits--building-blocks)
- [⚡ Quick Start Recommendations](#-quick-start-recommendations)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🌐 SaaS / Hosted Platforms

Below is a comparative breakdown of commercial weather intelligence, enterprise forecasting, and environmental data APIs. *Sorted by Company Scale / Valuation / Revenue (Descending).*

| Platform 🌐 | Scale / Valuation / Revenue 💼 | Description & Key Focus 🎯 | Starting Tier Pricing 💳 | Free Tier / Free Trial Limits 🎁 |
| :--- | :--- | :--- | :--- | :--- |
| **[The Weather Company API (IBM / Francisco Partners)](https://www.ibm.com/products/weather-company-data-packages)** | **~$2.0B+ Valuation** / ~$500M+ Revenue *(Global Enterprise Standard)* | High-resolution global forecast system (GRAF), severe weather alerts, clean energy & aviation decision support. | Standard production tier starts at **$500/mo** (~1,000,000 API calls/mo); Environmental Intelligence Suite from **$500/mo** | **30-day free trial**: Trial API key with up to 50,000 calls/day (capped at 100 calls/minute for internal testing/evaluation). |
| **[Tomorrow.io](https://www.tomorrow.io/)** *(formerly ClimaCell)* | **~$700M+ Valuation** / $250M+ Total Funding / ~$50M+ ARR | Hyperlocal forecasting, proprietary radar satellites, AI-driven weather resilience & automated severe alerts for aviation, insurance, and logistics. | **$0/mo** (Free plan); Paid API tiers start at **$50/mo** (Hobby/Builder tier) | **Free forever plan**: 500 requests/day (max 25 req/hr, 3 req/sec), 5-day forecast horizon, 24h historical data. |
| **[DTN (ClearAg / Weather API)](https://www.dtn.com/)** | **~$300M+ Annual Revenue** *(Parent: TBG AG)* | Industry-specialized weather intelligence for agriculture, energy trading, transportation, and marine navigation. | Professional API feeds start from **~$300–$500/mo** via AWS Marketplace & direct packages; Consumer tools from **$9.99/mo** | **30-day trial access**: Available upon consultation/request via ClearAg Viewer & trial API credentials. |
| **[AccuWeather API](https://developer.accuweather.com/)** | **~$150M+ Annual Revenue** *(Established Global Leader)* | Enterprise-grade forecasting, MinuteCast® minute-by-minute precipitation, severe warnings, and global radar. | Starter tier at **$2/mo** (~15,000 calls/mo); Standard tier at **$25/mo** (225,000 calls/mo) | **14-day free trial**: 500 calls/day (Core Weather API) and 50 calls/day (MinuteCast®). *(Permanent free tier retired)* |
| **[OpenWeather](https://openweathermap.org/)** | **~$30M+ Annual Revenue** / 5M+ Global Developers | Global weather API with current conditions, hourly/daily forecasts, historical archives, radar maps, and weather alerts. | **$0/mo** (Free tier); One Call API at **$0.0015/call**; Developer subscription at **$40/mo** (Startup tier) / **$180/mo** (Developer tier) | **Free forever plan**: 1,000 calls/day for One Call API 3.0; 60 calls/min (up to 1,000,000 calls/mo) for standard Free Weather API. |
| **[Meteomatics](https://www.meteomatics.com/)** | **~$60M+ Valuation** / ~$15M+ Revenue *(Lockheed Martin Backed)* | High-resolution API combining 100+ global sources, historical data from 1940, 1km downscaling, and aviation/energy models. | Starter API packages / Data Shop downloads start from **~$150/mo**; MetX / Enterprise customized quotes | **Free Basic Weather Account**: 500 queries/day (50 queries/min, 10 parallel queries, 10-day forecast); plus **14-day free trial** for high-res API. |
| **[Visual Crossing](https://www.visualcrossing.com/)** | **~$10M+ Annual Revenue** *(Bootstrapped & Profitable)* | Weather data engine emphasizing historical records (1970+), sub-hourly weather observations, and analytics/BI integrations. | **$0/mo** (Free plan); Pay-as-you-go at **$0.0001/record**; Professional (Pro) plan starts at **$35/mo** | **Free forever plan**: 1,000 records/day (resets daily, commercial use allowed in small projects). |
| **[Ambee](https://www.getambee.com/)** | **~$25M Valuation** / ~$5M ARR *(Techstars Backed)* | Environmental & weather intelligence API tracking hyperlocal weather, air quality (AQI), pollen counts, fire, and climate risk. | Starter developer packages start from **$29–$49/mo** (or AWS Marketplace pay-as-you-go) | **15-day free trial**: 100 API calls/day (Weather, Air Quality, Pollen); Geocoding free tier up to 3,000 requests/mo. |
| **[Weatherbit](https://www.weatherbit.io/)** | **~$3M–$5M Annual Revenue** *(High-Uptime Bootstrapped)* | High-performance weather API providing forecasts, historical data, air quality (AQI), severe weather alerts, and soil/ag datasets. | **$0/mo** (Free plan); Starter plan starts at **$35/mo** (2,500 calls/day); Business plans from **$160/mo** | **Free forever plan**: 500 calls/day (non-commercial use, current weather & 7-day forecast); 14-day Business trial (1,500 calls/day). |

---

## 💻 Open-Source Weather & AI Forecasting Projects

*Curated open-source repositories for weather APIs, deep learning atmospheric models, terminal dashboards, and numerical weather prediction pipelines. Sorted by GitHub Stars (Descending).*

- **[wttr.in](https://github.com/chubin/wttr.in)** [![Stars](https://img.shields.io/github/stars/chubin/wttr.in?style=social&color=white)](https://github.com/chubin/wttr.in/stargazers)  
  🌦️ The famous console-oriented weather forecast service that supports various representation methods like terminal-oriented ANSI sequences for console HTTP clients (`curl wttr.in`), HTML, and PNG.

- **[Breezy Weather](https://github.com/breezy-weather/breezy-weather)** [![Stars](https://img.shields.io/github/stars/breezy-weather/breezy-weather?style=social&color=white)](https://github.com/breezy-weather/breezy-weather/stargazers)  
  📱 Modern, feature-packed, privacy-first open-source Android weather application that connects to 50+ weather data sources and open meteorological APIs.

- **[wego](https://github.com/schachmat/wego)** [![Stars](https://img.shields.io/github/stars/schachmat/wego?style=social&color=white)](https://github.com/schachmat/wego/stargazers)  
  💻 Weather client for the terminal written in Go, featuring beautiful 256-color ASCII art representations of current weather conditions and multi-day forecasts.

- **[GraphCast (Google DeepMind)](https://github.com/google-deepmind/graphcast)** [![Stars](https://img.shields.io/github/stars/google-deepmind/graphcast?style=social&color=white)](https://github.com/google-deepmind/graphcast/stargazers)  
  🧠 State-of-the-art machine learning weather forecasting model based on Graph Neural Networks (GNNs) that predicts 10-day global atmospheric variables in under one minute at 0.25° resolution.

- **[Open-Meteo](https://github.com/open-meteo/open-meteo)** [![Stars](https://img.shields.io/github/stars/open-meteo/open-meteo?style=social&color=white)](https://github.com/open-meteo/open-meteo/stargazers)  
  ⚡ Free, high-performance open-source weather API engine aggregating 30+ national weather service NWP models (ECMWF, NOAA GFS, DWD ICON, MeteoFrance) with historical data from 1940.

- **[ansiweather](https://github.com/fcambus/ansiweather)** [![Stars](https://img.shields.io/github/stars/fcambus/ansiweather?style=social&color=white)](https://github.com/fcambus/ansiweather/stargazers)  
  🐚 Lightweight Shell script to display current weather conditions and forecasts in your terminal with ANSI colors and Unicode meteorological symbols.

- **[MetPy (Unidata)](https://github.com/Unidata/MetPy)** [![Stars](https://img.shields.io/github/stars/Unidata/MetPy?style=social&color=white)](https://github.com/Unidata/MetPy/stargazers)  
  🔬 Open-source Python library for meteorological analysis, unit-aware thermodynamic calculations, skew-T diagrams, isentropic analysis, and radar visualization.

- **[Earth-2 Studio (NVIDIA)](https://github.com/NVIDIA/earth2studio)** [![Stars](https://img.shields.io/github/stars/NVIDIA/earth2studio?style=social&color=white)](https://github.com/NVIDIA/earth2studio/stargazers)  
  🚀 Accelerated family of AI weather and climate models, pipelines, and frameworks for medium-range forecasting, extreme event risk modeling, and physical data assimilation.

- **[ClimaX (Microsoft Research)](https://github.com/microsoft/climax)** [![Stars](https://img.shields.io/github/stars/microsoft/climax?style=social&color=white)](https://github.com/microsoft/climax/stargazers)  
  🌐 Foundation model for weather and climate science capable of performing diverse atmospheric tasks including global forecasting, regional downscaling, and climate projection.

- **[WeatherBench 2 (Google Research)](https://github.com/google-research/weatherbench2)** [![Stars](https://img.shields.io/github/stars/google-research/weatherbench2?style=social&color=white)](https://github.com/google-research/weatherbench2/stargazers)  
  📊 Comprehensive benchmark dataset, verification metrics, and baseline suite for data-driven, machine-learned medium-range global weather forecasting.

- **[Pirate Weather](https://github.com/alexander0042/pirateweather)** [![Stars](https://img.shields.io/github/stars/alexander0042/pirateweather?style=social&color=white)](https://github.com/alexander0042/pirateweather/stargazers)  
  🏴‍☠️ Modern, open-source Dark Sky API replacement that ingests NOAA HRRR, GFS, and National Blend of Models (NBM) datasets to deliver fast, free JSON forecasts.

- **[ai-models (ECMWF Community)](https://github.com/ecmwf-lab/ai-models)** [![Stars](https://img.shields.io/github/stars/ecmwf-lab/ai-models?style=social&color=white)](https://github.com/ecmwf-lab/ai-models/stargazers)  
  🛠️ Community runner and plugin architecture to execute leading AI weather models (FourCastNet, Pangu-Weather, GraphCast, FuXi, Aurora, AIFS) on ECMWF open data feeds.

- **[awesome-weather-models](https://github.com/rebase-energy/awesome-weather-models)** [![Stars](https://img.shields.io/github/stars/rebase-energy/awesome-weather-models?style=social&color=white)](https://github.com/rebase-energy/awesome-weather-models/stargazers)  
  📚 Curated catalogue of AI-based weather forecasting models, documentation on weights availability, operational data pipelines, and performance benchmarks.

- **[awesome-large-weather-models](https://github.com/ai4earth/awesome-large-weather-models)** [![Stars](https://img.shields.io/github/stars/ai4earth/awesome-large-weather-models?style=social&color=white)](https://github.com/ai4earth/awesome-large-weather-models/stargazers)  
  📑 Resource list tracking foundation weather models, atmospheric transformers, radar nowcasting architectures, and climate AI research papers.

- **[AWIPS II (Unidata / NOAA)](https://github.com/Unidata/awips2)** [![Stars](https://img.shields.io/github/stars/Unidata/awips2?style=social&color=white)](https://github.com/Unidata/awips2/stargazers)  
  🛰️ Open-source release of the National Weather Service's Advanced Weather Interactive Processing System for real-time radar, satellite, and model grid analysis.

- **[weather-data-downloader](https://github.com/DWesl/weather-data-downloader)** [![Stars](https://img.shields.io/github/stars/DWesl/weather-data-downloader?style=social&color=white)](https://github.com/DWesl/weather-data-downloader/stargazers)  
  📥 Automated tools and CLI scripts for fetching and processing Numerical Weather Prediction (NWP) model outputs from NOAA NOMADS and ECMWF servers.

---

## 🧩 Meteorological Toolkits & Building Blocks

| Category 📂 | Description 📝 | Key Technologies & Repositories 🎯 |
| :--- | :--- | :--- |
| **Global Reanalysis Datasets** | Historical ground-truth hourly weather reconstructions spanning 1940 to present. | **ERA5** (ECMWF), **MERRA-2** (NASA), **NCEP CFSR**, Zarr/Cloud datasets |
| **Numerical Weather Prediction (NWP)** | Operational physical simulation grids at global and regional scales. | **NOAA GFS/HRRR/NAM**, **ECMWF IFS/AIFS**, **DWD ICON**, **MeteoFrance ARPEGE** |
| **Doppler Radar & Nowcasting** | Sub-hourly high-resolution precipitation tracking and severe convective storm detection. | **MRMS**, **NEXRAD Level II/III**, **pyart** (Python ARM Radar Toolkit) |
| **Self-Hosted API Servers** | Low-latency local and self-hosted APIs for serving forecast and historical data. | **Open-Meteo Server**, **Pirate Weather AWS Stack**, **FastAPI + Zarr** |
| **Data Science & Gridded Formats** | Formats and libraries optimized for multi-dimensional spatio-temporal meteorological cubes. | **Xarray**, **NetCDF4**, **Zarr**, **GRIB / eccodes**, **Cartopy** |

---

## ⚡ Quick Start Recommendations

| Use Case 🎯 | Recommended Starting Point 🚀 |
| :--- | :--- |
| **Best Free API for Developers (No Key Required)** | **[Open-Meteo](https://github.com/open-meteo/open-meteo)** |
| **Best Drop-in Replacement for Dark Sky** | **[Pirate Weather](https://github.com/alexander0042/pirateweather)** |
| **Best Enterprise Hyperlocal Resilience Platform** | **[Tomorrow.io](https://www.tomorrow.io/)** |
| **Best Machine Learning Global Forecast Model** | **[GraphCast](https://github.com/google-deepmind/graphcast)** or **[ai-models](https://github.com/ecmwf-lab/ai-models)** |
| **Best GPU-Accelerated Weather Inference Stack** | **[NVIDIA Earth-2](https://github.com/NVIDIA/earth2studio)** |
| **Best Python Library for Meteorological Analysis** | **[MetPy](https://github.com/Unidata/MetPy)** |
| **Best CLI / Terminal Weather Viewer** | **[wttr.in](https://github.com/chubin/wttr.in)** or **[wego](https://github.com/schachmat/wego)** |
| **Best Historical Weather Reanalysis Access** | **[Visual Crossing](https://www.visualcrossing.com/)** or **ERA5 via Open-Meteo** |
| **Best Environmental & Air Quality API** | **[Ambee](https://www.getambee.com/)** or **[Weatherbit](https://www.weatherbit.io/)** |

---

## 📈 Star History

<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Weather-Intelligence&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Weather-Intelligence&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Weather-Intelligence&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Weather-Intelligence&type=date&legend=bottom-right" />
</picture>
</a>
</div>

---

## 🤝 How to Contribute

Contributions, updates, and new platform additions are warmly welcome!
1. Fork this repository.
2. Add or update entries in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Weather-Intelligence/README.md) following the existing table and badge conventions.
3. Ensure all links are active, descriptions are factual, and categories are properly sorted.
4. Submit a Pull Request with a clear description of changes.

⭐ Star the repository if you find it helpful!

---

## ⚠️ Disclaimer
- This repository is a **community-curated index** for informational and educational purposes — not an endorsement.
- Meteorological forecasts and severe weather predictions carry inherent physical uncertainty; always consult official national weather services (e.g., NOAA NWS, ECMWF, Met Office) for life-safety and emergency operations.
- Self-hosted numerical and AI models require appropriate compute hardware and adherence to source data licenses.

---
**Made with ❤️ for developers, data scientists, energy traders, climate researchers, and logistics teams building the future of weather intelligence.**
