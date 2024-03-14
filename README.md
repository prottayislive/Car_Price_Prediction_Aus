# Australian Car Price Predictions: Data Insight to Model Precision
[View the code and visualisations](https://github.com/prottayislive/Car_Price_Prediction_Aus/blob/main/Car_Price_Prediction_Australia.ipynb)

The notebook presents a structured approach to predicting vehicle prices through a series of data science methodologies encompassing exploratory data analysis (EDA), data cleaning, feature engineering, modeling, and evaluation. This report delves into the specifics of each step, highlighting the key findings and the efficacy of the applied models.

### Data Preparation and Preprocessing

The process begins with importing necessary Python packages, which are foundational for data manipulation, analysis, and visualization. Following package loading, the dataset is ingested from a CSV file, laying the groundwork for subsequent analysis.

#### Data Cleaning and Transformation

Initial data inspection revealed the necessity for cleaning and transforming the dataset to ensure its suitability for analysis. This stage addressed missing values, corrected data types, and normalized column names, thereby streamlining the dataset for easier manipulation.

#### Outlier Detection and Removal

The analysis then focused on the 'Kilometres' and 'Price' columns to identify and mitigate the impact of outliers. Using the Inter Quartile Range (IQR) method, outliers were detected and removed. This approach is crucial for preventing skewed analyses and improving model accuracy by focusing on representative data points.

### Exploratory Data Analysis (EDA)

EDA provided insights into the distribution and relationships between different variables within the dataset. Visualization techniques, including histograms and scatter plots, facilitated a deeper understanding of the data, revealing patterns and trends that inform model selection and feature engineering.

### Feature Engineering and Data Encoding

The notebook highlights the transformation of categorical variables into a numerical format through encoding, enabling their use in machine learning models. This step is pivotal for integrating non-numeric features into the predictive analysis, enhancing the models' capability to capture the essence of the dataset.

### Model Development and Evaluation

#### Linear Regression

Initially, a Linear Regression model was developed, trained, and evaluated. Despite its simplicity, Linear Regression provided a baseline for performance comparison. The model's evaluation focused on metrics such as R-squared and Mean Squared Error (MSE), offering initial insights into its predictive power.

#### Random Forest

Subsequently, a Random Forest model was employed, capitalizing on its ability to handle non-linear relationships and interactions between features more effectively than Linear Regression. The Random Forest model underwent training, prediction, and evaluation, culminating in an accuracy of 86%. This model outperformed the Linear Regression baseline, demonstrating its robustness and suitability for this application.

### Findings and Conclusion

The notebook's analysis concludes with a comparison of the prediction results from both models, visually represented to illustrate the Random Forest model's superior performance. The detailed approach, from data cleaning to sophisticated modeling, underscores the potential of machine learning in predicting vehicle prices with high accuracy.

This comprehensive exploration and modeling process underscore the importance of thorough data preparation and the choice of an appropriate modeling technique. The Random Forest model's success in achieving 86% accuracy highlights its efficacy in handling complex datasets with non-linear relationships and interactions, making it a robust choice for predicting vehicle prices.
