# data_pipeline_airflow_snowflake
This project is designed to automate the process of loading CSV data into a Snowflake database using Apache Airflow and dbt. The project leverages existing sample data from Snowflake, allowing for efficient data handling and transformation within a cloud-based environment.
## Key Components
- **DAG**: Managed in `load_data_to_snowflake.py`, responsible for reading and loading data.
- **dbt**: Used for transforming the data and managing data models.
- **Snowflake**: The cloud data warehouse for storing and managing data.

## Technologies Used
- **Apache Airflow**
- **dbt**
- **Snowflake**

## Implementation Steps
1. Set Up Snowflake Table
2. Read Data
3. Transform Data
4. Load Data
5. Schedule Workflow

## Conclusion
This project streamlines the process of loading data into Snowflake, enhancing data accessibility for analysis while reducing manual effort and time.
