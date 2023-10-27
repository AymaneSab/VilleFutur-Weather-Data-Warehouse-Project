# VilleFutur Weather Data Warehouse Project

## Introduction

Welcome to the VilleFutur Weather Data Warehouse project. This individual project focuses on building a robust data warehouse on Azure to collect, model, and analyze historical and current weather data for VilleFutur. The objective is to anticipate future infrastructure, urban planning, and public service needs based on meteorological insights.

## Project Overview

This project involves several key phases:

1. **Data Collection**: Relevant data points, including temperature, humidity, wind speed, and precipitation, have been extracted for specified years.

2. **Data Integration**: Data transformation and loading processes were implemented using Data Flow and Copy Data activities to populate Synapse tables.

3. **Data Modeling**: Dimension tables (DateDim and RegionDim) have been created and populated, and a fact table (WeatherMetrics) has been established.

4. **Data Warehouse Creation**: SQL scripts define attributes for DateDim, RegionDim, and WeatherMetrics, following a star schema.

5. **Data Warehouse Management**: Azure Monitor and Log Analytics are utilized to monitor activities, ensure GDPR compliance, and plan regular maintenance tasks.

6. **Historical Changes Tracking**: A Slowly Changing Dimension (SCD) Type 1 methodology has been applied to the RegionDim table to track historical changes.

## Project Repository

This project is open-source and hosted on GitHub. You can access the code, documentation, and updates in the following repository: [GitHub Project](https://github.com/AymaneSab/Azure_DataWareHouse).

## Connect with Me

I look forward to sharing more updates as this project progresses. Feel free to connect with me if you're interested in discussing data development, Azure, or any related topics.

## Tags

#DataAnalytics #DataWarehouse #Azure #DataDevelopment #GitHub #VilleFutur
