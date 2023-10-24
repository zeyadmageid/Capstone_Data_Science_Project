# 🏆 Capstone_Data_Science_Project

<img width="579" alt="image" src="https://github.com/zeyadmageid/Capstone_Data_Science_Project/assets/52506246/7b486251-68e9-44bf-afef-8bfe029a6824">

## 📖: Summary
This capstone project will ultimately predict if the Space X Falcon 9 first stage will land successfully. Click [here](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/report.pdf) to view the report.

### :dart: Business mission
-  SpaceX launches Falcon 9 rockets at a cost of around $62m. This is considerably cheaper than other providers (which usually cost upwards of $165m), and much of the savings are because SpaceX can land, and then re-use the first stage of the rocket.

-  If we can make predictions on whether the first stage will land, we can determine the cost of a launch, and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## ✍️ Outline
-  [Data Collection using SpaceX's API](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/Lab_1_(_Data_Collection_Api_)_checkpoint.ipynb)
    - Using GET requests to obtain data using the SpaceX API
-  [Web Scraping](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/2_Space_X_Web_scraping_Falcon_9_and_Falcon_Heavy_Launches_Records_from_Wikipedia.ipynb)
-  [Data Wrangling](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/3_Space_X_Data_Wrangling_spacex.ipynb)
    - Using `fill.na()`method to remove NaN values.
    - Using `value_counts()`method to determine the following.
        - Number of launches on each site.
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully
    
-  [Exploratory Data Analysis by SQL](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/4_Space_X_EDA_Using_SQL.ipynb)
    - Using SQL queries to manipulate and evaluate the SpaceX dataset      
-  [Data Visualization](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/5_Space_X_EDA_DataViz_Using_Pandas_and_Matplotlib_SpaceX.ipynb)
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns
-  [Launch Sites Locations Analysis with Folium](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/6_Space_X_Launch_Sites_Locations_Analysis_with_Folium_Interactive_Visual_Analytics.ipy)
    -  Geospatial analytics using Folium

-  [Plotly interactive dashboard](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/7.%20Build%20an%20Interactive%20Dashboard%20with%20Ploty%20Dash%20-%20spacex_dash_app.py)
    -  Creating an interactive dashboard using Plotly Dash

-  [Predictive Analysis](https://github.com/zeyadmageid/Capstone_Data_Science_Project/blob/main/8_SpaceX_Machine_Learning_Prediction.ipynb)
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model
     
## :key: Key Skills Learned/Used:
-    Using data science methodologies to define and formulate a real-world business problem
-    Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
-    Interactive dashboard development with Plotly Dash
-    Interactive map development using Folium
-    Using machine learning to build a predictive model to help a business function more efficiently
-    Structuring and building a data-findings report

## Certificate:
Verify at this [Link](https://www.coursera.org/account/accomplishments/professional-cert/FY9YMA642SUX)
<img width="959" alt="image" src="https://github.com/zeyadmageid/Capstone_Data_Science_Project/assets/52506246/a8bd6523-84f9-412d-8de8-7bce98597ae8">
