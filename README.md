# WattWise – Smart Energy Monitoring and Waste Detection System

## Project Information

Project Title: WattWise – Smart Energy Monitoring and Waste Detection System

Course: Fundamentals of Data Engineering

Course Code: 24DEA3101

Academic Year: 2026–2027

Team: 14

Section: 7


## Team Members
------------------------------------------------
| S. No. | University ID | Name                |
| ------ | ------------- | ------------------- |
| 1      | 2420030204    | Y. Sri Anjana       |
| 2      | 2420030295    | Devanaboina Likitha |
| 3      | 2420030745    | CH. Hemavathi       |
------------------------------------------------

Under the Guidance of:
Dr. N. Shirisha
Assistant Professor
---

# 1. Project Overview

Buildings such as colleges, offices, and institutions consume significant amounts of electricity for their daily operations. Unnecessary usage, inefficient equipment, and abnormal consumption patterns can result in considerable energy wastage.

Traditional electricity monitoring methods may depend on manual observation or periodic readings, making it difficult to identify unusual consumption patterns promptly.

WattWise is a Big Data-based smart energy monitoring and waste detection system designed to continuously analyze electricity-consumption data and identify abnormal usage patterns.

The system uses simulated smart-meter data and integrates Big Data technologies for data ingestion, storage, processing, anomaly detection, risk analysis, and visualization.

# 2. Why Smart Energy Monitoring?

Smart energy monitoring was selected because buildings such as colleges, offices, and institutions continuously consume electricity for various activities.

Continuous monitoring can help organizations understand how electricity is being consumed and identify unusual usage patterns that may indicate potential energy wastage.

The major areas considered by WattWise include:

* Electricity consumption monitoring
* High-energy usage identification
* Abnormal consumption detection
* Energy wastage identification
* Consumption trend analysis
* Data-driven energy management

Large volumes of energy-consumption records require scalable technologies for data ingestion, storage, processing, and analysis.

Therefore, WattWise uses a Big Data pipeline to process energy data and generate useful insights.

# 3. Problem Statement

Traditional energy monitoring approaches often rely on manual observation or periodic electricity readings.

The major problems include:

* Lack of continuous monitoring
* Difficulty identifying abnormal consumption promptly
* Unnecessary energy usage
* Inefficient use of electrical equipment
* Difficulty processing large volumes of energy data
* Limited automated anomaly detection
* Separation between data processing and visualization
* Limited actionable insights for energy management

These challenges make it difficult for institutions and organizations to identify potential energy wastage efficiently.

WattWise addresses these problems by developing a continuous Big Data-based energy monitoring and anomaly detection pipeline.

# 4. Existing Situation

Traditional energy monitoring may follow a workflow such as:

Electricity Consumption
          ↓
Periodic / Manual Readings
          ↓
Historical Data
          ↓
Manual Analysis
          ↓
Identify Abnormal Usage
          ↓
Separate Reporting / Visualization

This approach can make continuous monitoring and early identification of unusual consumption difficult.

Energy data may also increase significantly over time, creating a need for scalable data processing technologies.

# 5. Proposed Solution

WattWise proposes an integrated Big Data pipeline for continuous energy monitoring and waste detection.

The proposed pipeline follows:

Simulated Smart-Meter Data
          ↓
      Apache Kafka
          ↓
      Hadoop HDFS
          ↓
 Apache Spark / PySpark
          ↓
 Data Cleaning & Transformation
          ↓
  Feature Engineering
          ↓
  Anomaly Detection
          ↓
    Risk Analysis
          ↓
       Power BI
          ↓
Energy Trends & Wastage Insights

The system continuously generates simulated smart-meter records without requiring physical IoT hardware.

Apache Kafka is used for continuous data ingestion, Hadoop HDFS is used for scalable storage, and Apache Spark is used for data processing and analysis.

The system then identifies abnormal consumption patterns using an anomaly detection module and presents the processed information through Power BI.

# 6. Objectives

The main objectives of WattWise are:

