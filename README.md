# City House Rent Estimator
## Table of Content
  * [Demo](#demo)
  * [Motivation](#motivation)
  * [Overview](#overview)
  * [Data](#data)
  * [Technical Aspect](#technical-aspect)
  * [Blog](#blog)
  * [To do](#to-do)
  * [Feature Request](#feature-request)
  * [Connect](#connect)
## Demo
Link: [https://house-rent-estimate-app.herokuapp.com/](https://house-rent-estimate-app.herokuapp.com/)
[![](https://github.com/sayeed245/house-rent-estimator/blob/main/house%20rent%20estimator.png)](https://house-rent-estimate-app.herokuapp.com/)
## Motivation
After completing 3 machine learning projects, I wanted to do an end to end project to really understand the ML workflow outside the professional setup by myself. I wanted to make a project which would be relevant to our use.  Keeping in mind all the articles that I have read since I started to learn ML and my initial web research, I decided to create a House Rent Estimator app. 
## Overview
To estimate the rent of a house by giving inputs(City,numnber of bathrooms,number of parking spaces,floor preference,Have/not have pets,Furnished/Not furnished) to the app
## Data
I was aware that finding an appropriate dataset for my project will be a challenge. I went on to find a dataset that had data on house rent of five cities of Brazil from Kaggle. I considered learning scraping data from web when I did not get any other producible dataset which will be relevant in the Indian setup. Again, with my research, I was not surprised to know that data scraping has its own world and will take me time to master. So, I decided to convert the dataset from Brazil into an Indian version. 
The challenge in converting the dataset to an Indian version was to understand the conversion rate that I should use to convert Brazilian currency (Brazilian Real=₹14.xx) into an acceptable rent price that would be a fit in the Indian scenario. After some hit and trial and analysis of the price I converted the rent to ₹ which seemed to be okay.
The next decision to make was to choose the cities to replace the five Brazilian cities. I naturally went forward to choose the metro cities: Delhi, Mumbai, Kolkata, Chennai and Bangalore. I looked at the rent distributions and made a decision to replace each city. With the data I had, I was really skeptical to keep Mumbai as a city. The rent amounts did not even closely resonate with the real market values. So, I have replaced Mumbai with Pune.

## Technical Aspect
[Estimator Notebook](https://github.com/sayeed245/house-rent-estimator/blob/main/estimator.ipynb)

   - Performed a simple RandomForestRegressor to predict the rent
   - Converted the model into pickle form

[App](https://github.com/sayeed245/house-rent-estimator/blob/main/app.py)
   - Used Streamlit to create app
   
[Procfile](https://github.com/sayeed245/house-rent-estimator/blob/main/Procfile)
[Setup](https://github.com/sayeed245/house-rent-estimator/blob/main/setup.sh)
    
   - Deployed the app in Heroku

## Blog
A detailed blog on how I created this app can be found [here](https://github.com/sayeed245/house-rent-estimator/blob/main/House%20Rent%20Estimator%20blog.pdf).

## To do
To make the same application with Flask and deploy in AWS.
   
## Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/sayeed245/Fraud-Detection/issues/new) by including your search query and the expected result.

## Connect
#### LinkedIn: [https://www.linkedin.com/in/sayeed-mohammad-83b691108/](https://www.linkedin.com/in/sayeed-mohammad-83b691108/)
#### Twitter: [https://twitter.com/6SAYEED](https://twitter.com/6SAYEED)
#### Tableau Public: [https://public.tableau.com/profile/sayeed.mohammad#!/](https://public.tableau.com/profile/sayeed.mohammad#!/)

