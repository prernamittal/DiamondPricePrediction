# DiamondPricePrediction
<h2>Abstract</h2>
This project aims to develop a machine learning model for predicting the prices of diamonds based on their various characteristics. The dataset used for this project contains information on 50,000 diamonds, including their carat weight, cut, color, clarity, depth, and table dimensions, as well as the price at which they were sold.

We begin by exploring the data and performing exploratory data analysis (EDA) to identify any patterns, trends, or outliers that may exist in the dataset. We then preprocess the data by handling missing values, outliers, and categorical variables, and scale the numeric features to ensure that they are on the same scale.

Next, we train several machine learning models, including linear regression, decision trees, random forests, and gradient boosting, to predict the diamond prices. We evaluate the models using various metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared to determine which model performs the best.

Finally, we use the best-performing model to make predictions on a separate test dataset, and evaluate its performance using various evaluation metrics. The results show that our model is able to predict the diamond prices with a high degree of accuracy, and can be used by jewelers and diamond traders to make informed pricing decisions.

In conclusion, this project demonstrates the potential of machine learning algorithms in predicting diamond prices, and provides a practical solution for the diamond industry.

# Steps:
<ol>
<li><b>Importing Required Libraries:</b>
The first step is to import the required libraries in Python, which are pandas, seaborn, matplotlib.pyplot, numpy, and sklearn. These libraries are used for data manipulation, visualization, and machine learning model building.
  <li><b>Loading the Data:</b>
The code reads the CSV file using the read_csv function from the pandas library and stores it in a pandas DataFrame named df. The data is displayed using the df variable.
  <li><b>Exploratory Data Analysis (EDA):</b>
Exploratory Data Analysis (EDA) is the process of analyzing and visualizing data to extract insights from it. In this code, seaborn library is used to plot different types of graphs such as bar plot, scatter plot, etc. to analyze the relationship between different variables and the target variable Price(in US dollars).
    <li><b>Data Preprocessing:</b>
Data preprocessing is an essential step before building a machine learning model. In this code, the LabelEncoder class from the sklearn library is used to encode categorical variables into numerical variables. The fit_transform() method is used to transform categorical variables into numerical variables.
  <li><b>Machine Learning Model Building:</b>
The code splits the data into training and testing sets using the train_test_split() function from sklearn library. The decision tree regressor and random forest regressor models are built and trained using the DecisionTreeRegressor and RandomForestRegressor classes from the sklearn library, respectively.
  <li><b>Evaluation Metrics:</b>
Evaluation metrics are used to measure the performance of the machine learning models. In this code, the mean_absolute_error(), mean_squared_error(), r2_score(), and math.sqrt() functions from sklearn and math libraries are used to calculate the Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared score (R2 score), and Root Mean Squared Error (RMSE) of the machine learning models.
  <li><b>Comparison of R2 Score:</b>
Finally, the R2 score of both the models are compared and printed for analysis. The R2 score is a statistical measure that represents the proportion of variance in the dependent variable that is predicted by the independent variables in a regression model. A higher R2 score indicates a better fit of the model.
  </li></ol>
    
# Tech Stack:
<li>Python
<li>Streamlit
<li>Python Libraries: pandas, seaborn, matplotlib.pyplot, numpy, sklearn
<li>Jupyter Notebook

# Deployment:
Test the deployed model [here](https://diamondpriceprediction.streamlit.app/)

# Demo:
![](https://github.com/prernamittal/DiamondPricePrediction/blob/main/demo.gif)
