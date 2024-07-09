# Uber-ETL

## Overview
Uber-ETL is a project focused on ETL (Extract, Transform, Load) processing. ETL is a fundamental process in data engineering and analytics that involves extracting data from various sources, transforming it into a usable format, and loading it into a target database or data warehouse. This project is designed for learning purposes and provides a hands-on approach to understanding ETL workflows.

## Workflow
The workflow of this project involves several key steps:

- **Data Extraction**: Data is extracted from multiple sources, including databases, APIs, and flat files.
- **Data Transformation**: The extracted data is cleaned, normalized, and transformed to fit the required schema. Various transformations are applied to split the data into different dimension tables.
- **Data Loading**: Transformed data is loaded into a target database. A fact table is created from the dimension tables to facilitate data analysis and reporting.

## Data Model
The data model for this project is designed to efficiently store and manage the transformed data. It includes:
- **Dimension Tables**: These tables contain attributes related to the dimensions of the data, such as time, geography, and user details.
- **Fact Table**: This table stores the transactional data and references the dimension tables to provide a comprehensive view of the data.

The detailed data model can be found in the attached diagram (`uber_data_model.pdf`).

## Data Dictionary
The data dictionary provides a detailed description of the data elements used in this project. It includes:
- **Table Definitions**: Descriptions of each table and its purpose.
- **Column Definitions**: Details of each column, including data types, constraints, and descriptions.

The complete data dictionary is included in the attached document (`data_dictionary.pdf`).

## Note
This project is intended for educational purposes and may differ from real-world ETL projects based on your specific requirements and style. Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.
