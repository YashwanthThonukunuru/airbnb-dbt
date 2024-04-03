# Airbnb Data Engineering with dbt

## Project Overview

This project aims to simulate a comprehensive Airbnb analytics engineering workflow, leveraging the power of dbt (Data Build Tool) to transform raw Airbnb data into insightful analytics. I have focused on data regarding Airbnb listings, reviews, and host interactions, with a unique twist of exploring the influence of full moon occurrences on guest reviews. The project demonstrates data transformation and modeling.

## Data Source

Our data originates from [Inside Airbnb](http://insideairbnb.com/), a source of publicly available information about Airbnb's listings across various cities. For this project, we've chosen Berlin, Germany, as our primary focus, considering its vibrant Airbnb market and diverse listing types.

## Solution Architecture

The workflow encompasses several stages:

- **Data Ingestion**: Listings, reviews, and host data are ingested into a Snowflake staging area.
- **Transformation**: dbt models are employed to clean, transform, and prepare the data for dimensional modeling, including the creation of fact tables and handling slowly changing dimensions via snapshots.
- **Data Quality**: We implement dbt tests to ensure data integrity and quality throughout the process.

![image](https://github.com/YashwanthThonukunuru/airbnb-dbt/assets/116011869/5cbc9ba8-0ac1-43b9-a154-969206a793b8)

## Technology Stack

- **Snowflake**: Managed cloud data warehouse for scalable, secure, and efficient data storage and analytics.
- **dbt (Data Build Tool)**: Tool for transforming data in-warehouse through SQL - the core of our transformation layer.
  
Additional tools and technologies can be integrated as per the requirements, including cloud storage solutions for data ingestion and alternative data warehouses like BigQuery or Redshift.
