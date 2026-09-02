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

## Weather and climate

Open projects for meteorologists. Code, data and write-ups are in the repos; take what is useful.

- **[noise-meteo-spb](https://github.com/meteoFurletov/noise-meteo-spb)** — how often the atmosphere favours sound propagation over Saint Petersburg, by direction, season and time of day. ERA5, 2014–2024, validated against radiosondes. Ready to plug into noise calculations.
- **[weather-sounding-tool](https://github.com/meteoFurletov/weather-sounding-tool)** — radiosonde data, easy to fetch and analyse.
- **[lightning_classification](https://github.com/meteoFurletov/lightning_classification)** — lightning detection from Doppler radar with machine learning.
- **[omsk-agriculture-microclimate](https://github.com/meteoFurletov/omsk-agriculture-microclimate)** — agrometeorological climatology of Omsk Oblast from ERA5, 1981–2024.

In progress: probabilistic post-processing of GEFS and AIFS ensembles over north-west Russia with
IMPROVER. Not public yet.

Coursework from 2023, kept for the record:
[Urban-Rural-Windscapes](https://github.com/meteoFurletov/Urban-Rural-Windscapes),
[atmospheric_modeling](https://github.com/meteoFurletov/atmospheric_modeling),
[climate_analysis](https://github.com/meteoFurletov/climate_analysis).

## Stack

ClickHouse · SQLMesh · Airflow · Terraform · Kubernetes · Atmospheric science

Digital nomad.
