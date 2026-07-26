# Manufacturing-Quality-Dashboard

## Project Overview

This project demonstrates an end-to-end Manufacturing Quality Analytics solution using SQL and Power BI.

The objective was to analyze manufacturing inspection data, evaluate production quality, identify operational bottlenecks, and build an interactive dashboard for production managers and quality engineers.

The project follows a real-world analytics workflow:

* Data exploration using SQL
* KPI calculation
* Business insight generation
* Interactive dashboard development in Power BI
* Recommendation of process improvement opportunities

Rather than focusing only on visualization, the project emphasizes converting raw manufacturing data into actionable business insights that support operational decision-making.

## Business Problem

Manufacturing organizations continuously strive to maximize production output while maintaining high product quality. Increasing defect rates, scrap generation, and inconsistent production performance across plants, production lines, and work shifts directly impact manufacturing costs, customer satisfaction, and operational efficiency.

The objective of this project is to analyze manufacturing quality inspection data to answer key operational questions such as:

* Which production plant performs most efficiently?
* Which production shift generates the highest defect rate?
* Which production line contributes the most defects?
* How do process parameters such as machine age, production speed, temperature, humidity, and material grade influence product quality?
* Which operational factors should be prioritized to reduce manufacturing defects?

The final outcome is an interactive Power BI dashboard that enables production managers and quality engineers to monitor quality KPIs, identify operational bottlenecks, and support data-driven decision-making for continuous process improvement.

## Dataset Information

**Dataset Name:** Manufacturing Quality Decisions Dataset

**Source:** Kaggle

The dataset represents manufacturing quality inspection records collected across multiple production plants, production lines, work shifts, and inspection methods. Each record corresponds to the quality outcome of an inspected manufactured component.

### Dataset Summary

* Approximately 10,000 inspection records
* Multiple manufacturing plants
* Multiple production lines
* Multiple work shifts
* Product quality inspection outcomes
* Process parameters affecting manufacturing quality

### Key Business Attributes

| Category   | Example Fields                       |
| ---------- | ------------------------------------ |
| Production | Plant, Line, Shift                   |
| Quality    | Defect Type, Scrap, Rework           |
| Process    | Temperature, Humidity, Process Speed |
| Machine    | Machine Age                          |
| Material   | Material Grade                       |
| Inspection | Inspection Method                    |

The dataset enables analysis of production efficiency, defect generation, operational performance, and the impact of manufacturing process parameters on product quality.

### Dataset Limitations

This dataset is primarily intended for learning manufacturing analytics and dashboard development. While it captures realistic manufacturing concepts such as production lines, shifts, quality inspections, and process variables, it does not represent data from a live Manufacturing Execution System (MES). Therefore, business conclusions should be interpreted as analytical exercises rather than real production recommendations.

## Business Objectives

The primary objective of this project is to evaluate manufacturing quality performance and identify opportunities to improve production efficiency through data-driven analysis.

The analysis focuses on the following business objectives:

### 1. Monitor Production Performance

* Measure inspection volume across plants, production lines, and work shifts.
* Compare production distribution to identify workload imbalances.

### 2. Evaluate Manufacturing Quality

* Calculate accepted parts, defect rate, scrap rate, and overall production efficiency.
* Analyze the distribution of different defect types.

### 3. Identify High-Performing Operations

* Compare plants based on production volume and quality performance.
* Determine which production lines and shifts consistently achieve better quality.

### 4. Perform Root Cause Analysis

Investigate whether manufacturing process parameters influence product quality, including:

* Machine age
* Material grade
* Process speed
* Temperature
* Humidity

### 5. Generate Actionable Business Recommendations

Transform analytical findings into practical recommendations that can help manufacturing teams:

* Reduce defect rates
* Improve process stability
* Prioritize preventive maintenance
* Optimize production planning
* Improve overall operational efficiency
## Key Performance Indicators (KPIs)

The following KPIs were developed to evaluate manufacturing quality and operational performance.

| KPI                             | Description                                                                       | Business Purpose                                              |
| ------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **Inspection Volume**           | Total number of inspected parts                                                   | Measures production workload across plants, lines, and shifts |
| **Accepted Parts**              | Number of parts without defects                                                   | Indicates successful production output                        |
| **Defect Rate (%)**             | Percentage of inspected parts identified as defective                             | Measures overall manufacturing quality                        |
| **Scrap Rate (%)**              | Percentage of parts classified as scrap                                           | Quantifies production losses                                  |
| **Production Efficiency (%)**   | Accepted Parts ÷ Total Inspection Volume × 100                                    | Compares manufacturing efficiency across plants               |
| **Defect Distribution**         | Count of each defect category                                                     | Identifies the most frequent quality issues                   |
| **Plant Performance**           | Comparison of production volume and quality by plant                              | Identifies high-performing manufacturing plants               |
| **Shift Performance**           | Quality comparison across Day, Swing, and Night shifts                            | Detects operational variation between shifts                  |
| **Production Line Performance** | Defect rate comparison across manufacturing lines                                 | Evaluates line-level operational performance                  |
| **Root Cause Metrics**          | Analysis of machine age, process speed, humidity, temperature, and material grade | Identifies process parameters influencing product quality     |
