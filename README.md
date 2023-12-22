# VilleFutur Weather Data Warehouse Project

![Alt text](https://maghreb.simplonline.co/_next/image?url=https%3A%2F%2Fsimplonline-v3-prod.s3.eu-west-3.amazonaws.com%2Fmedia%2Fimage%2Fpng%2Fsans-titre-6506f97fa0d5a220127652.png&w=1280&q=75)
## Overview

The VilleFutur Weather Data Warehouse Project aims to collect, model, and analyze historical and current meteorological data from different regions of the growing metropolis. The primary goal is to create a robust and scalable data warehouse in Azure, providing decision-makers, researchers, and urban planners with easy access to relevant weather data. This warehouse will enable informed decision-making for future infrastructure, urban development, and public services in VilleFutur.

## Developer's Mission

As a Data Developer, your mission is to oversee the entire data pipeline, from data collection to the creation of the Azure data warehouse. Special attention should be given to GDPR compliance, historical change tracking, and ensuring data integrity and security.

## Project Phases

### 1. Data Collection

- Extract relevant data points (temperature, humidity, wind speed, precipitation, etc.) for specified years.

### 2. Data Integration

- Transform data using the "Data Flow" activity.
- Load transformed data using the "Copy Data" activity into Synapse tables.

### 3. Data Modeling

- Create dimension tables (DateDim and RegionDim).
- Populate dimension tables (generate data for DateDim, input regions for RegionDim).
- Establish the WeatherMetrics fact table populated through the ETL process.

### 4. Data Warehouse Creation

- Write SQL scripts defining attributes for DateDim, RegionDim, and WeatherMetrics tables.
- Implement a star schema, selecting appropriate tables.
- Document role and permission configurations, set up firewall rules for security.

### 5. Data Warehouse Management

- Monitor warehouse activity and performance using Azure Monitor and Log Analytics.
- Document GDPR compliance, specifying data types, sources, and purposes.
- Schedule regular maintenance tasks, such as deleting old data.

### 6. Historical Change Tracking

- Implement Type 1 Slowly Changing Dimension (SCD) on the RegionDim table to track historical changes.

## Getting Started

1. Clone the repository.
2. Follow the step-by-step guide in the `docs/` directory for setting up and executing the data warehouse pipeline.

## Requirements

- Azure account with necessary permissions.
- Azure Synapse Analytics.
- Azure Data Factory.
- SQL Server Management Studio or similar tool.
- ...

## Contributors

- [Aymane Sari]

## License

This project is licensed under the [MIT] - see the [LICENSE.md](LICENSE.md) file for details.
