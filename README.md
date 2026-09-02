<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%"
       alt="Nikita Furletov. Data engineer for open-source analytics infrastructure. Meteorologist by training.">
</picture>

<p align="center">
  <a href="https://meteofurletov.com"><img alt="Website" src="https://img.shields.io/badge/meteofurletov.com-24292f?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/meteofurletov"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHRleHQgeD0iMTIiIHk9IjE5IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iQXJpYWwsIEhlbHZldGljYSwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxOSIgZm9udC13ZWlnaHQ9IjcwMCIgZmlsbD0iI2ZmZiI+aW48L3RleHQ+PC9zdmc+"></a>
  <a href="mailto:meteofurletov@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/meteoFurletov/skills"><img alt="Agent skills" src="https://img.shields.io/badge/Agent%20skills-meteof--skills-6E56CF?style=flat-square&logo=anthropic&logoColor=white"></a>
</p>

I build analytics platforms on open source, ClickHouse, S3 and Parquet, SQLMesh, Airflow, and I like
doing it from an empty repository. I dig into system internals and architectural trade-offs before
picking a tool, then own the result: pipelines, models, data quality, catalog, and the infrastructure
code underneath.

By day that is an investment company's data platform and its internal AI infrastructure (open-source
LLM serving, RAG, MCP servers for agents). On my own time it is a serverless lakehouse
on Yandex Cloud that costs a few dollars a month and doubles as a testbed for ideas before they touch
production. A platform is trustworthy when nobody checks the number twice.

My degrees are in atmospheric science, and postgraduate research keeps me in probabilistic
forecasting. It is where I got comfortable with messy spatiotemporal data, ERA5, GRIB, ensembles, and
where I learned that a number without its uncertainty isn't finished.

## Open source

| | |
|---|---|
| [skills](https://github.com/meteoFurletov/skills) | Agent skills I write and reuse across projects, shipped as one Claude Code plugin that is also its own marketplace. |
| [modern-sql-style](https://github.com/meteoFurletov/modern-sql-style) | A modern SQL style guide, DML and DDL, packaged as an agent skill. |
| [remarkable-pdf](https://github.com/meteoFurletov/remarkable-pdf) | Rendering Markdown and HTML into PDFs laid out for the reMarkable Paper Pro. Agent skill. |
| [balka](https://github.com/meteoFurletov/balka) | A file-based, AI-powered personal OS that runs inside Claude Code: tasks, learning loop, wiki. |
| [postgrad_intro_exams](https://github.com/meteoFurletov/postgrad_intro_exams) | Quartz digital garden with my postgraduate entrance-exam notes. |

## Weather and climate

Not my day job, but the problems are good and the data is messy in instructive ways. Kept as a
portfolio.

| | |
|---|---|
| [noise-meteo-spb](https://github.com/meteoFurletov/noise-meteo-spb) | ERA5 climatology of favourable sound-propagation conditions for Saint Petersburg, by direction, season and time of day, for traffic-noise calculation under ГОСТ 31295.2 / ISO 9613-2 and CNOSSOS-EU. Master's thesis: full pipeline, three stability classifiers, radiosonde validation, CI. |
| [weather-sounding-tool](https://github.com/meteoFurletov/weather-sounding-tool) | Downloads University of Wyoming radiosondes and extracts temperature inversions to Excel. |
| [lightning_classification](https://github.com/meteoFurletov/lightning_classification) | Machine-learning classification of lightning discharges from Doppler weather radar. |
| [omsk-agriculture-microclimate](https://github.com/meteoFurletov/omsk-agriculture-microclimate) | ERA5 agrometeorological climatology of Omsk Oblast, 1981–2024. |
| [Urban-Rural-Windscapes](https://github.com/meteoFurletov/Urban-Rural-Windscapes) · [atmospheric_modeling](https://github.com/meteoFurletov/atmospheric_modeling) · [climate_analysis](https://github.com/meteoFurletov/climate_analysis) | 2023 coursework: urban versus rural wind climatology, atmospheric models, climate analysis. |

Current research: probabilistic post-processing of GEFS and AIFS ensemble forecasts over north-west
Russia with the Met Office IMPROVER framework. Not public yet.

## Stack

<p>
  <img alt="ClickHouse" src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black">
  <img alt="SQLMesh" src="https://img.shields.io/badge/SQLMesh-1F2937?style=flat-square">
  <img alt="Airflow" src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white">
  <img alt="S3 and Parquet" src="https://img.shields.io/badge/S3%20%2B%20Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
</p>
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?style=flat-square">
  <img alt="xarray" src="https://img.shields.io/badge/xarray-1F5C99?style=flat-square">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white">
</p>

Saint Petersburg. I work in Russian and English.
