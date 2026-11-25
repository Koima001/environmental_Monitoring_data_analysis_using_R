# Environmental Monitoring Readings Analysis Using R

## 1. Project Overview

This project demonstrates the application of R programming in environmental data analysis, focusing on environmental monitoring readings across five industrial and processing sites.

The analysis explores environmental monitoring patterns involving air pollutants, temperature, rainfall, and wind speed. It applies data cleaning, validation, descriptive statistics, data standardization, and visualization techniques to assess environmental conditions and identify patterns that may require further investigation.

The project demonstrates practical data analysis skills, from preparing raw datasets to communicating findings and developing data-driven recommendations.

**Note:** The dataset used in this project is AI-generated for analytical and portfolio demonstration purposes. It does not represent actual environmental monitoring measurements or verified environmental conditions at the named sites.

## 2. Project Objectives

The main objectives of this project were to:

- Assess the completeness and quality of environmental monitoring data.
- Identify and address duplicate records and missing values.
- Standardize environmental monitoring variables and site names.
- Explore the distribution of environmental readings across different monitoring sites.
- Calculate descriptive statistics to summarize environmental variables.
- Visualize patterns and variations in pollutant concentrations and other environmental measurements.
- Interpret analytical findings and develop recommendations for environmental monitoring.

## 3. Tools and Technologies

| Tool/Technology | Application |
|---|---|
| R Programming | Data cleaning, manipulation, statistical analysis, and visualization. |
| RStudio | Development environment for conducting the analysis. |
| tidyverse | Data manipulation, transformation, and visualization. |
| lubridate | Date conversion and handling. |
| reactable / gt | Presentation of analytical tables. |
| R Markdown | Documentation and reporting of the analytical workflow. |
| Microsoft Word | Presentation of the final analysis report. |
| GitHub | Project version control and portfolio presentation. |

## 4. Dataset Description

The project uses an environmental monitoring dataset containing 1,505 initial records collected across five industrial and processing sites.

The dataset contains environmental measurements covering:

- **Air pollutants:** Carbon Monoxide (CO), Nitrogen Dioxide (NO2), Particulate Matter (PM10 and PM2.5), and Sulphur Dioxide (SO2).
- **Meteorological variables:** Temperature, rainfall, and wind speed.
- **Monitoring information:** Reading dates, monitoring sites, and pollutant categories.

The five monitoring locations represented in the dataset are:

1. Athi River Industrial Zone
2. Changamwe Works Area
3. Eldoret Industrial Area
4. Mtwapa Industrial Zone
5. Nakuru Processing Estate

## 5. Data Cleaning and Preparation

Data preparation was conducted using R to improve dataset quality and ensure consistency before analysis.

The cleaning and preparation process involved:

- Inspecting the dataset structure and variable types.
- Identifying and removing duplicate records.
- Assessing missing values across relevant variables.
- Standardizing monitoring site names.
- Converting date variables into appropriate date formats.
- Reviewing numerical variables for consistency and completeness.
- Preparing the cleaned dataset for statistical analysis and visualization.

**Data cleaning outcome:**
- Initial records: 1,505
- Duplicate records identified and removed: 5
- Final records: 1,500
- Remaining duplicate records: 0
- Missing pollutant reading values: 18

Missing values were retained as missing observations rather than replaced with arbitrary values.

## 6. Exploratory Data Analysis

Exploratory data analysis was conducted to understand the distribution, characteristics, and patterns within the environmental monitoring dataset.

The analysis covered:

- Dataset completeness and quality assessment.
- Distribution of environmental monitoring readings across sites.
- Descriptive statistics for pollutant and meteorological variables.
- Comparison of environmental readings across monitoring locations.
- Visualization of pollutant and meteorological measurements.

Visualizations and summary tables were used to support the interpretation of the dataset and highlight patterns requiring further investigation.

## 7. Key Findings and Recommendations

The analysis provided insights into the distribution and characteristics of environmental monitoring measurements across the five sites.

Key areas of investigation included pollutant reading variations, meteorological conditions, data completeness, and differences in environmental measurements across monitoring locations.

The findings informed recommendations focused on:

- Strengthening environmental monitoring and data collection practices.
- Improving data completeness and consistency.
- Prioritizing further investigation of elevated pollutant readings.
- Maintaining consistent monitoring procedures across sites.
- Using regular statistical analysis and visualization to support environmental assessment and decision-making.

*Detailed findings, supporting visualizations, and recommendations are presented in the final analysis report.*

## 8. Repository Structure

The repository is organized into two main folders containing the datasets, analysis code, and final report.

| Folder/File | Description |
|---|---|
| [a_data](./a_data/) | Contains the original raw dataset and the cleaned dataset used in the analysis. |
| [Raw Dataset](./a_data/r_environmental_monitoring_readings_raw.csv) | Original dataset before cleaning and preprocessing. |
| [Clean Dataset](./a_data/r_environmental_monitoring_readings_clean.csv) | Processed dataset used for exploratory data analysis and visualization. |
| [b_analysis](./b_analysis/) | Contains the R Markdown source code and final analytical report. |
| [R Markdown Analysis](./b_analysis/r_environmental_monitoring_readings.Rmd) | Documents the complete analytical workflow, including R code, data preparation, statistical analysis, and visualizations. |
| [Final Analysis Report](./b_analysis/environmental_monitoring_analysis.docx) | Presents the analytical findings, visualizations, interpretations, and recommendations. |

## 9. Skills Demonstrated

This project demonstrates practical competencies in:

- R programming and data manipulation.
- Data cleaning and quality assessment.
- Handling missing values and duplicate records.
- Data standardization and transformation.
- Descriptive statistics and exploratory data analysis.
- Environmental data interpretation.
- Data visualization and analytical reporting.
- Communicating findings and developing data-driven recommendations.
- Project documentation and version control using GitHub.

## 10. Project Conclusion

This project demonstrates an end-to-end analytical workflow using R, from raw data inspection and preparation to exploratory analysis, visualization, and reporting.

It highlights the application of data analytics techniques in environmental monitoring and demonstrates how structured data analysis can support the interpretation of environmental measurements and inform monitoring priorities.

The project also reinforces the importance of data quality, consistency, and clear communication when working with environmental datasets.
