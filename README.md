# ✈️ Aviation Accident Risk Analysis

## 📊 Overview

This project analyzes aviation accident data to support strategic decision-making for a company entering the aviation industry. The goal is to identify the safest and most suitable aircraft for commercial and private investment, based on historical accident trends and key flight attributes.

---

## 🧠 Business Problem

> Your company is expanding into new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises but lack knowledge about aviation risks.  
>
> You are tasked with determining which aircraft pose the **lowest investment risk** and converting those findings into **actionable insights** to guide procurement for the new aviation division.

---

## 📌 Key Questions Answered

- Which aircraft models are most frequently involved in accidents?
- What injury severity patterns exist across aircraft types?
- How do seasonal trends and weather conditions influence accident rates?
- What regulatory categories (FAR descriptions) show better safety records?
- Which flight schedules and purposes are most prone to incidents?

---

## 📁 Dataset

- **Source**: [Kaggle - Aviation Accident Database Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)
- **Columns Used**:
  - `event_date`, `event_year`, `event_decade`
  - `aircraft_make`, `aircraft_model`, `make_model`
  - `aircraft_damage`, `injury_severity_clean`, `total_individuals_affected`
  - `weather_condition`, `schedule_type`, `purpose_of_flight`
  - `state_full`, `far_description_explained`, `report_status`

---

## 📊 Tableau Dashboard

A fully interactive Tableau dashboard was developed, consisting of:

1. **Accidents Over Time** – Shows overall safety improvements.
2. **Monthly Trends** – Highlights peak risk months (June–August).
3. **Injury Severity by Aircraft Model** – Correlates model frequency with accident impact.
4. **FAR Regulation Impact** – Assesses safety under different regulatory brackets.
5. **Aircrafts Frequently Involved** – Identifies models with the highest impact.
6. **Filters** – Includes weather conditions, FAR description, and flight schedule.

> 🖥️ *Interactive visualizations empower stakeholders to explore scenarios and make data-informed investment decisions.*

---

## ✅ Business Recommendations

1. **Invest in Commercial & Business-Class Aircraft**  
   Safer, more regulated, and better suited for large-scale operations.

2. **Avoid High-Risk Small Aircraft**  
   Especially those used for personal or instructional purposes.

3. **Purchase Newer Aircraft**  
   Modern planes feature superior safety systems and reliability.

4. **Leverage FAR 121 and 135 Operations**  
   These show stronger safety performance due to strict regulatory oversight.

5. **Schedule Flights During Lower-Risk Periods**  
   Avoid peak summer months where accident rates historically spike.

---

## 🛠️ Tools Used

- **Python**: Data cleaning, preprocessing, and exploratory analysis (`pandas`, `plotly`, `matplotlib`, `seaborn`)
- **Tableau**: Interactive dashboard for storytelling and business intelligence

---

## 💻 Getting Started

To explore or replicate this analysis locally, follow the steps below:

### 1. 📦 Clone the Repository

```bash
git clone https://github.com/your-username/aviation-risk-analysis.git
cd aviation-risk-analysis
```

### 2. 🐍 Set Up Your Conda Environment

Make sure you have [Anaconda](https://www.anaconda.com/) installed. Then run:

```bash
conda create --name aviation-risk python=3.10
conda activate aviation-risk
```

### 3. 📚 Install Required Packages

You can install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn plotly
```


### 4. 📁 Load the Dataset

Ensure the dataset is organized in the following folder structure:

```
Data/
└── Aviation-data/
    └── AviationData.csv
```

Then, in your Python script or notebook, load the data using:

```python
import pandas as pd

aviation_data = pd.read_csv("Data/Aviation-data/AviationData.csv", encoding="latin1")
```

---

## 🙌 Acknowledgements

Special thanks to the following data sources and resources that made this project possible:

### 📊 Data Sources

- **Main Dataset**: [Kaggle - Aviation Accident Database Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)
- **FAA Regulations**: [Federal Aviation Administration (FAA)](https://www.faa.gov/regulations_policies/faa_regulations)
- **NTSB Aviation Reports**: [NTSB Aviation Query](https://www.ntsb.gov/Pages/AviationQueryv2.aspx)
- **Wikipedia**: [Wikipedia](https://www.wikipedia.org/) – for quick aircraft and terminology references
- **National Geographic**: [Air Crash Investigation Series](https://www.natgeotv.com/za/shows/natgeo/air-crash-investigation)

---
