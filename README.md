# Awesome-Atmospheric-Modeling-Weather-Simulation

## Top Atmospheric Modeling & Weather Simulation Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Numerical Weather Prediction (NWP), AI Weather Forecasting, Climate Simulation, Meteorological APIs & Atmospheric Data Processing*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Atmospheric Modeling & Weather Simulation**. These tools forecast, simulate, assimilate, downscale, and serve global and hyperlocal meteorological data using Numerical Weather Prediction (NWP) physics engines, machine learning weather models, satellite/radar telemetry, and self-hosted weather APIs.



**Examples** include Tomorrow.io, AccuWeather API, OpenWeatherMap, Meteomatics, Weatherbit, ClimaCell, Visual Crossing, Spire Weather, Earth Networks, DTN Weather, and pw-tf/isowind (the category leaders and notable community entries). 



**Open-source emphasis**: This section is heavily expanded with every major active project for meso-scale NWP modeling (WRF, MPAS), AI-powered global forecasting (GraphCast, FourCastNet, Aurora, Pangu-Weather), self-hosted weather APIs (Open-Meteo), and meteorological Python toolkits — ideal for meteorologists, climate scientists, renewable energy analysts, aerospace engineers, and developers building transparent weather intelligence systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Tomorrow.io (formerly ClimaCell)](https://tomorrow.io)**  

  AI-driven weather intelligence and hyperlocal atmospheric forecasting platform offering proprietary satellite data, probabilistic modeling, and enterprise weather APIs.



- **[Meteomatics](https://meteomatics.com)**  

  High-precision meteorological data provider combining global NWP models, radar/satellite nowcasting, and 90-meter downscaled weather APIs.



- **[OpenWeatherMap (OpenWeather)](https://openweathermap.org)**  

  Widely adopted cloud weather API platform offering global forecasts, historical weather archives, solar irradiance, and atmospheric air quality feeds.



- **[AccuWeather API](https://accuweather.com)**  

  Commercial weather forecasting and severe weather alerting API delivering minute-by-minute precipitation nowcasts and global location forecasts.



- **[Visual Crossing](https://visualcrossing.com)**  

  Cloud-based historical weather data and 15-day forecast API built for data science, energy modeling, agriculture, and business analytics.



- **[Weatherbit](https://weatherbit.io)**  

  High-speed RESTful weather API providing real-time observations, ensemble forecasts, air quality indices, and historical meteorological datasets.



- **[Spire Weather (Spire Global)](https://spire.com)**  

  Space-powered atmospheric modeling platform assimilating proprietary radio occultation satellite measurements into global numerical weather forecasts.



- **[DTN Weather](https://dtn.com)**  

  Enterprise operational meteorology and decision-support suite serving aviation, maritime, agriculture, utilities, and energy trading teams.



- **[Earth Networks (AEM)](https://earthnetworks.com)**  

  Global meteorological sensor network and hyperlocal severe-weather monitoring platform providing real-time lightning detection and atmospheric telemetry.





## Open-Source GitHub Projects



- **[Open-Meteo](https://github.com)**  

  Leading open-source weather forecast API written in Swift that aggregates high-resolution national weather service NWP models (NOAA GFS, DWD ICON, ECMWF IFS) with zero API keys required.



- **[WRF (Weather Research and Forecasting Model)](https://github.com)**  

  Industry-standard open-source mesoscale Numerical Weather Prediction (NWP) system developed by NCAR for atmospheric research and operational regional forecasting.



- **[GraphCast (Google DeepMind)](https://github.com)**  

  Open-source graph neural network weather forecasting model capable of predicting global weather variables 10 days ahead at 0.25-degree resolution in under a minute.



- **[NVIDIA Earth-2 / Makani & PhysicsNeMo](https://github.com)**  

  Open-source PyTorch framework for training and running massively parallel AI weather models such as FourCastNet and Spherical Fourier Neural Operators (SFNO).



- **[Microsoft Aurora](https://github.com)**  

  Open-source large-scale atmospheric foundation model trained on over a million hours of geophysical data for high-resolution weather, air quality, and ocean wave prediction.



- **[MPAS-Model (Model for Prediction Across Scales)](https://github.com)**  

  Open-source coupled atmosphere, ocean, and land-ice simulation system utilizing unstructured Voronoi meshes for variable-resolution global-to-local weather modeling.



- **[MetPy (Unidata)](https://github.com)**  

  Foundational open-source Python collection of tools for reading, visualizing, and performing thermodynamic and kinematic calculations with meteorological data.



- **[xarray](https://github.com)**  

  Essential open-source Python library for working with labeled multi-dimensional arrays (NetCDF, GRIB, Zarr) in atmospheric science and climate modeling.



- **[Herbie](https://github.com)**  

  Open-source Python package for discovering, downloading, and slicing Numerical Weather Prediction model outputs (HRRR, RAP, GFS, IFS, NBM) from cloud archives.



- **[earth2studio](https://github.com)**  

  Open-source Python toolkit providing standardized workflows for exploring, benchmarking, and running AI weather forecasting and data assimilation pipelines.



- **[pw-tf/isowind](https://github.com/pw-tf/isowind)**  

  Notable open-source community engine project (included per curated reference; an OpenMW-based isometric engine mod rather than an atmospheric simulator).



### Additional Strong Open-Source Options



- **[CLIMADA](https://github.com)** for probabilistic natural catastrophe, extreme weather risk, and climate adaptation modeling in Python.

- **[cfgrib](https://github.com)** and **[eccodes](https://github.com)** by ECMWF for decoding and encoding WMO GRIB and BUFR meteorological data formats.

- **[windrose](https://github.com)** and **[WindNinja](https://github.com)** for high-resolution terrain-aware surface wind field simulation and visualization.

- **[CESM (Community Earth System Model)](https://github.com)** for coupled global climate, atmosphere, ocean, and sea-ice simulation.

- **[Climt (Climate Modelling and Diagnostics Toolkit)](https://github.com)** for modular Python-based atmospheric column and radiative-convective modeling.



**Frameworks for building custom systems**: Combine **Open-Meteo** for self-hosted multi-model forecast APIs, **Herbie + xarray + MetPy** for GRIB/NetCDF atmospheric post-processing, and **GraphCast** or **WRF** for custom regional and AI-accelerated weather simulations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Atmospheric simulations and open-source forecast models should not be used as the sole source for life-safety aviation, maritime, or severe-weather emergency decisions; always consult official national meteorological agencies (NOAA/NWS, ECMWF, DWD, Met Office).

- Running full mesoscale NWP models (like `WRF`) or foundation AI weather models requires substantial multi-core CPU/MPI clusters or high-VRAM GPUs.



---



**Made for meteorologists, climate researchers, renewable energy engineers, data scientists, and open-source contributors.**  

Let's make atmospheric modeling and weather simulation more open, accurate, and accessible.
