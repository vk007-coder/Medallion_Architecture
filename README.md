# Medallion Architecture

## Description
This project implements the Medallion Architecture pipeline (Bronze → Silver → Gold layers) using PySpark. The goal is to process and manage large datasets in stages, ensuring data quality and transforming raw data into meaningful insights.

## Requirements
Before running the project, ensure you have the following installed:

- **Python** (Latest version, 3.13.1 or higher)
- **JDK** (Version 11.0.2 or higher)
- **PySpark** (Version 3.5.4)
- **PyCharm IDE** (Community Edition)

## Installation

1. **Install Python 3.13.1**  
   Download and install Python from the official [Python website](https://www.python.org/downloads/). Ensure that Python is added to the system path during installation.

2. **Install JDK 11.0.2 or higher**  
   Download and install JDK from the official [Oracle JDK website](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html). Make sure the `JAVA_HOME` environment variable is set correctly.

3. **Install PySpark 3.5.4**  
   Install PySpark using pip:
   ```bash
   pip install pyspark==3.5.4

Once the setup is complete, you can run the project from PyCharm or any Python environment:
**Clone the repository:**
git clone https://github.com/vk007-coder/Medallion_Architecture

**Navigate to the project directory:**
cd Medallion-Architecture
**Download the code.zip file which contains below and Execute the PySpark pipeline to run the Medallion Architecture layers:**
1.generate_data_with_config(generate random .csv file for testing) 
2.python bronze_layer.py(Raw data ingestion and storage)
3.python silver_layer.py(Data cleansing, transformations, and enrichment)
4.python gold_layer.py(Data aggregation and transformation into analytical form for reporting and insights.)


