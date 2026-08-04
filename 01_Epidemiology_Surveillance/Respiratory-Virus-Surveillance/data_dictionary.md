# Data Dictionary

## Project

Multi-Pathogen Respiratory Virus Surveillance

## Data Source

CDC Respiratory Virus Hospitalization Surveillance Network (RESP-NET)

## Purpose

This document records the variables used in the analysis, their definitions, data types, and any transformations applied during data preparation.

## Variables

| Variable | Description | Data Type | Planned Use |
|---|---|---|---|
| pathogen | Respiratory virus reported, including COVID-19, influenza, or RSV | Categorical | Compare hospitalization patterns across pathogens |
| week_ending_date | Final date of the surveillance week | Date | Weekly trend analysis |
| season | Respiratory-virus surveillance season | Categorical | Seasonal comparisons |
| age_group | Reported patient age category | Categorical | Age-specific rate analysis |
| sex | Reported sex category | Categorical | Demographic comparisons |
| race_ethnicity | Reported race and ethnicity category | Categorical | Health-disparity analysis |
| surveillance_site | RESP-NET geographic surveillance location | Categorical | Geographic comparisons |
| hospitalization_rate | Reported hospitalization rate | Numeric | Primary surveillance outcome |
| population_denominator | Population used to calculate the rate, when available | Numeric | Rate validation and interpretation |

## Data-Quality Checks

The following checks will be performed:

- Confirm date fields are formatted correctly
- Identify duplicate records
- Quantify missing values
- Review suppressed or unreliable estimates
- Confirm hospitalization-rate units
- Examine unexpected category labels
- Validate weekly and seasonal ordering
- Document all exclusions and transformations

## Notes

Variable names and definitions will be updated after reviewing the downloaded dataset and official CDC metadata.
