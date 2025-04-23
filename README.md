# Making Diagnostic Analytics Using Python
## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data analysis](#exploratory-data-analysis)
- [Results](results)
- [Insights and Recommendations](#insights-and-recommendations)
- [Limitations](#limitations)
- [References](#references)
### Project Overview
This data analysisis project focuses on fictional NHS appointments data provided by London School of Economics covering a 30 month periodaiming to find out:  
- if there was enough staffing and resources at the height of Covid-19 Pandemic.
- What the utilisation of the resources was like.
- if it would be beneficial to use additional external data sources e.g X (formerly Twitter) to run the analysis.
Answering these questions would help the NHS budget better and allocate resouces appropriateley.



![appointments_by_service_setting_across_seasons (1)](https://github.com/user-attachments/assets/c5581fee-21be-4829-9288-7477facec047)
### Data source
Below files were provided:
- actual_duration.csv - this contained details of appointments made by patients for exampple, name, date of birth, durations and the number of appointments.
- appointments_regional.csv - Types of appointments made by patients e.g regional information, month of appointmemt, duration,and number of appointments.
- national_categories.xlsx - details of national categories of appointments made by patients for example, regional information, date of appointment, natioanal categories, typr of context and number of appointments.
- metadata_nhs.txt - deatailed infprmation about the dataset.
- tweets.csv - data related to heathcare scrapped from X(formely Twitter).

### Tools Used
Python - For data cleaning, analysis and visualisation.

### Data Cleaning and Preparation
Plese refer to the Jupiter notebook provided.
- Imported necessary libraries.
- Imported the first three files onto a jupiter notbook and loaded them.
- Sense-check the files, find measures of central tendencies, missing values, duplicates and descriptive statistics.

### Exploratory Data Analysis
 An exploration of the data aimed to answer several questions, for example:
 - What is the number of locations, service settings, context types, national categories, and appointment statuses in the data sets?
 - What is the date range of the provided data sets, and which service settings reported the most appointments for a specific period?
 - What is the number of appointments and records per month?
 - What are the top trending hashtags (#) on the supplied Twitter data set and how can this be used in the decision-making process?
 - Was there adequate staff and capacity in the networks?
 - What was the actual utilisation of resources?
 - What insights can be gained by looking at missed appointments?
 - What are the most important patterns visible in the data relating to the use case? 
  - What insights can be gained from the data, and what recommendations can be made to the NHS based on these insights?
 Please refer to the Jupiter Notebook provided for more questions.
EDA involved doing the following:
- Used the datetime module to sort the appointments by date.
- Used value_counts to get total number of appointments in diifferent catergories.
- Used Seaborn to visualize patterns and trends.
- Use the results to draw conclusions, offer insights and recommendations.

### Results
 - General practice had the highest number of appointments across seasons and 
months.
 - Autumn season saw the highest number of patients book appointments. 
 - Walk-in type of appointments were higher than the other types.
 - The utilisation of resources was about 84% so this means that the NHS was within its capacity. 
 - There wasn't enough data to confidently say whether external data sources like X were 
valuable for analysis. 
### Insights and Recommendations
- Resources could be leveraged to help relieve the pressure on the General practices that were recieving high volume of appointments.
- Since autumn season saw the highest number of appointments, NHS could use this information to anticipate high numbers and be better prepared.
- With walk in appointments being the most popular type of appointment, the NHS could find ways for some patients to attend in other ways, say telephone and video appointments and reduce the pressure on staff at the walk-in clinics and departments.
- There was no need to employ more staff since tge NHS was operating within capacity but some staff in less busy areas could be reallocated to busy departments to help their colleagues.
- The use of external data resources like twiiter could be an area for further research since there was no conclusive benefit at the time of analysis.

### Limitations.
There wasn't enough data to confidently say whether external data sources are 
valuable, this is an area that needs more research
  
 ### References
  London School of Economis and Political Science (2024). LSE_DA201_Data Analytics using Python_P2_2024. https://fourthrev.instructure.com/courses/740





 
