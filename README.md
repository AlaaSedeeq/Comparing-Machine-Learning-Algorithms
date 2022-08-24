#
# Comparing Machine Learning Algorithms
- It's important to define which algorithm gives better performance of the machine learning solutions, we need to narrow down on the best algorithms that suit both the data and the business requirements.

- You can see:
    - <a href="https://www.kaggle.com/code/alaasedeeq/object-oriented-programming-for-data-science">OOP implementation of the same project</a>
    - <a href="https://www.kaggle.com/code/alaasedeeq/house-price-prediction-top-8">Kaggle Version of the same project</a>

#
### <p style="background-color:skyblue; font-family:newtimeroman; font-size:200%; text-align:center; border-radius: 10px 100px;">Procedures:</p>
<ul>
    <li><b>Phase I</b>
        <ul>
            <li>Data Pre-processing
                <ul>
                    <li>Gathering the Data
                    <li>Data Exploration and Analysis
                    <li>Data Cleaning
                        <ul>
                            <li>Outliers Detection
                            <li>Dealing with Null values
                            <li>Adding new features
                        </ul>
                    <li>Prepare the data for ML
                    <li>Dealing with the high skewness of the data
                </ul>
        </ul>
    <li><b>Phase II:</b>
    </li>
    <ul>
        <li>Initialize the models.
        <li>Comparing different Machine learning models.
            <ul>
                <li>Compute train/test results.</li>
                <li>Evaluate our models using cross validation.</li>
            </ul>
        <li>Improving the top models</li>
        <li>Stacking the best models to get a better score</li> 
    </ul>
</ul>

#
### Results :<br>
- Phase 1
  - Nulls
  
<p align="center">
  <img width="48%" src="data\images\nulls.png">
  <img width="48%" src="data\images\nulls_.png">
</p>
  
  - Skewness
  
<p align="center">
  <img width="48%" hight="200" src="data\images\skewness_values.png">
  <img width="48%" hight="200" src="data\images\skewness.png">
</p>

- Phase 2
  - Train/Test
    - R-Squared and Adjusted R Squared
    
    <p align="center">
      <img width="48%" src="data\images\tarin_test_R_2.png">
      <img width="48%" src="data\images\tarin_test_adj_R_2.png">
    </p>
  
    - MAE, MSE, and RMSE
  
<p align="center">
  <img width="33%" hight="200" src="data\images\tarin_test_mae.png">
  <img width="33%" hight="200" src="data\images\tarin_test_mse.png">
  <img width="33%" hight="200" src="data\images\tarin_test_rmse.png">
</p>


  - Cross-Validation
    - R-Squared and Adjusted R Squared
      <p align="center">
        <img width="48%" src="data\images\cv_R_2.png">
        <img width="48%" src="data\images\cv_R_2_box.png">
      </p>
    
    - RMSE
      <p align="center">
        <img width="48%" src="data\images\cv_rmse.png">
        <img width="48%" src="data\images\cv_rmse_box.png">
      </p>
  
#

### Used Data  :<br>
<a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data">House Prices</a><br>
#
### Algorithms :<br>
  - Elastic Net 
  - Kernel Ridge
  - Lasso
  - Random Forest 
  - SVM 
  - XGBoost 
  - LGBM
  - Gradient Boosting
  
#
