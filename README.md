# MSc Statistics Data Challenge 2017 
# Forecasting and mitigating epidemic disasters 	

#### Background
The [West African Ebola virus epidemic](http://apps.who.int/ebola/our-work/achievements) was the most widespread outbreak of Ebola virus disease in history, with disastrous on local populations, and entire countries. Other recent examples of major infectious disease outbreaks are the [2015-2016 Zika epidemic](http://www.who.int/emergencies/zika-virus/en/), and the [MERS-coronavirus epidemic](http://www.who.int/emergencies/mers-cov/en/).

In response, the World Health Organization is characterising the risk of member states to infectious disease threads. The primary aims are to prioritize resources for epidemic prevention, early detection, and control by evaluating areas that are most in need of resources as well as predicting the impact of infectious disease threats  

#### Primary objective
The WHO's epidemic disasters data set contains a comprehensive record of the number of epidemic outbreaks by year and country. For the 2017 Imperial/WHO Data Challenge, outbreak data are available from 184 countries for 5 years, 2010 to 2015.

Your primary objective is to predict the number of epidemic disasters in the same 184 countries in 2016.  

#### Why we care
Scientifically, we are interested in identifying and understanding the interplay of factors that are predictive of epidemic disasters at a country level. 

#### Open data for the Data Challenge
To model vulnerability, the WHO is collecting data on a countries' capacity to respond to major public health crises. The IHR data set contains records of 11 capacity indicators per country for 6 years, 2010 to 2016, which could be used to inform a predictive model of epidemic disasters in 2016.     

Some entries are missing, but this is only the first challenge. 

Public institutions are now making large data sets open access, that describe the wealth and health of countries. There is no reason why you should limit yourself to the IHR data set in predicting country-level risk of major epidemic disease outbreaks. For this year's Data Challenge, we prepared for you several data sets, bringing the number of potential predictors close to 500. This is where the challenge starts to be fun.  

#### How to start
* Get the data, type in `R`:
```r
devtools:::install_github("olli0601/PANGEA.HIV.sim")
?emstrain
```    
* Explore the References tab above to get a feel for all available data sets.
* Read the survival guide.
* Think before you type.

#### How to make a submission
