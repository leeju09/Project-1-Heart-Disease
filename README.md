# Cardiovascular Disease(CVD) Death rate analysis. 
Analysis of geographical distribution of the CVD death rate of all the counties in the United States of America. 

## Project Collaborators 
Chelsea Cullen,Meredith Walter,Julia Lee,Walgama Jayasekara,
 
## Background

CVD disease (CVD) is one of the most serious health issues and leading cause of sudden death in the worldwide. 
It is a common issue in both developed countries and developing countries. 
Risk factors for the CVD basically categorize demographic, socioeconomic, behavioral, environmental, and physiological factors.

But there may be some other factors that matter.
There for it is very important to gather and analyze CVD death information  to make any decision on minimizing CVD death rates.

[source: --World Health Organization (WHO)--](https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds))

## Scope of the project 
 
In this project analysis is limited to the counties only in Unites Sates of America (USA).
Further analysis is limited to the demographic risk factor among various risk factors associated with the CVD death rate. 

## Data source
- [catalog.data.gov :Published by U.S. Department of Health & Human Services](https://catalog.data.gov/dataset/national-health-and-nutrition-examination-survey-nhanes-national-cardiovascular-disease-su)
- [American Lung Association](lung.org/research)

## Area of analysis
- Geographic distribution of the CVD death rate.
- Effect of the smoking behavior to the CVD death rate  
- Distribution of Heart disease among ethnicities.
- Distribution of Heart disease among gender groups.

## Folder structure
- All the source code file (jupyter notebook) available at the root level.
- Resources folder: This folder contains all the resources data file. 
- Project Proposal : This folder contain the project proposal.
- Outputs : This folder contains all the graphs. 
- Summary : final presentation with the conclusion.

## Key analysis 
- [Top and bottom five counties compared to the country average CVD death rate.](Outputs/wa_top_bottom_counties.png)
- [Geographic distribution of the top and bottom five counties](Outputs/top_bottom_five_map.png)
- [Region CVD death rates compare to the country rate. ](Outputs/wa_region_rates.png)
- [States distribution of the CVD death rate](Outputs/states1.png)
- [Ethnicity distribution](Outputs/ethnicity1.png)
- [National CVD death rate by ethnicity](Outputs/ethnicity2.png)
- [National CVD death rate by gender.](Outputs/gender.png)
- [County CVD death rate of the Minnesota compared to the states average. ](Outputs/states2.png)
- [Geographic distribution of the CVD death rate of Minnesota state. ](Outputs/states4.png)
- [Correlation between smoking and CVD death rate ](Outputs/wa_smoking_vs_death.png)
   
## Details of the analysis codes (jupyter notebooks)
- [Heartdisease.ipynb: Codes related to the data cleating process.](Heartdisease.ipynb)
- [geographic_CVD.ipynb : Codes related to states geographic analysis and the correlation of the smoking death rate and CVD death rates.](geographic_CVD.ipynb)  
- [Julia-Ethnicity.ipynb : Codes related to the ethnicity distribution of the CVD death rate.](Julia-Ethnicity.ipynb) 
- [states_breakdown.ipynb : codes related to the Minnesota states CVD death  rate analysis.]([states_breakdown.ipynb) 
- [Mer.ipynb : Codes related to the gender analysis of the CVD deat rate.](Mer.ipynb)

## Summary of the analysis
- Higher CVD death rates can be seen in the south regions of the country having above the country average.
- CVD death rate of some counties in southern era is more than the double as country average.
- There is a notable increase in CVD mortality for men in the USA.
- Black ethnicity  have an higher mortality rate than other ethnic groups while Asian having low rate
- There is a positive relationship between smoking rate and the CVD death rate.
- CVD death rate of Minnesota fell top lowest among the states.
- Western side of Minnesota is where the top 2 areas from cvd death occurred.

[Summary Report](Summary/SummaryoftheStudy.docx)

## Next  stage 
Seeing the summary of the analysis it is noticeable that the southern area of the country having higher CVD death rate.

And higher CVD death rate for male.

As a next step, need a deep dive on other factors like socioeconomic, behavioral, environmental, and physiological factors that directly to CVD death rate of that south regions area. 
