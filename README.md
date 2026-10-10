# Azure Health Data Platform

An Azure Data Engineering project focused on building an end-to-end
data pipeline using Microsoft Azure services.

The project uses COVID-19 and European population datasets to
implement data ingestion, storage, transformation, and orchestration
workflows.

## Azure Resources

| Resource | Name | Region | Status |
|---|---|---|---|
| Resource Group | `covid-reporting-rg` | UAE North | Active |
| Azure Data Factory | `covid-reporting-adf-abdo` | UAE North | Deployed |
| Azure Storage Account | `covidreportingsa67` | UAE North | Deployed |
| Azure Data Lake Storage Gen2 | `covidreportingdl67` | UAE North | Deployed |
| Azure SQL Server | `covid-srv67` | UAE North | Deployed |
| Azure SQL Database | `covid-db` | UAE North | Deployed |

## Documentation

### Data Ingestion

- [Population Data Ingestion Preparation](docs/setup/blob-ingestion-preparation.md)

### Project Standards

- [ADF Naming Conventions](docs/naming-conventions.md)