# dbt-analytics-engineer

# DBT Project: Data Transformation and Analytics
## Overview
This DBT project aims to perform data transformation, data testing, validation, and enable analytics on data stored in Google BigQuery. It utilizes the power of DBT, a popular data modeling and transformation tool, to streamline and automate the data pipeline.

## Prerequisites
Before running this project, make sure you have the following prerequisites set up:

Access to a Google Cloud Platform (GCP) project with BigQuery enabled.
Installed and configured DBT on your local machine or environment.
Proper access credentials and permissions to access the BigQuery datasets.

## Setup
To set up and run this DBT project, follow these steps:

Clone the repository to your local machine or environment:

`git clone https://github.com/your-username/dbt-project.git`

Configure the necessary credentials and connection details in the profiles.yml file. This file should be located in the .dbt directory. Provide the appropriate values for your BigQuery project and authentication.

1 - Navigate to the project directory:

`cd dbt-project`

2 - Install the required dependencies:

`dbt deps`

## Usage
To utilize this DBT project, follow these steps:

1 - Run the DBT transformations:

`dbt run`

2 - Execute data tests to ensure data quality:

`dbt test`

3 - Generate documentation for the project:

`dbt docs generate`

4 - Open the generated documentation:

`dbt docs serve`

## Project Structure
The project structure follows the standard DBT conventions:

dbt_project.yml: Configuration file for the DBT project.
profiles.yml: Connection and authentication details for BigQuery.
models/: Directory containing the DBT models and transformations.
tests/: Directory containing data tests and validations.
macros/: Directory containing custom macros for reusability.
docs/: Directory containing the generated documentation.


## License
This project is licensed under the MIT License. Feel free to use and modify the codebase according to your needs.








