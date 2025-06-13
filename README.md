Retail Demand Forecasting
In this project I focused on retail demand forecasting using XGBoost that is combined with a dynamic user simulation module to model user behavior impacting demand.
📝 Key components:
•	Libraries: Pandas, NumPy, Matplotlib, Seaborn, XGBoost, scikit-learn
•	Data: https://www.kaggle.com/datasets/tanayatipre/store-sales-forecasting-dataset
📝Workflow:
1.	Data Exploration: Understand the structure, missing values, distributions.  
2.	Preprocessing: Handle missing values, encode categorical variables (if any), normalize/scale as needed.  
3.	Modeling:
   - Use XGBoost Regressor to train the model.  
   - Perform cross-validation.  
   - Split data into train and test sets.
4.  Evaluation:  
   - Compute Mean Squared Error (MSE).  
   - Compute R² score.  
   - Visualize actual vs. predicted demand.  
5. Dynamic User Simulation:
   A custom simulation to model changes in demand based on hypothetical customer behavior patterns (e.g., price sensitivity, seasonal variation).  
📝 Results Summary
The XGBoost model was able to predict retail demand quite well. It gave a low Mean Squared Error (MSE), showing that the predictions were close to the actual values. The R² score was high, which means the model explained most of the changes in demand. Overall, the model performed well and can help forecast demand based on sales data.
