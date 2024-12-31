## California House Value Prediction
This project aims to predict house value in California districts using over 20,000 data on housing features and location. The dataset contains 10 columns including housing median age, total rooms and location coordinates. The goal is to build a predictive model using Random Forest to estimate house value and evaluate performance using Root Mean Square Error (RMSE). Different tools were used such as Python libraries: Pandas and Numpy, Scikit learn and Matplotlib.

## Project Overview:

### Data Collection and Processing:
This project predicts the house value in over 20000 California districts. The dataset contains features such as house age, total rooms, number of bedrooms, population, median income and location coordinates. The data is processed using Pandas and Numpy before analysis. Additional features were added for clarity and to better capture anomalies that may affect prediction. The added features were room per household and bedroom per room. 

### Data Visualization:
For visualization purposes, tools like Matplotlib, Seaborn are used for histograms, scatter plots and correlation matrix.

### Train-Test Split:
To evaluate the model’s performance, the dataset is split into training and testing subsets using Scikit-learn's train-test split method. This ensures the model is trained on part of the data and evaluated on unseen data, allowing for accurate performance assessment.

### Regression Model using Random Forest:
The project uses the Random Forest Regressor, a powerful ensemble learning method that reduces overfitting and handles non-linear relationships well. This model achieves strong predictive accuracy by combining multiple decision trees.

### Model Evaluation:
The model is evaluated using metrics such as R² (R-squared) score and Root Mean Squared Error (RMSE).

## Conclusion
The feature importance aspect of the regressor is able to show nonlinear relationships unlike the correlation matrix which only shows linear relationships. It is based on the contribution weight of reducing prediction errors. This shows the strength of the random forest in predicting house value with high accuracy.


 
