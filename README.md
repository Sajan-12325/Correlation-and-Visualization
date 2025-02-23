This project involves data exploration, visualization, and regression modeling using Python. 
The dataset used is the Automobile Dataset, which is loaded from an external URL. 
The project applies correlation analysis, regression plots, and machine learning models to predict car prices based on various features.

Project Structure

WEEK -1 

The notebook consists of the following key steps:

1. Data Loading and Exploration
The dataset is loaded using pandas.read_csv().

Data types of all columns are checked using df.dtypes.

2. Data Preprocessing
Numeric columns are filtered using select_dtypes().
A correlation matrix is computed using df.corr() to identify relationships between variables.

3. Data Visualization
Regression plots are created using seaborn.regplot() to visualize the relationship between:
engine-size and price
highway-mpg and price
peak-rpm and price
stroke and price
Boxplots are generated using sns.boxplot() to analyze categorical variables.

4. Linear Regression Modeling
A Simple Linear Regression model is built using sklearn.linear_model.LinearRegression().
The model is trained using fit(X, y), where:
X consists of independent variables.
y is the target variable (price).
Predictions are made using predict(X).

Also Used Other models regression models like Multiple Linear Regression, Polynomial Regression. 

WEEK - 2

5. Pipeline Implementation
A data preprocessing and modeling pipeline is created using sklearn.pipeline.Pipeline.
The pipeline includes:
Feature scaling (StandardScaler)
Linear Regression Model


6. Model Evaluation:

Using Visualization plots distplot
Using R2_score and Mean Squared Error