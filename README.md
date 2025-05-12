# Project Summary

This project focuses on analyzing and predicting the selling price of used cars based on various features such as vehicle age, mileage, engine capacity, fuel type, and more. The dataset contains 15,411 rows and 13 columns, with the target variable being the `selling_price`.

## Key Steps:
1. **Data Exploration and Visualization**:
    - Analyzed the distribution of features and identified outliers in columns like `km_driven`, `engine`, `selling_price`, and `max_power`.
    - Visualized relationships between features such as mileage vs. selling price, fuel type vs. selling price, and brand vs. selling price.

2. **Outlier Detection and Removal**:
    - Used the Interquartile Range (IQR) method to detect and remove outliers, ensuring a cleaner dataset for model training.

3. **Feature Engineering**:
    - Encoded categorical variables using one-hot encoding.
    - Identified important features using the `ExtraTreesRegressor` model.

4. **Model Building and Evaluation**:
    - Built multiple regression models, including Linear Regression, Support Vector Regression, Decision Tree Regressor, Random Forest Regressor, Ridge, and Lasso.
    - Evaluated models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Explained Variance Score (EVS), and R-squared Score.

5. **Model Comparison**:
    - Compared the performance of different models to identify the best-performing one.
    - Random Forest Regressor emerged as one of the top-performing models.

6. **Model Deployment**:
    - Saved trained models as pickle files for future use.
    - Demonstrated predictions using sample input values.

## Observations:
- Dealers tend to provide higher price valuations compared to other seller types.
- Vehicle age negatively impacts the selling price.
- Automatic cars have a higher average selling price than manual cars.
- Petrol is the most preferred fuel type, followed by diesel and LPG.
- Brands like Maruti and Hyundai dominate the used car market.

## Conclusion:
The project successfully built a predictive model for estimating the selling price of used cars. The insights derived from the analysis can help stakeholders, such as car dealers and buyers, make informed decisions. Further improvements can be made by incorporating additional features or fine-tuning the models.
