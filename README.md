# Vaccine_Prediction
Classification Problem

# Overview

- Can you predict whether people got H1N1 and seasonal flu vaccines using information they shared about their backgrounds, opinions, and health behaviors? In this challenge, we will take a look at vaccination, a key public health measure used to fight infectious diseases. Vaccines provide immunization for individuals, and enough immunization in a community can further reduce the spread of diseases through "herd immunity."

- As of the launch of this competition, vaccines for the COVID-19 virus are still under development and not yet available. The competition will instead revisit the public health response to a different recent major respiratory disease pandemic. Beginning in spring 2009, a pandemic caused by the H1N1 influenza virus, colloquially named "swine flu," swept across the world. Researchers estimate that in the first year, it was responsible for between 151,000 to 575,000 deaths globally.

- A vaccine for the H1N1 flu virus became publicly available in October 2009. In late 2009 and early 2010, the United States conducted the National 2009 H1N1 Flu Survey. This phone survey asked respondents whether they had received the H1N1 and seasonal flu vaccines, in conjunction with questions about themselves. These additional questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission. A better understanding of how these characteristics are associated with personal vaccination patterns can provide guidance for future public health efforts.

- Data is provided courtesy of the United States National Center for Health Statistics. U.S. Department of Health and Human Services (DHHS). National Center for Health Statistics. The National 2009 H1N1 Flu Survey. Hyattsville, MD: Centers for Disease Control and Prevention, 2012. Images courtesy of the U.S. Navy and the Fort Meade Public Affairs Office via Flickr under the CC BY 2.0 license

## Problem Definition

Goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines. Specifically, we have to be predicting two probabilities: 
-  h1n1_vaccine and 
- seasonal_vaccine.

## Conclusion
<h2 style="color:green"> Using SMOTE Technique XGBoost Model with hypertune is best model with 86% AUC to predict the person is having h1n1 Vaccine and Seasonal Vaccine
