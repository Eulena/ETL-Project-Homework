## Submitted by: Monica Zulueta-Linsangan

# ETL Project (Homework)- TOPIC

## Content
This dataset includes a record for every federal emergencies or disasters declared by the President of the United States from 1953 to present year.

## Why this topic?
* QUESTION: From 1953, which United States President declared the highest number of Federal Emergencies and Disasters? 
* ANSWER: George W. Bush

![final_app_part4.png](Images/Disaster_Count.PNG)

## Prerequisites
* Jupyter Notebook (pandas)
* Psycopg2
* Sqlalchemy
* sqlalchemy.ext.declarative
* sqlalchemy_utils


## EXTRACTION (Data Sources)
* Extract CSVs into DataFrames
FEMA - `https://www.fema.gov/media-library/assets/documents/28318`(DisasterDeclarationsSummaries.csv)
LIBRARY OF CONGRESS - `https://www.loc.gov/rr/print/list/057_chron.html`(Presidents.csv)
(Please see file Disasters_declared.ipynb)


## TRANSFORMATION: (Data Cleanup & Analysis)
* Merge dataframes then sort by Pres_Id
* Sort data by Declaration Number
* Summarize Data using value_counts to show count of disasters declared by each President
* Rearrange columns in meaningful order
* Rename the column headers
(Please see file Disasters_declared.ipynb)


## LOAD:
* Create Database Connection to PostgreSQL
* Load data to PostgreSQL Database (relational)
(Please see file Disasters_declared.ipynb)


![final_app_part4.png](Images/LOAD_disaster_db.PNG)




