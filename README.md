# GridScope — Energy & Grid Analytics

An analytics engineering portfolio project exploring electricity generation, grid operations, and the transition to cleaner energy.

Built with dbt v2, SQL, DuckDB, and eventually Snowflake.

## Project Goals

GridScope transforms publicly available energy data into reliable, well-tested analytical datasets.

The project is designed to demonstrate practical analytics engineering skills, including:

- Multi-source data integration and standardization
- Data quality testing and validation
- Complex SQL transformations
- Incremental processing and historical data management
- Dimensional modeling and analytical marts
- Reusable dbt macros and documentation
- Automated testing and CI/CD

## Planned Data Sources

- EIA-860: Power plant and generator characteristics
- EIA-923: Electricity generation and fuel consumption
- EIA-930: Hourly grid operating data
- Weather data: Future integration

## Technology Stack

| Technology | Purpose |
|---|---|
| dbt v2 | Data transformation and testing |
| DuckDB | Local development |
| Snowflake | Cloud data platform |
| SQL | Data modeling |
| Python | Data ingestion and automation |
| GitHub | Version control and collaboration |

## Project Structure

- `models/staging/` — Source-specific cleaning and standardization
- `models/intermediate/` — Reusable transformation logic
- `models/marts/core/` — Curated facts and dimensions
- `models/marts/reporting/` — Analytical reporting models
- `seeds/` — Local reference data
- `macros/` — Reusable dbt logic

## Status

Project setup and local development environment established. Data ingestion and modeling are upcoming.

---

*An independent analytics engineering portfolio project.*