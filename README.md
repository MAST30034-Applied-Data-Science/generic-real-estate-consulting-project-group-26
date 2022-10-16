# Generic Real Estate Consulting Project
Group Name:  
- Group 26

# Group Members:  
- Yihan Bao (1174241)
- Shunran Wang (1056590)
- Chaoran Xu (1217537)
- Hairong Xu (1074211)
- Xiangyi Huang (1132626)

# Research goal 
The main objective of our project is to advice stakeholders where and what to invest for a higher profit.

# Timeline 
Some annual data is collected for predicting feature year.  
- Income is collected from 2005 to 2018.
- Population is collected from 2000 to 2021.
- Rental price is collected from 2014 to 2018

# Repository Directory
- `notebooks`: 
  - `Summary Notebook.ipynb` includes the introduction and analysis of each step in this project. It also includes solution ideas for each problem.  
  - `Data Scraping` : This folder includes the files which collect data by web scraping. 
  - `Feature Engineering` : This folder mainly consider creating the useful attributes for project and merge dataset for solving question. 
  - `Preprocessing` : This folder mainly preprocesses the data, extracts useful attribute from original dataset. The clean data will be stored in `data/curated` folder. 
  - `Visualisation` : This folder includes files which the map the relative data on Victoria map.
  - `Q1 Data Analysis.ipynb`, `Q2 Predict Growth Rate.ipynb`, `Q3 Liveability and affordability.ipynb` represent the solution algorithm for Question 1, 2, 3 respectively.  
  
- `data`: contains raw and curated data
- `plots`: contains all plot which created in all files. 

# Requirements
Some external package needs to be pip installed to perform some functionalities, see `requirements.txt`

# Reference and Data Sources
- Property: www.domain.com.au
- Median rental price: https://www.dhhs.vic.gov.au/moving-annual-rents-suburb-march-quarter-2021-excel
- SA2 District Boundaries (ABS) : https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.001July%202016
- Total population by SA2 Districts : https://www.abs.gov.au/statistics/people/population/regional-population/2021#data-download
- Income by SA2 Districts 05-10 : https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/6524.0.55.0022005-06%20to%202010-11?OpenDocument
- Income by SA2 Districts 11-15 : https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/6524.0.55.0022011-2015?OpenDocument
- Income by SA2 Districts	14-18 : https://www.abs.gov.au/statistics/labour/earnings-and-working-conditions/personal-income-australia/2014-15-2018-19#data-download
- Hospital data: https://springernature.figshare.com/ndownloader/files/15591434
- Entertainment Facility data: https://discover.data.vic.gov.au/dataset/e6db797e-3801-4cfa-bf02-82350d0f722d/resource/bfff5fff-9c74-4671-8396-43f793613b70/download/srv_ifmd_all-facilities.xlsx
- Population Forecasts by SA2 Districts : https://www.gen-agedcaredata.gov.au/Resources/Access-data/2019/September/Population-projections,-2017-(base)-to-2032-for-al
- VIC Suburb/Locality Boundaries - Geoscape Administrative Boundaries : https://data.gov.au/data/dataset/vic-suburb-locality-boundaries-geoscape-administrative-boundaries
- Crime data: https://www.crimestatistics.vic.gov.au/
- School locations : https://discover.data.vic.gov.au/dataset/school-locations-2022
- API: openrouteservice.org by HeiGIT | Map data OpenStreetMap contributors
