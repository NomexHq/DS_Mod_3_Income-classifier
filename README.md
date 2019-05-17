# DS_Mod_3_Income_classifier
Project attmepts to build an income level clasification model by applying various classification algorithms.  

## Task
Predicting income level (below or above 50K / year) based on various socio-economic attributes.  

## Data
The dataset is taken from UCI machine learning repository.  
Extraction was done from the 1994 Census database.  

**Target Variable:**  
income level >50K and <=50K

**Attributes:**  
age, workclass, fnlwgt, education, education-num, marital-status, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country

## Some of the data cleaning operations performed:
* useless and redundant columns removed ('fnlwgt', 'capital-gain', 'capital-loss', 'relationship')
* transformation of categorical variables into 1 and 0
* values that made no meaningful sense were removed
* in order to cut down the amount of categories in variables, some of the values were removed or merged with larger categories where it was meaningful 
* outliers were removed based on 3sd principle

## EDA insights
* Potential issue with class inbalance  
![char1](Visuals/balance.png)<br>

* Gender by income distribution  
![char2](Visuals/Gen_by_income.png)<br>

* Marital status by income distribution
![char3](Visuals/Mar_by_income.png)<br> 

* Education by income distribution
![char4](Visuals/Edu_by_income.png)<br> 

* Working sector by income distribution
![char5](Visuals/Sector_by_income.png)<br> 

* Difference in age and income distribution by gender  
![char6](Visuals/sex_age.png)<br>

* Difference in education and income distribution by gender  
![char7](Visuals/sex_edu.png)<br>

## Initial modelling  


