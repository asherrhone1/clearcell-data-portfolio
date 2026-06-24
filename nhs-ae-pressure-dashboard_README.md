# NHS A&E Pressure Dashboard

## Project Overview

This project analyses publicly available NHS A&E attendance and emergency admissions data to identify pressure points across providers.

The aim of the project is to demonstrate how raw public healthcare data can be cleaned, transformed and analysed to produce useful operational insight. The analysis focuses on A&E demand, waiting-time pressure, emergency admissions and long waits after a decision to admit.

This project was created as part of a data analytics portfolio to show skills in healthcare analytics, business intelligence and operational reporting.

---

## Business / Public-Sector Problem

A&E departments can experience pressure from high attendance volumes, emergency admissions, long waits and delays after a decision to admit.

Using public NHS A&E data, this project explores:

* Which providers have the highest A&E attendance volumes
* Which providers show the highest over-4-hour waiting-time pressure
* Which providers have the highest 12+ hour decision-to-admit waits
* Which providers appear as statistical outliers
* How providers can be segmented into different pressure groups

The aim is not to make clinical conclusions, but to show how data can support operational review and decision-making.

---

## Data Source

The project uses publicly available NHS England A&E Attendances and Emergency Admissions data.

The analysis combines six monthly CSV files covering:

* October 2025
* November 2025
* December 2025
* January 2026
* February 2026
* March 2026

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* Google Drive

---

## Skills Demonstrated

* Data cleaning
* Combining multiple CSV files
* Column standardisation
* KPI creation
* Exploratory data analysis
* Provider ranking
* Trend analysis
* Outlier detection using z-scores
* Provider segmentation
* Data visualisation
* Business insight reporting
* Translating technical analysis into plain-English recommendations

---

## Key Measures Created

The raw dataset contained separate columns for different A&E department types. These were combined into clearer operational KPIs, including:

* Total A&E attendances
* Total attendances over 4 hours
* Within-4-hour performance rate
* Over-4-hour wait rate
* Emergency admissions via A&E
* Admission rate
* Total decision-to-admit waits
* 12+ hour decision-to-admit waits
* Combined pressure score

---

## Analysis Performed

### 1. Data Cleaning

The dataset was cleaned by standardising column names, combining monthly files and creating a clean working dataset for analysis.

### 2. KPI Creation

New operational measures were created to make the raw data easier to interpret.

### 3. Provider Ranking

Providers were ranked by:

* Total A&E attendances
* Average over-4-hour wait rate
* Total 12+ hour DTA waits
* Emergency admissions
* Combined pressure score

### 4. Data Visualisation

Charts were created to show:

* Top providers by A&E attendance volume
* Top providers by waiting-time pressure
* Top providers by 12+ hour decision-to-admit waits
* Monthly attendance trends
* Monthly within-4-hour performance trends

### 5. Outlier Detection

A z-score method was used to identify providers with unusually high pressure indicators compared with the wider dataset.

Outlier indicators included:

* High over-4-hour wait rate
* High 12+ hour DTA waits
* High emergency admissions
* High attendance volume

### 6. Provider Segmentation

Providers were segmented into four pressure groups:

* High demand / High wait pressure
* High demand / Lower wait pressure
* Lower demand / High wait pressure
* Lower demand / Lower wait pressure

This helped separate demand pressure from waiting-time pressure.

---

## Key Insights

The analysis showed that A&E pressure is not explained by one single measure. Some providers experience pressure because of very high attendance volumes, while others appear under pressure because a higher proportion of patients wait longer than 4 hours.

The combined pressure score provided a simple way to identify providers that ranked highly across several indicators. This is not an official NHS metric, but it is useful as a portfolio method for identifying organisations that may warrant further operational review.

Outlier detection helped highlight providers whose pressure indicators were noticeably different from the rest of the dataset.

The segmentation analysis showed that the most important group for further review is the “High demand / High wait pressure” segment, because these providers combine large attendance volumes with higher waiting-time pressure.

---

## Recommendations

Based on the analysis, the following recommendations were made:

1. Prioritise providers with repeated pressure across several indicators.
2. Review providers in the high demand / high wait pressure segment.
3. Investigate outlier providers separately to understand local causes.
4. Monitor monthly trends to identify worsening pressure over time.
5. Develop the analysis into a repeatable dashboard that updates when new data becomes available.

---

## Limitations

This project uses publicly available provider-level data and does not include patient-level, staffing, bed-capacity or local operational data.

The analysis should therefore be treated as a high-level operational review rather than a full performance assessment.

The combined pressure score and segmentation approach are portfolio methods created for analysis and demonstration purposes. They are not official NHS performance measures.

---

## Future Improvements

Future versions of the project could include:

* More months of data
* Regional filtering
* Provider-level drilldowns
* Interactive dashboard development
* Integration with other public NHS datasets
* More advanced anomaly detection
* Forecasting of future pressure trends
* Comparison by NHS region or trust type

---

## Portfolio Summary

This project demonstrates how public healthcare data can be converted into meaningful operational insight.

It shows the ability to clean messy data, create useful KPIs, identify trends, detect outliers, segment providers and communicate findings clearly to non-technical stakeholders.

The project is relevant to healthcare analytics, business intelligence, NHS operational reporting and data consultancy work.
