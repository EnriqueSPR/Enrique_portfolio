# Enrique_portfolio
A summary of my data science projects

# [Project 1: Data Science Salary Estimator](https://github.com/EnriqueSPR/ds_salary_project)

* Created a tool that estimates data science salaries to help data scientists negotiate their income when they get a job.

* Scraped over 1000 job descriptions from glassdoor using python and selenium.

* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.

* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.

* Built a client facing API using flask

<img src="figures/bar_subplots_ax1_ax2.png" width="600"/>

# [Project 2: Data Science Price Estimator from Houses in Madrid](https://github.com/EnriqueSPR/house_pricing_madrid)

* Created a tool that estimates prices from Madrid houses which can aid flat owners as well as people looking for a house to get an idea of the Real State Market in Madrid.

* Performed data cleaning steps and removed outliers.

* Exploratory Data Analyses shed light into the most important parameters driving house prices in Spain.These parameters were chosen in the model building process.

* Optimized Linear, Decission Tree, and Random Forest Regressors using GridsearchCV to reach the best model.

* Built a client facing API using flask.

<img src="figures/random_forest_data.png" width="400"/>

<img src="figures/Prediction_Tool_Screenshot.png" width="400"/>

# [Project 3: Data Science Rental Estimator from Houses in Madrid](https://github.com/EnriqueSPR/house_renting_madrid)

* Created a tool that estimates rental prices from Madrid houses which can aid flat owners as well as people looking for a house to get an idea of the Real State Market in Madrid.

* Scraped over 2000 house rent information from https://www.pisos.com/ using python and the beautifulsoup library.

* Performed data cleaning steps and removed outliers.

* Exploratory Data Analyses shed light into the most important parameters driving house prices in Spain. These parameters were chosen in the model building process.

* Optimized Linear, Lasso, Decission Tree, Random Forest, Support Vector Regressors using GridsearchCV to find the best model.

* Wrote a python flask server that uses the saved model to serve http requests.

* Built a website in html, css and javascript that allows user to predict rental prices in Madrid.

<img src="figures/hist_boxcox.png" width="600"/>

<img src="figures/corr.png" width="500"/>

# [Project 4: tennis_match_predictor](https://github.com/EnriqueSPR/tennis_match_predictor)

* The goal of this project was to create an algorithm using supervised machine learning to predict the outcome of tennis matches by taking in account information from the players form before the match.

* I scrapped the data from ATP tournaments, matches and players from 1999 to 2020.

* I performed data cleaning steps and feature engineering to create information of the players form at the moment of the upcoming match.

* Exploratory data analyses were carried out to get insight into the features correlation and distribution. This allowed to select the most relevant features for the model.

* I tested diferent algorithms capable of working on this classification problem:

  * Linear Algorithms: Logistic Regression (LR) and Linear Discriminant Analysis (LDA).
  * Nonlinear Algorithms: Classification and Regression Trees (CART), Support Vector Machines (SVM), Gaussian Naive Bayes (NB) and k-Nearest Neighbors (KNN).
  
* Linear Regression models preformed better in this case, and were chosen for further tunning. 


<img src="figures/alg_comparisson.png" width="300"/>    <img src="figures/Model_Performance.png" width="200"/>



# [Project 5: Covid EDA project](https://github.com/EnriqueSPR/Covid_EDA_Project)

In this notebook I focused on analyzing covid data in an effort to better understand the main factors that drive the spread of this virus.

Below I include few highlight figures.

* Plots showing the number of cases per million and the number of tests per 1000 reported in each continent daily:

<img src="figures/lines_cases_per_milllion_continents.png" width="300"/>   <img src="figures/new_tests_per_1000_continents.png" width="300"/>

* Plots showing the top 5 countries affected in the world by cumulative cases and deaths every 2 weeks:

<img src="figures/cumulative_cases_2W_top5.png" width="300"/>   <img src="figures/cumulative_deaths_2W_top5.png" width="300"/>

* Plots showing the death rates, the percentage of population older than 70 and the testing rates by country:

<img src="figures/perc_deaths_country.png" width="300"/><img src="figures/population_aged70_country.png" width="300"/><img src="figures/test_rates_country.png" width="300"/> 

* Screenshots of the interactive plots generated with Bokeh and Plotly:

<img src="figures/Total_Deaths_Per_Million.png" width="600"/>


<img src="figures/interactive_plot_cases_deaths_px.png" width="500"/>

# [Project 6: Redwine Quality Predictor](https://github.com/EnriqueSPR/red_wine_quality)

Supervised Multi-classification ML problem -> Predicting wine quality

In this project we will tackle a multi-classification problem using supervised ML on a well known dataset about red wine quality. See here. This dataset contains quality parameters for 1596 red-wines, which we can use to build a model that predicts red wine quality (Classifies it on a scale from 0 to 5).

Following analyses of feature distribution and data prepocessing, several classification models were trained and their performance assessed.
For this particular case the Support Vector Classification(SCV) algorithm show to perdorm best.
Below are some images associated to the evaluation of the SVC model against the test set.

  * Confusion Matrix Diagram:
  
 <img src="figures/matshow.png" width="200"/> 
 
  * Plot bar showing the feature importance and the correlation of each attribute with the target:
  
 <img src="figures/importance_vs_corr.png" height="250" width="450"/> 
 
  * Plots of the Receiver Operating Characteristic(ROC) curves for classes 2 and 3:
  
 <img src="figures/ROC.png" width="250"/>  

