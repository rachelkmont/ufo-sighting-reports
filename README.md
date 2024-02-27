# UFO Sighting Reports Analysis (2015-2019)

## Overview
This repository contains the code and data for an exploratory data analysis (EDA) on UFO sighting reports in the United States from 2015 to 2019. The analysis delves into various factors influencing UFO sightings, including weather conditions, political affiliations, cultural phenomena such as sci-fi movie releases, and textual descriptions of sightings.

## Contributors
- **Edmund Hui**
- **Rachel Montgomery**
- **Rio Jia**
- **Yuning Wu**

## Folders

### 01_Preprocessing
- **nuforc_reports**: Raw data downloaded from [Kaggle](https://www.kaggle.com/datasets/rishidamarla/ufo-sightings-approx-100000).
- **Missingness_Investigation.Rmd**: Preliminary analysis of the raw data.
- **2019_Census_US_Population_Data_By_State_Lat_Long.csv**: US population data in 2019 by state.
- **alcohol.csv**: Data of alcohol consumption by state.
- **education.csv**: Data of education level by state.
- **iq.csv**: Data of IQ levels by state.
- **multiTimeline.csv**: Google Trends data.
- **political_affiliations.csv**: Political affiliation data.
- **populations_by_city.csv**: City populations in 2021.
- **statepop.csv**: State populations in 2021.

### 02_Data
- **Clean_UFO_Dataset.Rmd**: File used to clean the raw data (`nuforc_reports`) initially.
- **JoinWeather.ipynb**: File used to join weather data.

### 02_Data >> Clean_Data
- **DataDictionary.pdf**: Data dictionary of all the variables from the UFO dataset used and the variables from the joined datasets.
- **UFO_and_Weather.csv**: Final clean data of UFO reports joined to weather data.
- **shape_1.csv**: Final clean data of UFO reports for shape alluvium plot.
- **shape_2.csv**: Final clean data of UFO reports for shape interactive Plotly plot.
- **politics.csv**: Final clean data of UFO reports for political plot.

### 03_Main_Findings
- **Frequency and Text Analysis.Rmd**: Investigation of UFO report frequency and patterns across time, as well as a text analysis from the descriptions of UFO reports.
- **MADAR.Rmd**: Investigation of the patterns of reports from MADAR nodes.
- **Missingness_and_Data_Validations.Rmd**: Investigation of missing data and data validations.
- **Weather.Rmd**: Investigation of the weather around UFO reports using `UFO_and_Weather.csv`.
- **Shape_and_Political.Rmd**: Investigation of shape and political affiliations.
- **Population_and_Phenomenon.Rmd**: Investigation of population effects and cultural patterns with cultural phenomena.

### 04_Deliverables
- **Team10_EDA22_Final_Report.pdf**: Final report of our findings.
- **Team10_EDA22_Final_Presentation.pdf**: Final presentation of our findings.
