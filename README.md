# **F1 Lap Time & Pit Stop Analysis**

## **Project Overview**
This project focuses on analyzing Formula 1 (F1) lap times and pit stop strategies using **PySpark** for large-scale data processing. Pit stops play a crucial role in determining race outcomes, and optimizing their timing can significantly enhance team strategies. By leveraging telemetry data such as lap times, tire wear, and environmental conditions, this project aims to identify patterns and insights that could help in decision-making.

## **Objective**
The primary goal of this project is to:
- Process **F1 lap data** using PySpark for efficient computation.
- Identify laps involving **pit stops** and analyze their impact on overall race performance.
- Handle missing values and clean the dataset for accurate analysis.
- Engineer key features such as **tyre wear trends, track temperature variations, and pit stop frequency**.
- Provide insights into optimizing pit stop strategies based on historical lap performances.

## **Dataset**
The dataset used in this project consists of **20 race sessions**, stored in a CSV file:  
📂 `updated_combined_laps_20_sessions_v2.csv`  

**Key Features:**
- **Lap Time (Seconds)** – Total time taken to complete a lap.
- **Tyre Wear (%)** – Degradation of tires over laps.
- **Track & Air Temperature (°C)** – Environmental conditions affecting performance.
- **Pit Stop Time (Seconds)** – Duration of pit stops, if applicable.
- **IsPitLap (Binary Flag)** – A derived feature indicating whether the lap includes a pit stop.

## **Technology Stack**
- **PySpark** – For scalable and distributed data processing.
- **Pandas** – For local data manipulations.
- **DBFS (Databricks File Store)** – To store and access large datasets.
- **Apache Spark SQL** – For querying and transforming structured data.

## **Key Processing Steps**
1. **Data Ingestion**: Load the dataset using PySpark’s DataFrame API.
2. **Data Cleaning**: Handle missing values in critical features.
3. **Feature Engineering**: Create new insights such as `IsPitLap`, tire degradation trends, and temperature effects.
4. **Exploratory Data Analysis (EDA)**: Analyze lap trends, pit stop effects, and environmental impact.
5. **Optimization Insights**: Evaluate race strategies based on historical data.

## **Installation & Setup**
To run this project, ensure you have the following dependencies installed:

```bash
pip install pyspark pandas
