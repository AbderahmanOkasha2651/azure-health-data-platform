# Azure Data Factory Naming Conventions

## Purpose

Define consistent naming conventions for Azure Data Factory components to make pipelines easier to understand, maintain, and manage.

## Naming Standards

| Component | Prefix | Naming Pattern |
|---|---|---|
| Linked Service | `LS` | `LS_<ServiceType>_<ResourceName>` |
| Dataset | `DS` | `DS_<DataName>_<Layer>_<Format>` |
| Pipeline | `PL` | `PL_<Action>_<DataName>` |
| Activity | Descriptive name | `<Action> <DataName>` |

## Population Ingestion — Proposed Names

| Component | Proposed Name |
|---|---|
| Source Linked Service | `LS_Blob_CovidReportingSA` |
| Destination Linked Service | `LS_ADLS_CovidReportingDL` |
| Source Dataset | `DS_Population_Raw_GZip` |
| Destination Dataset | `DS_Population_Raw_TSV` |
| Pipeline | `PL_IngestPopulationData` |
| Copy Activity | `Copy Population Data` |

These names are based on the course's suggested naming approach. The actual component names will be confirmed during implementation.

## Naming Guidelines

- Use consistent prefixes for each component type.
- Include the service type in Linked Service names.
- Include the data subject and format in Dataset names.
- Name Pipelines according to their business purpose.
- Use descriptive Activity names that explain the operation.
