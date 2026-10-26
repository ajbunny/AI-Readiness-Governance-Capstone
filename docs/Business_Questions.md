# Business Questions

## Project Object
The objective of this project is to evaluate digital infrasture and connectivity gaps across selected countries to identify where digital investment will have the greatest impact. This analysis hopes to 
help developing nations aware of the gaps they are facing and the most efficent way to eliminate their infrasture/connectivity gaps.

## Analysis focal points:
- Infrastrure availability: whether broadband instrastructure is available
- Access: Whether households have access to the internet
- Adoption: Whether available connectivity is actually being used

## Stakeholder Problem
An internation development organization has limited resources for digital development. The goal is to identify
where investments should ne prioritized and what telecommunications infrasture barries should be addressed.

These focal points will help determine if a country's primary barrier is due to inadequte infrasture or low adaption with existing instrasture 
# Current Scope
| UPDATE |
The current phase focuses exclusively on telecommunications and digital
infrastructure indicators from the ITU DataHub for 2018-2025.

Governance, human capital, affordability, and other AI-readiness dimensions
are outside the scope of the initial analysis and may be incorporated in
future extensions of the project
--------------------------------------------
Initial analysis will focus on telecommunications and digital infrasture indicators from the ITU Datahub

## Core Indicators

The initial analysis will use the following core ITU indicators. 
1. Individuals using the internet
2. Households with internet access at home
3. Population coverage, by mobile network technology
4. Active mobile-broadband subscriptions
5. Fixed-broadband subscriptions

Total population will be included as a supporting variable for normalizing
subscription counts across countries of different population sizes. 

## Analytical Approach

Raw subscription counts will be retained from the ITU data and normalized
using population data to calculate comparable subscription rates.

## Initial Questions
| Business Question | ITU Data Needed |
|---|---|
| Which countries have the largest basic connectivity gaps? | Internet usage %, household internet access, mobile broadband subscriptions, fixed broadband subscriptions |
| Where does infrastuture exist but adoption remains low? | 4G/5G coveage compared with internet use or broadband subscriptions |
| Is the issue that infracture doesn't exist or that it's not being used? | Network coverage vs internet usage/ subscriptions |
| Which countries are most dependent on mobile connectivity? | Mobile broadband vs fixed broadband |

## Decision Questions

The analysis will focus on the following questions:

1. Which countries have the largest basic connectivity gaps?

2. Where does mobile broadband infrastructure exist, but internet adoption
   remains comparatively low?

3. For countries with connectivity gaps, does the evidence suggest that the
   primary barrier is infrastructure availability or adoption?

4. Which countries rely more heavily on mobile broadband compared with fixed
   broadband connectivity?

5. Based on the observed infrastructure and adoption gaps, which countries
   appear to have the greatest digital infrastructure needs?

   ## Refined Research Questions — Experiment B

Following Experiment A, the research focus has been narrowed to better understand the relationship between digital infrastructure availability and actual internet adoption. The original business questions remain relevant, but Experiment B will place greater emphasis on identifying and examining the gaps between network coverage and internet use.

### Primary Research Question

How does the availability of digital infrastructure compare with actual internet adoption across countries, and where are the largest gaps between network coverage and use?

### Supporting Research Questions

1. Which countries have high LTE/WiMAX network coverage but comparatively low internet adoption?
2. How do coverage-use gaps differ across countries, and what patterns emerge when examining electricity access and broadband subscriptions?
3. What relationships can be identified between infrastructure availability and internet adoption, and what additional factors may require investigation?

### Business Objective

The goal is to help Jupiter's Justice distinguish between countries where network infrastructure is limited and countries where network coverage is available but internet adoption remains low. Understanding these differences can help identify where further investigation may be needed before making infrastructure investment decisions.

### Planned Analytical Approach

- Expand the dataset beyond the original 25 countries to include all countries with eligible data from the ITU and World Bank.
- Conduct descriptive and exploratory analysis before additional predictive modeling.
- Calculate the coverage-use gap using LTE/WiMAX coverage (%) minus internet users (%).
- Examine how electricity access and broadband subscriptions relate to differences between coverage and adoption.
- Investigate potential explanations for observed gaps while distinguishing statistical associations from proven causes.

### Research Scope

Experiment B will focus specifically on digital infrastructure availability and internet adoption. The analysis will not attempt to classify countries as AI-ready or not AI-ready. Instead, the objective is to better understand the infrastructure and adoption patterns that may affect countries' ability to benefit from emerging technologies.