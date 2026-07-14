# Marketing Mix Effectiveness Analysis

A marketing analytics project that evaluates the effectiveness of multiple promotional programs using time series analysis, A/B testing, lift analysis, and regression modeling.

The project analyzes physician-level marketing activities from a pharmaceutical company to quantify the impact of different marketing channels on prescription volume and provides data-driven recommendations for optimizing marketing investments.

---

## Project Overview

Pharmaceutical companies invest substantial resources in physician-focused marketing initiatives, including speaker programs, free drug samples, loyalty cards, and sales representative visits.

Determining which marketing activities generate the greatest increase in prescriptions is essential for improving marketing efficiency and maximizing return on investment.

This project evaluates the effectiveness of four major promotional programs and identifies the optimal level of marketing activity using statistical analysis and business analytics techniques.

---

## Business Problem

Marketing budgets are finite, making it important to allocate resources toward the most effective promotional activities.

This project investigates several key business questions:

- Which marketing programs generate the largest increase in prescription volume?
- How long does it take for marketing activities to influence physician prescribing behavior?
- Which marketing initiatives deliver the highest return?
- What level of promotional activity maximizes effectiveness?
- How should future marketing campaigns and medical conferences be evaluated?

---

## Dataset

The dataset contains physician-level marketing activity and prescription information collected over multiple time periods.

Marketing activities include:

- Speaker Programs
- Free Samples
- Loyalty Cards
- Sales Representative Visits

The analysis measures how these activities influence prescription volumes and physician engagement over time.

---

## Tools & Technologies

- R
- tidyverse
- dplyr
- ggplot2
- Time Series Analysis
- Linear Regression
- A/B Testing
- Lift Analysis
- Business Analytics
- Marketing Analytics

---

## Project Workflow

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Time series analysis
4. A/B testing
5. Lift analysis
6. Multiple linear regression
7. Subgroup analysis
8. Business recommendations

---

## Methodology

### Time Series Analysis

Historical prescription volumes were analyzed to identify recurring trends, seasonal patterns, and the timing of marketing activities.

Prescription peaks were compared with promotional activities to evaluate delayed marketing effects.

---

### A/B Testing

Physicians who participated in each marketing initiative were compared with physicians who did not participate.

This approach estimates the incremental impact of each marketing program while reducing selection bias.

---

### Lift Analysis

Lift analysis compares prescription performance between treatment and control groups.

The analysis identifies which marketing activities generate the largest increase in prescriptions and determines the optimal participation intensity.

---

### Regression Modeling

Multiple linear regression was used to estimate the independent contribution of each marketing initiative while controlling for the effects of other promotional activities.

Regression coefficients were used to compare the relative importance of each marketing channel.

---

## Key Findings

### Loyalty Cards

Loyalty Cards generated the strongest impact on prescription growth.

- Approximately **230% prescription lift**
- Largest regression coefficient (**β = 2.098**)
- Prescription volume increased until approximately five loyalty cards per physician before diminishing returns appeared.

---

### Free Samples

Free Samples produced a significant increase in prescriptions.

- Approximately **92% lift**
- Regression coefficient (**β = 0.523**)

The analysis suggests distributing approximately **50–75 samples per physician** to maximize effectiveness.

---

### Sales Representative Visits

Sales representative visits positively influenced physician prescribing behavior.

- Approximately **74% lift**
- Regression coefficient (**β = 0.342**)

Sales visits were most effective when combined with other marketing initiatives.

---

### Speaker Programs

Speaker Programs showed a statistically significant but comparatively smaller impact than the other promotional channels.

---

### Marketing Time Lag

Marketing activities influenced prescription volume after approximately **2–6 weeks**, suggesting campaign performance should be evaluated over an extended period rather than immediately after implementation.

---

## Medical Conference Evaluation

The project also proposes a framework for evaluating marketing effectiveness at medical conferences.

Recommended performance metrics include:

- Booth interaction rate
- Physician engagement duration
- Contact information submission rate
- Prescription conversion rate
- Three-month ROI
- Six-month ROI

These metrics provide a structured approach for measuring conference performance and supporting future investment decisions.

---

## Business Recommendations

Based on the analysis:

- Expand Loyalty Card distribution in high-performing regions.
- Increase Free Sample allocation for high-potential physicians.
- Use Sales Representative visits to reinforce Loyalty Card and Free Sample campaigns.
- Reassess the effectiveness of Speaker Programs and improve audience targeting.
- Incorporate time-lag analysis when evaluating future marketing campaigns.
- Establish standardized performance metrics for conference marketing activities.

---

## Repository Structure

```
marketing-mix-effectiveness-analysis/

│
├── Marketing_Campaign_Report.pdf
└── README.md
```

---

## Repository Contents

| File | Description |
|------|-------------|
| Marketing_Campaign_Report.pdf | Project report describing methodology, analysis, findings, and recommendations |
| README.md | Project documentation |

---

## Future Improvements

Potential future enhancements include:

- Applying causal inference techniques such as Propensity Score Matching or Difference-in-Differences.
- Developing physician-level response prediction models using machine learning.
- Optimizing marketing budget allocation through simulation and optimization models.
- Incorporating physician specialty, geographic location, and patient characteristics.
- Building an interactive dashboard for campaign monitoring and ROI tracking.

---

## Skills Demonstrated

- Marketing Analytics
- Marketing Mix Analysis
- Campaign Effectiveness Analysis
- A/B Testing
- Lift Analysis
- Time Series Analysis
- Regression Modeling
- Business Analytics
- Data Visualization
- R
- Statistical Analysis
