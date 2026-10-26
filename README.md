# AI Readiness & Governance Capstone

## Digital Infrastructure and AI Access

This capstone will focus on the digital infrastructure and connectivity across countries as a foundation for understanding broader AI 
readiness and to indentify areas that can be improved to help solidify the expansion of AI within the nation. 

## Project Overview
This project will explore the national readiness of developing countries by analyzing the technological, socioeconomic and governance indicators.
The goal will be to examine the differences in AI readiness between developing and developed nations and identify factors that mau influence a country's ability to adopt
and benefit from artifical intelligence.

The project is designed from the perspective of a data analyst/scientist
advising an international development organization with limited resources
for digital development.

The central stakeholder problem is:

> Where are the greatest digital infrastructure and connectivity needs,
> and what types of infrastructure or adoption barriers appear to be
> contributing to those gaps?

## Project Progress

### Experiment A — Data Preparation and Predictive Modeling (Completed)

Experiment A examined whether selected digital infrastructure indicators could help predict internet adoption across 25 countries between 2018 and 2024.

The analysis combined telecommunications data from the International Telecommunication Union (ITU) with World Bank electricity access and country classification data. After preprocessing, 174 country-year observations were available for supervised modeling.

Four regression approaches were compared: DummyRegressor (baseline), Multiple Linear Regression, Ridge Regression, and Random Forest Regression.

**Final 2024 Test Results**

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Tuned Random Forest | 7.224 | 10.168 | 0.872 |
| Multiple Linear Regression | 9.718 | 13.015 | 0.791 |
| Ridge Regression | 9.755 | 13.041 | 0.790 |
| Baseline | 27.189 | 29.376 | -0.065 |

Random Forest produced the lowest prediction errors. However, the analysis also revealed substantial errors for individual countries, especially some observations with missing infrastructure indicators.

Because the same countries appeared across the training and testing periods, the results do not establish how well the model would perform on entirely new countries.

### Experiment B — Infrastructure Availability vs. Internet Adoption (Planned)

The next phase will expand the analysis beyond the original 25-country sample to include all countries with eligible data available through the ITU and relevant World Bank sources.

The research will focus on understanding the difference between infrastructure availability and actual internet adoption. Greater attention will be given to descriptive analysis, identifying countries where network coverage exceeds internet use, and investigating patterns that may help explain these differences.

The goal is to develop findings that can help Jupiter's Justice better understand digital infrastructure gaps and identify areas requiring further investigation before investment decisions are made.
---

## Project Objective

The objective of this project is to develop a data-driven framework for
evaluating digital infrastructure needs across countries.

The analysis distinguishes between several stages of digital access:

1. Foundational infrastructure
2. Digital infrastructure availability
3. Household access
4. Digital adoption and use

This structure will help identify whether observed connectivity gaps are
associated with limited infrastructure availability or lower adoption of
available infrastructure.

---

## Core Indicators

The initial analysis uses telecommunications and infrastructure indicators
from the International Telecommunication Union (ITU) and nations electricity data
from The World Bank's World Developent Indicators (WB).

### Nations Electricity Access
- Access to electricity (% of population)

### Digital Infrastructure
- Population coverage by mobile network technology

### Digital Access
- Households with Internet access at home

### Digital Adoption and Use
- Individuals using the Internet
- Active mobile-broadband subscriptions
- Fixed-broadband subscriptions

### Supporting Variable
- Total population

Population will be used to normalize raw subscription counts so that
countries of different population sizes can be compared more appropriately.

## Research / Business Questions

The project currently investigates:

1. Which countries demonstrate the largest basic connectivity gaps?
2. Where does mobile broadband infrastructure exist but adoption remains low?
3. Do observed connectivity gaps appear more strongly associated with
   infrastructure availability or adoption?
4. Which countries rely more heavily on mobile broadband compared with
   fixed broadband?
5. How does foundational infrastructure, particularly electricity access,
   relate to observed digital connectivity gaps?

## Country Selection

Countries were grouped by World Bank income level, and then selected from different regions to make sure the sample included geographic diversity. More countries were selected from the low- and middle-income groups because they are the main focus of this project, while a smaller number of high-income countries were selected for comparison.

The initial candidate screening pool contains 29 economies:

- 8 Low Income
- 8 Lower Middle Income
- 8 Upper Middle Income
- 5 High Income benchmarks

Candidate selection is based on income classification and geographic
representation rather than telecommunications performance.

The candidate pool will be screened for ITU data availability across the core
digital infrastructure and access indicators for approximately 2018–2025.
Countries with insufficient longitudinal coverage may be replaced or excluded
before the final analytical sample is established.
--- 
## Project Status

### Current Status

- Initial ITU data exploration completed
- Core analytical indicators identified
- World Bank income classification data acquired and explored
- Candidate country screening methodology established
- 29-country screening pool selected
- Next step: evaluate ITU longitudinal data availability and finalize the analytical sample