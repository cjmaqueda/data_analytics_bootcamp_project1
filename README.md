# data_analytics_bootcamp_project1
Sujin Guo
Eric Franco
Carlos Maqueda

Project Title: Water Quality, Mortality, and Economic Outcomes

We propose to use water quality data reported by the US Environmental Protection Agency to explore water quality data and explore how water quality impacts economic and health outcomes across the US. We will to focus on concentrations of nitrates, lead, mercury, fluoride, chlorine, and arsenic in water measured from 2006-2011. The project will start with an exploratory data analysis of geographic concentrations of these contaminants and how they have changed over time. We will then explore how water contamination impacts mortality data and how economic outcomes and activity impact water quality.


Datasets
-EPA water quality data 
(https://www.epa.gov/dwsixyearreview/six-year-review-3-compliance-monitoring-data-2006-2011)
-geographic description of monitoring stations (https://ofmpub.epa.gov/apex/sfdw/f?p=108:21:::NO:RP,RIR)
-US county level mortality data (https://www.kaggle.com/IHME/us-countylevel-mortality#mort.csv)
-US Census Bureau data on household income

Tasks
-Merge water quality data with detailed data on collection stations
-Merge mortality data by state and county
-Merge household income data
-Exploratory data analysis on water quality data
-Explore relationships between water quality and mortality
-Explore relationships between water quality and household income


Merging the datasets
Merge on the following columns
in nitrate data = "PWSID"
in station tag data "PWS ID"