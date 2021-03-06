# AirBnb Price Prediction

## Medium Article

https://medium.com/@chaure.v/boston-airbnb-price-prediction-67f65aa54768

## Problem Setting

Since its inception, Airbnb has been a critical market driver in addressing a low-cost lodging problem by investigating the ancillary revenue stream of residents who could not afford their apartment's rent. Airbnb now provides a solid, intermediate public framework for connecting supply and demand in the temporary housing and accommodation market. We wish to explore the underlying facts behind the listings of the various properties inside Boston and try to answer specific issues that could assist both Airbnb and potential owners as Airbnb has grown in popularity. 

## Problem Definition

We plan to investigate it from a distinct perspective to see if there is anything we can do to assist property owners in determining whether to advertise their home and what we can do to help them obtain the highest price, which would benefit both the landlord and Airbnb. This project aims to solve this problem, by using machine learning and data mining techniques to predict the base price for properties in Boston. 

# Dataset
The Dataset used for this project is available on “insideairbnb.com”. 

# Variables

The dataset consists of 74 columns. 

Few important variables: 

* Accommodates: the number of guests the rental can accommodate. 
* Bedrooms: number of bedrooms included in the rental. 
* Bathrooms: number of bathrooms included in the rental. 
* Price: nightly price for the rental. 
* First Review: the date of the first review. 
* Last Review: the date of the most recent review. 
* Review Score Rating: guests can score properties overall from 1 to 5 stars 

# ML Models used
* KNN with Hyperparamter Tuning
* Decision Tree with Hyperparameter Tuning
* Random Forest with Hyperparameter Tuning
* SVR with Hyperparameter Tuning
* Neural Network with Hyperparamter Tuning
* Ridge with Hyperparameter Tuning
* XGB with Hyperparameter Tuning

# Conclusion

The most important features for the price of Airbnb accommodation in Boston are whether the Entire Apt/Home is available or not, Number of bathrooms, Number of people it can 
accommodates with feature weight as 0.20,0.09,0.08 and 0.03 respectively. 
Using XGB model, we are able to predict price with RMSE of 96. 
Few other important features are parking space availability, number of nights the Airbnb is available and host response for predicting the price. 
From project, it can also be concluded that most of the listing of the Boston city are around central Boston. 

Looking at the results of the different questions that we wanted to ask, we found that the In Boston mentioning features or amenities like Availability of entire apartment, Number of bathrooms, Number of apartments can accommodate and Exercise Facilities would certainly influence the price for the property. The parking space, ratings and amenities would certainly have effect as well. So, Using the model and rules of association for features would make a listing stand out from the crowd and would help hosts as well as the Airbnb to predict the best price range for any property in Boston.
