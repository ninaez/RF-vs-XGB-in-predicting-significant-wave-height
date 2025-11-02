# Comparison of Gradient Boosting and Random Forest in Predicting Significant Wave Height
This repository contains the files for my project (college thesis) titled "Comparison of Gradient Boosting and Random Forest in Predicting Significant Wave Height". This project compares some aspects in random forest and gradient boosting (XGBoost) when predicting significant wave height using oceanographic data from NDBC Station 51004 Southeast Hawai'i.

## Thesis Abstract
Significant wave height is a crucial parameter in oceanographic studies as it directly affects safety, operations, and the planning of maritime activities, thereby requiring accurate and reliable prediction methods. This study aims to compare the performance of two machine learning algorithms, namely gradient boosting (XGBoost) and random forest, in predicting significant wave height using oceanographic data from Southeast Hawai’i. The research stages included data collection and processing, model training and implementation, and evaluation of prediction results for both models. The gradient boosting algorithm achieved an MAE of 0,110604, RMSE of 0,153243, R2 of 0,921567, bias of -0,005159, and Pearson’s correlation coefficient of 0,960166, with a computation time of 1 minute 53,4 seconds. In comparison, random forest obtained an MAE of 0,111459, RMSE of 0,154747, R2 of 0,920020, bias of -0,004722, and Pearson’s correlation coefficient of 0,959282, with a computation time of 38 minutes 24,3 seconds. Gradient boosting demonstrated superior performance in capturing fluctuation patterns and variations of significant wave height, as well as in minimizing errors, particularly large errors, whereas random forest showed an advantage in producing more neutral bias.

## Tools Used
While working in this project, I used Visual Studio Code as the main app to run Jupyter Notebook files containing all python scripts for the analysis, processing, modelling, and evaluation processes. Here are the list of all apps, tools, and libraries used:
- Visual Studio Code
- Jupyter Notebook
- Pandas
- Numpy
- Seaborn
- Matplotlib
- SKLearn
- XGBoost
