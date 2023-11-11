# Maternal-Smoking-EDA-Prediction-Analysis
An Exploratory Data Analysis on Maternal Smoking dataset and Prediction Analysis using select algorithms or models that could be used to to identify women at high risk of preterm birth.
<h1 align="center"><code style="background-color: #8c182b;color:white;">Exploratory Data Analysis and Prediction Analysis on Maternal Smoking</code></h1> 
![Alt text](https://github.com/AJAgyeman/Maternal-Smoking-EDA-Prediction-Analysis/blob/9ed6e684187fffa49a17186ac616ec5c3fcb7370/babyrauchen.png)

<h3><code style="background:#8c182b;color:white">Introduction</code></h3> 

Maternal smoking during pregnancy has been shown to have a negative impact on the gestation period, or the length of time a woman carries a pregnancy. Studies have consistently found that maternal smoking is associated with a shorter gestational period, meaning that the baby is born earlier than expected.
Smoking during pregnancy can also lead to an increased risk of preterm birth, which is defined as delivery before 37 weeks (270 days) of gestation. Preterm birth is a major cause of infant morbidity and mortality, and is associated with a range of long-term health problems.

Overall, it is recommended that women avoid smoking during pregnancy in order to promote a healthy gestational period and reduce the risk of adverse health outcomes for their baby.

This dataset is a subset of the Child Health and Development Study (CHDS), a long-term study conducted by the Public Health Institute in California that began in 1959 and followed a cohort of over 15,000 pregnant women and their offspring for several decades. The subset includes data on maternal smoking and other factors collected during the pregnancy, as well as birth outcomes such as birth weight and gestation. 

<h3><code style="background:#8c182b;color:white">Problem Statement</code></h3> 

The aim of this analysis is to explore if there is a relationship between maternal smoking during pregnancy and preterm birth, while considering other variables such as maternal BMI, age, race, income, marital status, parity, and birth weight.

The analysis will investigate the prevalence of maternal smoking during pregnancy in the dataset and compare the risk of preterm birth between smokers and non-smokers. It will also examine the relationship between maternal BMI and preterm birth, and whether there are differences in preterm birth rates based on maternal age, race, income, marital status, and parity.

Finally, I will find out if a predictive model can be developed to identify women at high risk of preterm birth based on maternal smoking, BMI, age, race, income, marital status, parity, and birth weight.

<h3><code style="background:#8c182b;color:white">Code Book</code></h3> 

| code|description | 
| :----------- | :----------- |
| gestation      | gestational age of the baby/babies in days (above of below normal gestation period-270 days |
| babys_weight   | weight of the baby/babies in ounces        |
| parity      | parity of the mother (whether first born or subsequent birth)       |
| mothers_education     | level of education of the mother       |
| mothers_height   | height of the mother in inches        |
| mothers_weight      | weight of the mother in pounds       |
| mothers_race   | race/ethnicity of the mother        |
| fathers_age      | age of the father in years       |
| fathers_education   | level of education of the father        |
| fathers_height      | height of the father in inche       |
| fathers_weight   | weight of the father in pounds        |
| fathers_race      | race/ethnicity of the father       |
| marital_status   | marital status of the mother        |
| total_income      | total family income       |
| mothers_age|age of the mother in years||
| smoking_status   | smoking status of the mother during pregnancy (smokes or not)        |
| quit_time      | time at which the mother quit smoking during pregnancy      |
| num_cigs_taken   | number of cigarettes smoked per day by the mother during pregnancy        |