* To monitor electricity consumption continuously using simulated smart-meter data.
* To collect and process large volumes of energy-consumption data efficiently.
* To store energy data using scalable Big Data storage technologies.
* To analyze electricity-consumption patterns.
* To identify abnormal energy usage.
* To detect potential energy wastage through anomaly detection.
* To calculate risk associated with abnormal consumption.
* To visualize consumption trends and anomalies.
* To provide actionable insights for energy-efficient decision-making.

# 7. Technologies Used
--------------------------------------------------------------------------
| Technology             | Purpose                                       |
| ---------------------- | --------------------------------------------- |
| Python                 | Generate simulated smart-meter data           |
| Apache Kafka           | Continuous energy-data ingestion              |
| Hadoop HDFS            | Storage of raw and processed data             |
| Apache Spark / PySpark | Data cleaning, transformation, and processing |
| Spark SQL              | Energy-data querying and aggregation          |
| Python / PySpark       | Feature engineering                           |
| Scikit-learn           | Machine-learning implementation               |
| Isolation Forest       | Anomaly detection                             |
| Python                 | Risk-score calculation                        |
| Power BI               | Visualization and dashboard                   |
---------------------------------------------------------------------------

# 8. System Workflow

The proposed WattWise workflow is:

Start
  ↓
Generate Simulated Smart-Meter Data
  ↓
Apache Kafka Data Ingestion
  ↓
Store Data in Hadoop HDFS
  ↓
Process Data Using Apache Spark
  ↓
Data Cleaning & Transformation
  ↓
Feature Engineering
  ↓
Anomaly Detection
  ↓
Risk Analysis
  ↓
Power BI Visualization
  ↓
Energy-Wastage Insights
  ↓
End

The workflow integrates data generation, ingestion, storage, processing, analytics, anomaly detection, risk analysis, and visualization into a single pipeline.

# 9. Data Generation and Ingestion

WattWise uses simulated smart-meter data to represent electricity-consumption records.

The simulated data continuously generates energy-consumption information without requiring physical IoT hardware.

Apache Kafka is used as the data-ingestion layer to stream the generated energy-consumption records.

This enables the system to demonstrate continuous energy-data processing.

# 10. Data Processing and Analytics

After ingestion, energy-consumption data is stored using Hadoop HDFS.

Apache Spark / PySpark is used to process the data.

The processing stage includes:

* Data cleaning
* Data transformation
* Data aggregation
* Energy-consumption analysis
* Feature engineering

Spark SQL is used for querying and aggregating energy data.

The processed data is then passed to the anomaly detection stage.

# 11. Anomaly Detection

WattWise identifies unusual electricity-consumption patterns using an anomaly detection module.

Isolation Forest is used to identify abnormal consumption records.

Anomalies may indicate unusual or inefficient electricity usage and can help identify potential energy wastage.

The anomaly detection process is integrated into the Spark-based data-processing pipeline.

# 12. Risk Analysis

After identifying abnormal energy-consumption patterns, WattWise performs risk analysis.

Python is used to calculate a risk score associated with detected abnormal consumption.

The risk analysis helps categorize and understand the potential severity of unusual energy usage.

The resulting information can support organizations in prioritizing areas that require attention.

# 13. Visualization and Dashboard

Power BI is used to visualize the processed energy-consumption data and detected anomalies.

The dashboard provides information such as:

* Energy-consumption trends
* High-usage areas
* Detected anomalies
* Abnormal consumption patterns
* Risk information
* Actionable energy-management insights

The visualization layer helps users understand energy usage and make informed decisions for improving energy efficiency.

# 14. Repository Structure

WattWise/
│
├── src/
│   └── Source code and implementation files
│
├── docs/
│   └── Presentations and project documentation
│
├── data/
│   └── Dataset or documented data-source references
│
├── results/
│   └── Processing results and analysis outputs
│
├── reports/
│   └── Phase reports and project deliverables
│
├── README.md
└── .gitignore

