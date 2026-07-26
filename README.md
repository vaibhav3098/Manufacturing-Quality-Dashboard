# Manufacturing-Quality-Dashboard
![SQL Server]
![Power BI]
![GitHub]
## Project Highlights

* End-to-end Manufacturing Quality Analytics project
* Built using SQL Server and Microsoft Power BI
* Analyzed 10,000+ manufacturing inspection records
* Developed 10+ business KPIs
* Performed root cause analysis using machine age, process speed, temperature, humidity, and material grade
* Designed an interactive Power BI dashboard with dynamic filtering
* Generated business recommendations to improve manufacturing quality and operational efficiency


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
## SQL Analysis

SQL was used to transform raw manufacturing inspection data into meaningful business insights. The analysis followed a structured approach, beginning with production monitoring and progressing toward quality evaluation and root cause analysis.

### Production Analysis

* Calculated inspection volume across manufacturing plants.
* Compared production distribution across production lines.
* Evaluated workload across different work shifts.

### Quality Analysis

* Calculated accepted parts and defective parts.
* Measured production efficiency.
* Computed defect rate and scrap rate.
* Analyzed defect distribution across multiple defect categories.

### Performance Comparison

* Compared quality performance between manufacturing plants.
* Evaluated production line efficiency.
* Identified quality variation across work shifts.

### Root Cause Analysis

Investigated relationships between manufacturing process variables and product quality:

* Machine Age vs Defect Rate
* Material Grade vs Defect Rate
* Process Speed vs Crack Defects
* Humidity vs Contamination Defects
* Temperature vs Finish Defects

### SQL Concepts Used

The project demonstrates practical usage of:

* Aggregate Functions
* GROUP BY
* CASE WHEN
* Conditional Aggregation
* Common Table Expressions (CTEs)
* Window Functions
* Subqueries
* Data Type Casting
* Business KPI Calculations
## Power BI Dashboard

An interactive Power BI dashboard was developed to provide a comprehensive view of manufacturing quality performance. The dashboard enables users to monitor production, evaluate quality metrics, and identify operational bottlenecks through interactive filtering and visualization.

### Dashboard Features

#### Executive KPI Cards

* Inspection Volume
* Accepted Parts
* Defect Rate (%)
* Scrap Rate (%)

#### Production Monitoring

* Inspection Volume by Plant
* Inspection Volume by Production Line
* Inspection Volume by Shift

#### Quality Monitoring

* Defect Rate by Plant
* Defect Rate by Production Line
* Defect Rate by Shift
* Defect Distribution by Defect Type

#### Interactive Filtering

The dashboard supports dynamic filtering using:

* Plant
* Production Shift
* Material Grade
* Inspection Method

Selecting any filter automatically updates all dashboard visuals, allowing users to analyze manufacturing performance from multiple operational perspectives.

### Business Value

The dashboard enables production managers and quality engineers to:

* Monitor manufacturing performance in real time.
* Compare quality performance across plants, shifts, and production lines.
* Quickly identify areas with elevated defect rates.
* Support data-driven operational and quality improvement decisions.
## Key Business Insights

The analysis identified several operational patterns and quality trends across the manufacturing process.

### Production Performance

* Plant 1 processed the highest inspection volume while also achieving the highest production efficiency (~84.5%), indicating strong operational performance.
* Production volume was relatively balanced across manufacturing lines, suggesting an even distribution of workload.

### Shift Performance

* The Night Shift recorded the highest defect rate despite having the lowest production volume.
* This suggests that operational conditions during the night shift should be investigated further, including staffing, supervision, machine availability, and maintenance practices.

### Material Quality

* Material Grade A achieved the lowest defect rate while supporting the highest production volume.
* Material Grade C exhibited the highest defect rate, indicating that raw material quality may significantly influence manufacturing performance.

### Machine Performance

* Defect percentage increased consistently with machine age.
* Machines older than 12 years showed the highest defect rate, highlighting the importance of preventive maintenance and equipment replacement planning.

### Process Parameters

* Crack defects increased noticeably once process speed exceeded approximately 90 units/hour.
* Higher humidity levels were associated with an increase in contamination defects.
* Finish defects showed higher occurrence at elevated operating temperatures, suggesting environmental conditions may influence product quality.

## Overall Observation

The analysis indicates that manufacturing quality is influenced by a combination of operational, environmental, and equipment-related factors rather than a single root cause.

