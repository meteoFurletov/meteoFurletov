# Nikita Furletov

**Data engineer for open-source analytics infrastructure. Meteorologist by training.**

[![Website](https://img.shields.io/badge/meteofurletov.com-222222?logo=googlechrome&logoColor=white)](https://meteofurletov.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-meteofurletov-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/meteofurletov)
[![Email](https://img.shields.io/badge/Email-meteofurletov%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:meteofurletov@gmail.com)
[![Skills](https://img.shields.io/badge/Agent%20skills-meteof--skills-6E56CF)](https://github.com/meteoFurletov/skills)

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

<img align="right" width="340"
     src="https://raw.githubusercontent.com/meteoFurletov/noise-meteo-spb/main/docs/figures/phase_f_v2/fig1b_polar_seasonal_diurnal.png"
     alt="Probability of favourable sound propagation by direction over Saint Petersburg, four season and time-of-day panels">

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

<br clear="both">

## Stack

ClickHouse · SQLMesh · Airflow · Python · Go · Terraform · Kubernetes · xarray · PyTorch

Saint Petersburg. I work in Russian and English.
