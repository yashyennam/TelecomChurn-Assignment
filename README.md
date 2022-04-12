# TelecomChurn-Assignment

# Problem Statement

In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, your task in this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

- It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.

- It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A ML Model is required to predict telecom churn.
- The Model was build using different algorithms Logistics Regression, Random Forest and XGBoost and was further tuned using hyperparameter tuning.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- arpu_diff is the avg revenue per user, if the arpu is less for any customer there can be a possibility for customer to churn. The company can provide special offers to retain the customer which inturn will also increase the arpu.
- total recharge amt for any customer is less then the customer is most likely to churn. Company can offer special discounts & offers to attract the customer
last recharge days should be low depending on the recharge validity too for a customer to not churn . The team should keep a note of this and provide them with more talk time offers if it is high
- same goes for last data recharge too, it should also be less and if not then provide with offers like discount on OTT platforms
if the values in total incoming & outgoing diff for local as well as roaming drops it can signify churn, may provide with better STD,ISD charges
the aon- age on network can be a a sign of loyalty the more the better, we should not lose long term customers & retain by offering benifits

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
 
- numpy - version 1.19.5
- pandas - version 1.1.5
- matplotlib - version 3.2.2
- seaborn - version 0.11.2
- sklearn - version 0.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [this tutorial](https://www.Upgrad.com).

## Contact
Created by [@yashyennam] and [@IndrashisChatterjee] - feel free to contact me!
