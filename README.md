

Old Car Price Prediction using Supervised Learning (RandomForestRegressor)
Project Overview:
This project focuses on predicting the prices of used cars using a supervised learning model, specifically the RandomForestRegressor algorithm. The goal is to develop a robust model that can accurately estimate the price of a car based on various features such as the car's age, mileage, brand, model, engine size, and more.

Key Features
1. Dataset: The dataset used for this project includes historical data on used car prices, including features like brand, model, year of manufacture, mileage, fuel type, transmission, and engine size.

2. Data Preprocessing: The data underwent extensive preprocessing, including handling missing values, encoding categorical variables, and normalizing numerical features to ensure the model's performance.
  
3. Modeling: The RandomForestRegressor algorithm was chosen for its ability to handle non-linear relationships and interactions between variables. The model was trained and validated using cross-validation to prevent overfitting.
  
4. Power BI Visualization: The results and insights from the model were visualized using Power BI to provide interactive dashboards that allow users to explore the relationships between features and the predicted prices.

5. Performance Evaluation: The model's performance was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to ensure it provides accurate predictions.

6. Results: The final model demonstrated strong predictive power, making it a reliable tool for estimating the prices of used cars.

Technologies Used:

1. Python: For data manipulation, modeling, and evaluation.
   
2. Pandas: For data preprocessing and manipulation.

3. NumPy: For numerical operations.
   
5. Scikit-learn: For implementing the RandomForestRegressor and model evaluation.
   
7. Power BI: For creating interactive dashboards and visualizing the model's predictions.
Matplotlib/Seaborn: For additional data visualizations.

How to Use:

1. Clone the Repository: Clone this repository to your local machine using git clone.
   
2. Install Dependencies: Install the required Python libraries using pip install -r requirements.txt.
   
3. Run the Notebook: Open and run the Jupyter Notebook Car_Price_Prediction.ipynb to see the data preprocessing, model training, and evaluation steps.

4. Explore Power BI Dashboards: Open the provided Power BI file to interact with the visualized data and gain insights.

5. Predict Car Prices: Use the trained model to predict the price of a used car by providing the necessary features.
Future Work

7. Feature Engineering: Further enhance the model by experimenting with additional features or feature interactions.
   
8. Model Optimization: Tune hyperparameters to improve the model's accuracy and generalization capabilities.

9. Deployment: Deploy the model as a web application using Flask or Django to make it accessible to users.