Continuous monitoring of process parameters together with preventive maintenance and material quality control can significantly improve manufacturing performance.
## Business Recommendations

Based on the analysis, the following operational improvements are recommended:

### 1. Improve Night Shift Quality

The Night Shift recorded the highest defect rate despite handling a lower production volume.

**Recommended Actions**

* Review staffing levels and operator training.
* Evaluate machine maintenance schedules during night operations.
* Increase quality inspection frequency during the night shift.

---

### 2. Prioritize Preventive Maintenance

Older machines exhibited progressively higher defect rates.

**Recommended Actions**

* Introduce preventive maintenance based on machine age.
* Schedule periodic machine health assessments.
* Prioritize replacement or refurbishment of aging equipment with consistently poor quality performance.

---

### 3. Optimize Process Speed

Crack defects increased significantly when process speed exceeded approximately 90 units per hour.

**Recommended Actions**

* Review production targets at higher operating speeds.
* Perform cost-benefit analysis between increased throughput and additional scrap generation.
* Establish optimal operating speed limits for stable production.

---

### 4. Improve Environmental Controls

Higher humidity and elevated operating temperatures were associated with increased contamination and finish defects.

**Recommended Actions**

* Continuously monitor shop-floor environmental conditions.
* Improve temperature and humidity control where economically feasible.
* Define acceptable operating ranges for critical manufacturing processes.

---

### 5. Strengthen Material Quality Control

Material Grade C demonstrated the highest defect rate among all material grades.

**Recommended Actions**

* Review supplier quality performance.
* Increase incoming material inspection for lower-performing grades.
* Investigate process adjustments or supplier improvement initiatives.

---

## Expected Business Impact

Implementing these recommendations may contribute to:

* Lower manufacturing defect rates
* Reduced scrap and rework costs
* Improved production efficiency
* Better equipment utilization
* More consistent manufacturing quality
* Enhanced operational decision-making through data-driven monitoring
## Tech Stack

The following tools and technologies were used throughout this project:

### Data Analysis

* SQL Server
* T-SQL

### Business Intelligence

* Microsoft Power BI
* DAX (Data Analysis Expressions)

### Data Visualization

* KPI Cards
* Clustered Column Charts
* Donut Charts
* Slicers
* Interactive Dashboard

### Development Environment

* SQL Server Management Studio (SSMS)
* Microsoft Power BI Desktop

### Version Control

* Git
* GitHub
## Project Structure

```text
Manufacturing-Quality-Dashboard
│
├── README.md
│
├── dataset
│   └── ManufacturingQuality.csv
│
├── sql
│   ├── 01_Business_Questions.sql
│   ├── 02_SQL_Analysis.sql
│   └── 03_KPI_Calculations.sql
│
├── powerbi
│   └── Manufacturing_Quality_Dashboard.pbix
│
├── dashboard
│   └── Dashboard.pdf
│
├── screenshots
│   ├── Dashboard.png
│   └── SQL_Output.png
│
└── insights.md
```
## Future Improvements

This project served as a foundational manufacturing analytics project for learning SQL and Power BI while applying business-oriented analytical thinking.

Future enhancements include:

* Develop a multi-page executive dashboard with drill-through functionality.
* Perform trend analysis using time-series manufacturing data.
* Build advanced DAX measures for operational KPIs.
* Integrate Python for exploratory data analysis (EDA) and statistical analysis.
* Develop machine learning models for defect prediction and quality forecasting.
* Incorporate supplier performance and maintenance history for deeper root cause analysis.
* Automate reporting using scheduled Power BI refreshes.
* Expand the project using a more realistic manufacturing dataset with richer operational complexity.
## Dashboard Preview

### Executive Dashboard

<img src="https://github.com/vaibhav3098/Manufacturing-Quality-Dashboard/blob/ff3486124e354cde20978761fe3e23daecd95034/screenshots/dashboard_overview.png">

The dashboard provides an interactive view of manufacturing performance through production KPIs, quality metrics, defect analysis, and operational filtering.

Users can analyze manufacturing performance by:

* Plant
* Production Line
* Shift
* Material Grade
* Inspection Method
  
## Author

**Vaibhav Sharma**

Mechanical Design Engineer transitioning into Data Analytics.

### Skills Demonstrated

* SQL
* Power BI
* Business Analytics
* Manufacturing Analytics
* KPI Development
* Root Cause Analysis
* Dashboard Design

For suggestions or feedback, feel free to connect through GitHub.

