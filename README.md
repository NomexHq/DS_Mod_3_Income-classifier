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
⋅⋅* useless and redundant columns removed ('fnlwgt', 'capital-gain', 'capital-loss', 'relationship')
..* transformation of categorical variables into 1 and 0
..* values that made no meaningful sense were removed
..* in order to cut down the amount of categories in variables, some of the values were removed or merged with larger categories where it was meaningful 
..* outliers were removed based on 3sd principle

## EDA insights
..* Potential issue with class inbalance
[[/Visuals/balance.png|class_balance_check]]  

..* Gender by income distribution
[[/Visuals/Gen_by_income.png|gender_income]]  

..* Marital status by income distribution
[[/Visuals/Mar_by_income.png|mar_income]]  

..* Education by income distribution
[[/Visuals/Edu_by_income.png|edu_income]]  

..* Working sector by income distribution
[[/Visuals/Sector_by_income.pdf|sec_income]]  

..* Difference in age and income distribution by gender . 
[[/Visuals/sex_age.pdf|diff1]]  

..* Difference in education and income distribution by gender  
[[/Visuals/sex_edu.pdf|diff2]]  

## Initial modelling  



