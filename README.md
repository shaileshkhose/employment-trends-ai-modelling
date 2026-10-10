# employment-trends-ai-modelling
Modeling Employment Trends and AI‑Driven White‑Collar Job Displacement in Illinois

# Project Overview
This project investigates employment trends in Illinois and evaluates how advances in artificial intelligence may impact white-collar occupation. By combining employment statistics, occupational characteristics, and demographic data, the team will identify occupations that may not be susceptible to AI-driven disruption.

# Objectives

* Analyze employment trends in Illinois
* Measure AI exposure of white-collar occupations
* Identify occupations at risk of displacement
* Build predictive models for employment changes

# Milestones
* Repository Setup
* Data Acquisition
* Exploratory Data Analysis
* Model Development
* Final Report
* Class Presentation

# Methodology
   1) Collect employment data from BLS.
   2) Extract occupational characteritics from ONET.
   3) Obtain workfore demographics from ACS.
   4) Merge datasets using SOC occupation codes.
   5) Perform exploratory data analyis (EDA).
   6) Develop predictive models.
   7) Evaluate employment trends and AI exposure.

# Research Questions

1) Which occupations are growing or shrinking?
2) Which jobs have high AI exposure?
3) Can AI exposure predict employment decline?

# Recommended Data Sources
## Primary Sources

1) Bureau of Labor Statistics (BLS)
    * Employment trends
    * Occupational Employment Statistics

2) O*NET (Occupational Information Network)

      O*NET is a U.S. Department of Labor database that provides detailed information about occupations. It is often used to study automation and AI exposure because it describes what workers actually do in their jobs. (https://www.onetonline.org/)
    * Job tasks and skills
    * AI/automation susceptibility indicators

4) American Community Survey (ACS)

    ACS is conducted by the U.S. Census Bureau and provides annual demographic and workforce statistics.
    Website: https://www.census.gov/programs-surveys/acs
    * Demographics
    * Income
    * Education
    * Geographic distribution

# How They Fit Together

A strong project workflow could be:

BLS Employment Data

        +
O*NET Occupational Characteristics

        +
ACS Demographic Data

        ↓
Merged Analytical Dataset

        ↓
Model Employment Trends

        ↓
Identify Occupations Most Vulnerable to AI

# Create a reproducible pipeline:

Store each step as separate Python scripts in src/ rather than having everything in notebooks. Professors often appreciate projects that are reproducible and organized like real-world data science projects.

Raw Data

    ↓    
Cleaning Script

    ↓    
Feature Engineering

    ↓    
Model Training

    ↓  
Evaluation

    ↓
Visualizations


# Team Members
1) Casey Hallas
2) Shailesh Khose
3) Jonathan Acheampong
4) Carlos Vera-Esquivel
