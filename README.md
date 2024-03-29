# FishMarekt-fishspecies-prediction



# Project Description

- This dataset is a record of 7 common different fish species in fish market sales. With this dataset, a predictive model can be performed using machine friendly data and estimate the weight of fish can be predicted.



## Dataset
The dataset was obtained from here kaggle.
click here for the datasets 

https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/master/fish%20market%20dataset.csv

### The main objective of the project is:

To train predictive models that predict the weight of fish using the popular linear ML algorithms—scikit-learn-implementation.



## 📋 Tasks Performed
* 📂 EDA of the dataset
* 📂 cleaning the data 
* 📂 Feature Extraction
* 📂 constructing model
* 📂 Data Manipulation
* 📂 Data Visualization

### steps we did in this project
- Uploading the datasets
- Cleaning and converting the data types
- Feature extractions
- Visualize the outliers of the dataset
- Distribution of the dataset after standardization and noise removal
- Visualize relationships between variables of dataset
- Model selection and implementing the best model
- Predicting and visualing the results
- A learning curve of a best model (LGBMRegressor)
- Normal Q-Q plot of best model
- Regplot of target vs prediction on validation dataset



# Results of the models 
   
    
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Linear_regression</th>
      <th>Decission_Tree</th>
      <th>Random_Forest</th>
      <th>XGboots_Regressor	</th>
      <th>LGBM_Regressor</th>
      <th>CatBoost_Regressor</th>
      <th>SGD_Regressor</th>
      <th>Kernel_Ridge</th>
      <th>Elastic_Net</th>
      <th>Bayesian_Ridge</th>
      <th>GradientBoosting_Regressor</th>
      <th>SVR</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>MSE</th>
      <td>0.08</td>
      <td>0.05</td>
      <td>0.02</td>
      <td>0.03</td>
      <td>0.03</td>
      <td>0.03</td>
      <td>0.10</td>
      <td>0.10</td>
      <td>0.52</td>
      <td>0.08</td>
      <td>0.03</td>
      <td>0.02</td>
    </tr>
       <tr>
      <th>MAE</th>
      <td>0.23</td>
      <td>0.16</td>
      <td>0.09</td>
      <td>0.13</td>
      <td>0.12</td>
      <td>0.10</td>
      <td>0.26</td>
      <td>0.26</td>
      <td>0.62</td>
      <td>0.23</td>
      <td>0.12</td>
      <td>0.09</td>
    </tr>
       <tr>
      <th>R_squred</th>
      <td>0.89</td>
      <td>0.94</td>
      <td>0.98</td>
      <td>0.96</td>
      <td>0.97</td>
      <td>0.97</td>
      <td>0.86</td>
      <td>0.86</td>
      <td>-3.87</td>
      <td>0.89</td>
      <td>0.97</td>
      <td>0.98</td>
    </tr>
  </tbody>
</table>
</div>


## Visualize the outliers of the dataset

![Visualize the outliers of the dataset](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/master/images/outliers.png)


## Distribution of the dataset after standardization and noise removal 

![Distribution of the dataset after standardization and noise removal ](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/497c2928bf7672d1aed40683ea196307b079486a/images/standardisation%20noise%20removal.png)


## Heatmap Visualize relationships between variables of dataset

![Heatmap Visualize relationships between variables of dataset](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/master/images/heatmap.png)

## A learning curve of a best model (LGBMRegressor)

![Visualize the outliers of the dataset](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/master/images/learning%20curve.png)

##  Regplot of target vs prediction on validation dataset

![Regplot of target vs prediction on validation dataset](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/94fbe9d737f21ed112e46be956eaedc350f43ed9/images/target%20vs%20prediction.png)

## The best model actual value  vs prediction value plot 

![The best model actual value  vs prediction value plot](https://github.com/hariramgit/FishMarekt-fishspecies-prediction/blob/94fbe9d737f21ed112e46be956eaedc350f43ed9/images/actual%20value%20vs%20prediction%20value%20plot.png)





## 🏗️ Built with
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)



## 👩‍💻 Libraries used
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=purple)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-F7931E.svg?style=for-the-badge&logo=Matplotlib&logoColor=orange)
![os](https://img.shields.io/badge/os-F7931E.svg?style=for-the-badge&logo=os&logoColor=green)

![seaborn](https://img.shields.io/badge/Seaborn-2C2D72?style=for-the-badge&logo=Seaborn&logoColor=blue)
![Xgboost](https://img.shields.io/badge/Xgboost-2C2D72?style=for-the-badge&logo=Xgboost&logoColor=blue)
![plotly](https://img.shields.io/badge/plotly-2C2D72?style=for-the-badge&logo=plotly&logoColor=black)
![statsmodels](https://img.shields.io/badge/statsmodels-2C2D72?style=for-the-badge&logo=statsmodels&logoColor=black)

![plotlyplotly](https://img.shields.io/badge/plotlyplotly-2C2D72?style=for-the-badge&logo=sklearn&logoColor=black)
![plotly](https://img.shields.io/badge/plotly-2C2D72?style=for-the-badge&logo=catboost&logoColor=black)



Important models/algorithms were used in this project:
- StandardScaler
- LabelEncoder
- train_test_split
- metrics 
- LinearRegression,Ridge,lasso
- DecisionTreeRegressor
- RandomForestRegressor
- SGDRegressor
- ElasticNet
- BayesianRidge
- GradientBoostingRegressor
- KernelRidge




## Organization
- Repository "(https://github.com/hariramgit/FishMarekt-fishspecies-prediction/tree/master/code))": you may find the main Python Notebooks produced by me to realize the analysis, visualisations and predictive models.


## ✍️ Authors
*HARIRAM
* [Email](mailto:hariramhdmp@gmail.com)


## 🤝 Support
Contributions, issues, and feature requests are welcome!
Give a STAR if you like this project! and FOLLOW do SUPPORT Friends.

