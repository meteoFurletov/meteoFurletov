<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%"
       alt="Nikita Furletov. Data Platform Engineer. Analytics platforms on ClickHouse, S3 and Iceberg, SQLMesh, AWS.">
</picture>

<p align="center">
  <a href="https://meteofurletov.com"><img alt="Website" src="https://img.shields.io/badge/meteofurletov.com-24292f?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/meteofurletov"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHRleHQgeD0iMTIiIHk9IjE5IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iQXJpYWwsIEhlbHZldGljYSwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxOSIgZm9udC13ZWlnaHQ9IjcwMCIgZmlsbD0iI2ZmZiI+aW48L3RleHQ+PC9zdmc+"></a>
  <a href="mailto:meteofurletov@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/meteoFurletov/skills"><img alt="Agent skills" src="https://img.shields.io/badge/Agent%20skills-meteof--skills-6E56CF?style=flat-square&logo=anthropic&logoColor=white"></a>
</p>

I build analytics platforms as systems, not as sets of pipelines. I choose the storage and the
engine, put a transformation framework and quality gates on top, make the data discoverable, ship
the whole thing as code, and put an AI interface on it so people get answers without a developer in
the loop. A platform is trustworthy when nobody checks the number twice.

## Platform work

One analytics platform for a bookstore chain, four iterations since 2023. It started as PostgreSQL
with Airflow ETL in Docker on Yandex Cloud and DataLens dashboards. Then Airflow with SQLMesh
models, four Postgres instances and Superset, a proper transformation layer running on an always-on
VM far too big for the workload. Then a serverless, scale-to-zero lakehouse: Parquet on object
storage, DuckDB for every transformation, YAML data contracts that validate each dataset and
generate the catalog, atomic publish, all Terraform, at about 5× lower TCO than the VM it replaced.
The fourth is an AWS twin of the same platform on S3, Spark on AWS Glue, Iceberg tables and Athena,
with the Yandex Cloud original still running beside it. Finished in 2026. It runs unattended.

At TKB Investment Partners I re-architected the company data platform on a hybrid S3 and ClickHouse
medallion design, took it from one to two bad-data days a month to near-zero data-quality incidents
with SQLMesh audits and tests, and deployed OpenMetadata as the company-wide catalog. I also own the
internal AI infrastructure: Open WebUI over open-source LLMs, vLLM for inference with observability,
and MCP interfaces going onto internal services with Hermes on top.

## Weather and climate

Open projects for meteorologists. Code, data and write-ups are in the repos; take what is useful.

| Project | What it is |
|---|---|
| [noise-meteo-spb](https://github.com/meteoFurletov/noise-meteo-spb) | Sound-propagation climatology of Saint Petersburg from ERA5, by direction and season. |
| [postgrad_intro_exams](https://github.com/meteoFurletov/postgrad_intro_exams) | Exam notes on atmospheric physics and dynamics, as a [website](https://meteofurletov.github.io/postgrad_intro_exams/). |
| [weather-sounding-tool](https://github.com/meteoFurletov/weather-sounding-tool) | Radiosonde data, easy to fetch and analyze. |
| [lightning_classification](https://github.com/meteoFurletov/lightning_classification) | Lightning detection from Doppler radar with machine learning. |
| [omsk-agriculture-microclimate](https://github.com/meteoFurletov/omsk-agriculture-microclimate) | Agrometeorological climatology of Omsk Oblast from ERA5, 1981–2024. |
| [Urban-Rural-Windscapes](https://github.com/meteoFurletov/Urban-Rural-Windscapes) | Urban versus rural wind regimes around Saint Petersburg, by season. |
| [atmospheric_modeling](https://github.com/meteoFurletov/atmospheric_modeling) | NRLMSISE-00 atmosphere model checked against a year of radiosondes. |
| [climate_analysis](https://github.com/meteoFurletov/climate_analysis) | Station climate statistics: trends, anomalies, outliers, maps. |

## Stack

ClickHouse · dbt / SQLMesh · Airflow · AWS · Terraform · Iceberg · DuckDB

Digital nomad, based in Georgia (UTC+4).
