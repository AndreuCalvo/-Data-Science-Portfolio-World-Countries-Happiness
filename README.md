# 1. Title:
Analize the main factors why the countries are happy or not and create a model to classificated it

# 2. Problem Description
The happiness is one of the most important factors in the life of the humankind, it's very important to identify the factors than can help to build a better world (a world more happier). Be happy improve other factors in the human life as health, productivity, motivation... 

## 2.1 What is the business or policy problem you are facing?
First, serch the main factors that impact in the countries happiness and create a model to classificate if one country is happy or not.  
## 2.2 Who or what is affected by this problem?
All the countries in the earth are involved in these analisys, it's true that not all the countries are in the happines world data in the 2015,2016,2017,2018 and 2019 datasets
## 2.3 How many of these people/organizations/places/etc. are affected by the problem, and how much are they affected
The happiness affect all the labels of the human life, all the people could be affected for the results of this analisys

# 3. Goals
Create differentes machine learning models applied to these datasets and evaluate its. 
## 3.1. What are your social, policy, or business goals, and what constraints do you have?
We only have data about the interview world hapiness until 2019, it would be very interesting to have more contemporanious information, because in 2019 covid19 appear and it's possible that the values change radicaly


# 4. Data
## 2015, 2016, 2017, 2018, 2019
- Country	Region	
- Happiness Rank	
- Happiness Score	
- Standard Error	
- Economy (GDP per Capita)	
- Family	
- Health (Life Expectancy)	
- Freedom	
- Trust (Government Corruption)	
- Generosity	
- Dystopia Residual	Year	
- Whisker.high	
- Whisker.low	
- Social support
## country_data
- gdp
- sex_ratio
- surface_area
- life_expectancy_male
- unemployment
- imports
- homicide_rate
- currency
- iso2
- employment_services
- employment_industry
- urban_population_growth
- secondary_school_enrollment_female
- employment_agriculture
- capital
- forested_area
- exports
- life_expectancy_female
- post_secondary_enrollment_female
- post_secondary_enrollment_male
- primary_school_enrollment_female
- infant_mortality
- gdp_growth
- threatened_species
- population 
- urban_population
- secondary_school_enrollment_male
- name
- pop_growth
- region
- pop_density
- internet_users
- gdp_per_capita
- fertility
- refugees
- primary_school_enrollment_male
- co2_emissions
- tourists

# 5. Analysis
Univariate analisys: analize al the features identifying the type variable (categorical or numerical)
Transform the data
Merging some values
Identifying the missing values and deciding the missing type (MCAR, MAR, MNAR)
Applying differents techinques to manage the missing values
Select the best features to success in the model implementation
We apply two classification models: Logistic regression and Deccision trees 
Evaluate de models

# 6. Ethical Considerations
This project has an educational porpuse and doesn't exist any ethical consideration to take into consideration
## 6.1 Privacy, Confidentiality, Transparency, Discrimination/Equity and Security
The dataset has been downloaded from Kaggle platform.