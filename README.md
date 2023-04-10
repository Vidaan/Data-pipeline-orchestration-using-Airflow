# Data-pipeline-orchestration-using-Airflow

Objective: To create a data pipeline using Airflow.

Activities performed:
1. Defined a Data Pipeline
2. Executed a SQL request with the PostgresOperator to create a table
3. Executed a HTTP request against an API
4. Used a Sensor to check for the validity of the HTTP connection 
5. Executed a Python function with the PythonOperator to process the user data, captured through the API call, into a CSV file
6. Used Hooks to access secret methods that copies data from CSV file and saves it into the Postgres table
7. Exchange data between tasks through the dependencies

The final DAG:
<img width="434" alt="image" src="https://user-images.githubusercontent.com/56769902/231002945-849846c6-f8b8-4491-b00c-c6ee8879aa20.png">

Connections:
<img width="907" alt="image" src="https://user-images.githubusercontent.com/56769902/231005238-52f51e98-f1c6-4956-9145-0263ad3ea775.png">

