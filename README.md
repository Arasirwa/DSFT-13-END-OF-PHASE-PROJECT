# ✈️ Aviation Accident Risk Analysis

## 📊 Overview

This project analyzes aviation accident data to support strategic decision-making for a company entering the aviation industry. The goal is to identify the safest and most suitable aircraft for commercial and private investment, based on historical accident trends and key flight attributes.

## 📁 Dataset

- **Source**: [Kaggle - Aviation Accident Database Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)
- **Columns Used**:
  - `event_date`, `event_year`, `event_decade`
  - `aircraft_make`, `aircraft_model`, `make_model`
  - `aircraft_damage`, `injury_severity_clean`, `total_individuals_affected`
  - `weather_condition`, `schedule_type`, `purpose_of_flight`
  - `state_full`, `far_description_explained`, `report_status`

## 🧠 Business Problem

> Your company is expanding into new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises but lack knowledge about aviation risks.  
>
> You are tasked with determining which aircraft pose the **lowest investment risk** and converting those findings into **actionable insights** to guide procurement for the new aviation division.

## 📌 Key Questions Answered

- Which aircraft models are most frequently involved in accidents?
- What injury severity patterns exist across aircraft types?
- How do seasonal trends and weather conditions influence accident rates?
- What regulatory categories (FAR descriptions) show better safety records?
- Which flight schedules and purposes are most prone to incidents?

## 📊 Tableau Dashboard

A fully interactive Tableau dashboard was developed, consisting of:

1. **Accidents Over Time** – Shows overall safety improvements.
2. **Monthly Trends** – Highlights peak risk months (June–August).
3. **Injury Severity by Aircraft Model** – Correlates model frequency with accident impact.
4. **FAR Regulation Impact** – Assesses safety under different regulatory brackets.
5. **Aircrafts Frequently Involved** – Identifies models with the highest impact.
6. **Filters** – Includes weather conditions, FAR description, and flight schedule.

> 🖥️ *Interactive visualizations empower stakeholders to explore scenarios and make data-informed investment decisions.*

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

## 🛠️ Tools Used

- **Python**: Data cleaning, preprocessing, and exploratory analysis (pandas, plotly).
- **Tableau**: Interactive dashboard for storytelling and business intelligence.

 ## 🙌 Acknowledgements

## 📊 Data Sources

- **Main Dataset**: [Kaggle - Aviation Accident Database Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)  
  The core dataset used for exploratory analysis and dashboarding.

- **FAA Regulations**: [Federal Aviation Administration (FAA) Regulations](https://www.faa.gov/regulations_policies/faa_regulations)  
  Provided contextual support on how regulatory frameworks impact flight operations and accident risk.

- **NTSB Aviation Investigation Reports**: [NTSB Aviation Query](https://www.ntsb.gov/Pages/AviationQueryv2.aspx)  
  Helped validate the structure and format of aviation incident reporting.

- **Wikipedia**: [Wikipedia.org](https://www.wikipedia.org/)  
  Used for quick reference checks on aircraft types, manufacturers, and aviation terminology.

- **National Geographic – Air Crash Investigation**: [Air Crash Investigation Series](https://www.natgeotv.com/za/shows/natgeo/air-crash-investigation)  
  Provided narrative context and real-world investigative frameworks for aviation incidents.
