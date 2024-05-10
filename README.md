# [Project 1: ECOPREDICT- Modeling CO2 Emissions for sustainable solutions](https://github.com/jahnavipotu/data-analyst-portfolio/blob/main/CO2_Prediction%201.ipynb)
The focus of the project is to analyze the predominant environmental pollutant, CO2, and explore its underlying causes and sources and to develop a robust machine learning model to assist stakeholders in mitigating its impact. Created a predictive model that empowers automobile designers to forecast CO2 emissions resulting from feature modifications. Furthermore, provided consumers with insights into the environmental consequences of their vehicle choices. Data is sourced from U.S. gov Energy Information open data and Open Canada data via API Pull. 

Identified the greenhouse gas that will be the major cause of concern for global warming. Despite N2O and CH4 having higher heat-trapping capacities, CO2’s vast emission volumes make it the primary focus in combating global warming. 

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/3.png" alt="Dashboard" width="600">

Overall in the US, the Top Contributor to CO2 Emissions is the “Transportation Sector", followed closely by the "Electric Power Sector".

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/1.png" alt="Dashboard" width="600">

In the transportation sector, especially automobiles that contribute to CO2 emissions, developed a predictive model that will take in inputs such as vehicle Mileage, model, brand, Engine Size, number of cylinders, type of fuel used and will return a predicted output for the CO2 emissions. 

After modeling various machine learning techniques, it was observed that the Random Forest regressor provided the least error prone predictions on the test data. However, it exhibited signs of overfitting. Conversely, both Gradient Boosting and Bi-directional LSTM models demonstrated better generalization to the test data. When comparing Gradient Boosting and Bi-directional LSTM, although Gradient Boosting yielded slightly higher error rates, it was preferred due to its interpretability. Fine-tuned the Gradient boost model to improve the performance. After hyperparameter tuning, the model's error rate on the test data set was reduced from 18.24 to 9.70, which is a significant improvement.

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/2.png" alt="Dashboard" width="600">

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/7.png" alt="Dashboard" width="600">

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/6.png" alt="Dashboard" width="600">

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/4.png" alt="Dashboard" width="600">

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/5.png" alt="Dashboard" width="600">

This predictive model, as showcased in the provided interface, can be highly beneficial for vehicle manufacturers during the initial stages of ideation and design.By embedding this predictive model into the early stages of vehicle design and development, manufacturers not only enhance their capacity to produce environmentally friendly vehicles but also streamline their design processes and align closely with global trends toward emission reductions. 


# Project 2: Customer Segmentation for a laundry startup using clustering in Tableau
Performed Segmentation for a laundry-pickup services startup with stores in 150 locations in U.S, using variables marketing spend, revenue generated and population using clustering. Identified the top 3 stores in their 10 new stores that have the best potential to generate more revenue with less marketing spend for the company to invest more funds into marketing.

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/Screenshot%20(33).png" alt="Dashboard" width="600">

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/Screenshot%20(34).png" alt="Dashboard" width="600">


# Project 3: Seattle Airbnb Open data Visualization Using Tableau 
Created effective visualizations and dashboard in Tableau using Seattle Airbnb Open data. Answered some analytical questions like Which Zipcode charges the most on average?, Which times of year is best to rent airbnbs?, Average Price Per Bedroom, Distinct Count of Bedroom Listings.

<img src="https://github.com/jahnavipotu/data-analyst-portfolio/raw/main/Screenshot%20(19).png" alt="Dashboard" width="600">


# [Project 4: House Sales in King County, USA: Data Analysis with Python project](https://github.com/jahnavipotu/data-analyst-portfolio/blob/main/PythonDataAnalysisProject%20(1).ipynb)
Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. Prediction of the market price of a house given a set of features. Analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. The dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It was taken from Kaggle.

Importing Data, Data Wrangling, Exploratory Data Analysis, Model Development, Model Evaluation and Refinement

Statistical Models used: Multiple Linear Regression, Polynomial Regression, Ridge Regression

Python Libraries used: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn.
