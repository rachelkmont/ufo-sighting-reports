# Welcome to UFO Sighting Reports 2015-2019!
### Edmund, Rachel, Rio, and Yuning, DS 5610 Fall 2022 Team 10 

### 01_Preprocessing https://github.com/DSI-EDA-2022/Team10_final/tree/main/01_Preprocessing
- nuforc_reports: the raw data downloaded from https://www.kaggle.com/datasets/rishidamarla/ufo-sightings-approx-100000 
- Missingness_Investigation.Rmd: preliminary analysis of the raw data
- 2019_Census_US_Population_Data_By_State_Lat_Long.csv: US population data in 2019 by state 
- alcohol.csv: data of alcohol consumption by state 
- education.csv: data of education level by state 
- iq.csv: data of iq levels by state
- multiTimeline.csv: google trends data 
- political_affiliations.csv: political affiliation data 
- populations_by_city.csv: city populations 2021
- statepop.csv: state populations 2021
### 02_Data https://github.com/DSI-EDA-2022/Team10_final/tree/main/02_Data
- Clean_UFO_Dataset.Rmd: file used to clean the raw data (nuforc_reports) initially
- JoinWeather.ipynb: file used to join weather data 
### 02_Data >> Clean_Data https://github.com/DSI-EDA-2022/Team10_final/tree/main/02_Data/Clean_Data 
- DataDictionary.pdf: data dictionary of all the variables from the UFO dataset we use and the variables from the joined datasets 
- UFO_and_Weather.csv: final clean data UFO reports joined to weather data 
- shape_1.csv: final clean data UFO reports for shape alluvium plot
- shape_2.csv: final clean data UFO reports for shape interactive Plotly plot
- politics.csv: final clean data UFO reports for political plot
### 03_Main_Findings https://github.com/DSI-EDA-2022/Team10_final/tree/main/03_Main_Findings 
- Frequency and Text Analysis.Rmd: Investigation of UFO report frequency and patterns across time as well as a text analysis from the descriptions of UFO reports
- MADAR.Rmd: Investigation of the patterns of reports from MADAR nodes
- Missingness_and_Data_Validations.Rmd: Investigation of Missing data and data validations
- Weather.Rmd: Investigation of the weather around UFO reports using UFO_and_Weather.csv 
- Shape_and_Political.Rmd: Investigation of shape and political affiliations
- Population_and_Phenomenon.Rmd: Investigation of population effects and cultural patterns with cultural phenomenon

### 04_Deliverables https://github.com/DSI-EDA-2022/Team10_final/tree/main/04_Deliverables
- Team10_EDA22_Final_Report.pdf: Final Report of our Findings
- Team10_EDA22_Final_Presentation.ppt: Final Presentation of our Findings 


## Anticipated Schedule (Subject to Change)
by Wed 10/26: 
* Come up with overarching question
* Dataset(s) 
* General Summary of proposal 

Wed 10/26–Wed 11/02: 
* Validate and clean data 
* Create master CSV file with the ≥ 3 transformed variables 
* Perform preliminary analyses on your own and communicate your thoughts in the Slack to ensure your idea for an analysis does not overlap with another group member's 

Wed 11/02–Wed 11/09:
* Perform actual analyses and figure generation (Each person create 1 basic & we all work together on the more advanced EDA figure)

Tues 11/03 - Friday 11/11:
* Meet via Zoom to discuss findings
* Begin report 

Wed 11/09–Wed 11/16:
* Write the report

Mon 11/28–Friday 12/02:
* Revise & Edit each other's sections of the report
* Make the presentation

Sat 12/03–Sat 12/10
* Revise & Edit each other's sections of the presentation
* Practice the presentation together as a group

Sunday 12/11:
* report & peer review due

Monday 12/12:
* Presentation in class 
