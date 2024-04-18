# OpenWeatherAPI_Airflow_AWS_ETL

## Overview
This is an end-to-end ETL pipeline project which utilizes the OpenWeatherMap API to fetch weather data, performs transformations, and then loads the transformed data into AWS S3. The entire workflow is managed using Apache Airflow on an AWS EC2 instance.

## Requirements
- Python 3.x
- Apache Airflow
- OpenWeatherMap API Key
- AWS Account with access to EC2 and S3 services

## Files
- `weather_dag.py`:  Python script to fetch weather data from OpenWeatherMap API, to transform and load data into AWS S3 and Apache Airflow DAG file to orchestrate the entire workflow.

## Acknowledgements
- [OpenWeatherMap](https://openweathermap.org/) for providing weather data through their API.
- [Apache Airflow](https://airflow.apache.org/) for enabling workflow orchestration.
- [AWS](https://aws.amazon.com/) for providing cloud infrastructure.