# 15. Expected Outcome

The expected outcome of WattWise is an integrated Big Data-based energy monitoring system capable of continuously processing electricity-consumption data and identifying potential energy wastage.

The project aims to provide:

* Continuous energy-consumption monitoring
* Efficient processing of large energy datasets
* Detection of abnormal consumption patterns
* Identification of potential energy wastage
* Risk analysis of unusual consumption
* Interactive visualization of energy trends
* Actionable insights for energy-efficient decision-making

The system is intended to demonstrate how Big Data technologies can be integrated for intelligent energy management.

# 16. Setup and Execution

## Prerequisites

The following tools and technologies are required:

* Python
* Apache Kafka
* Hadoop HDFS
* Apache Spark / PySpark
* Scikit-learn
* Power BI
* Git
* GitHub

## Setup

1. Clone the repository.
2. Install the required Python dependencies.
3. Configure Apache Kafka.
4. Configure Hadoop HDFS.
5. Configure Apache Spark / PySpark.
6. Configure the required project environment.
7. Place the required dataset or configure the documented data source.
8. Start the required services.
9. Run the smart-meter data-generation module.
10. Start the data-processing pipeline.

## Execution Flow

Start
  ↓
Generate Smart-Meter Data
  ↓
Stream Data Through Kafka
  ↓
Store Data in HDFS
  ↓
Process Data Using Spark
  ↓
Clean & Transform Data
  ↓
Perform Feature Engineering
  ↓
Detect Anomalies
  ↓
Calculate Risk Scores
  ↓
Generate Results
  ↓
Visualize Through Power BI
  ↓
End

# 17. Current Phase Status

Current Phase: Project Setup and Initial Development

Status: Project structure, problem identification, literature review, objectives, methodology, system architecture, and technology-stack planning have been completed.

The implementation of the smart-meter data generation, Kafka ingestion, HDFS storage, Spark processing, anomaly detection, risk analysis, and Power BI visualization components will be developed progressively.

The README will be updated as the project progresses through its different phases.

# 18. Team Contributions

Each team member will contribute to the project using their own GitHub account.

Progressive and meaningful commits will be maintained throughout the project so that individual contributions can be verified through the GitHub commit history.

Team members will contribute to different areas of the project, including:

* Data generation
* Data ingestion
* Data storage
* Data processing
* Anomaly detection
* Risk analysis
* Visualization
* Documentation
* Testing and evaluation

# 19. Project Deliverables

The project will be developed and submitted progressively through different project phases.

Phase deliverables will be tagged appropriately in the GitHub repository.

Example tags:
review-1
review-2
final

Project presentations, reports, documentation, source code, results, and other deliverables will be maintained in the appropriate repository directories.

# 20. Data Security

The repository will not contain sensitive, confidential, or unauthorized information.

The following information must not be uploaded to GitHub:

* Passwords
* API keys
* Database credentials
* Authentication tokens
* Confidential institutional data
* Licensed datasets without permission

Sensitive configuration information should be stored securely using environment variables or appropriate configuration methods.

# 21. Future Scope

Future improvements to WattWise may include:

* Integration with real smart-meter or IoT devices
* Real-time energy monitoring
* Advanced anomaly detection techniques
* Improved energy-wastage prediction
* More detailed risk analysis
* Automated alerts for abnormal energy consumption
* Integration with additional data sources
* Improved Power BI dashboards
* Expansion to larger institutional and commercial environments
* More advanced energy-efficiency recommendations

# 22. Conclusion

WattWise aims to provide a Big Data-based solution for continuous electricity-consumption monitoring and energy-wastage detection.

The system integrates simulated smart-meter data generation, Apache Kafka, Hadoop HDFS, Apache Spark, anomaly detection, risk analysis, and Power BI visualization into an end-to-end pipeline.

By identifying abnormal consumption patterns and presenting them through an interactive dashboard, WattWise aims to help colleges, offices, and institutions understand their energy usage and make data-driven decisions for improving energy efficiency.
