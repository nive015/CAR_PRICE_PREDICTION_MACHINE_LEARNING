# CAR_PRICE_PREDICTION_ML_DJANGO

HERE IS THE LINK TO DOWNLOAD ALL THE FILES:

https://drive.google.com/drive/folders/1_jbmudV0-AzQh9_knK-U8JzZ34fw5mqb?usp=sharing

HERE IS THE LINK OF THE VIDEO OF THE PROJECT:

https://drive.google.com/file/d/12V-KsVZudP2TEpGQBG4bMs_NHNhJVFXY/view?usp=sharing

**Project Overview:**
- The project uses a dataset (`car_prices.csv`) containing car attributes such as year, make, model, condition, odometer, color, seller details, market valuation (MMR), and selling price.
- The goal is to preprocess the data and apply different regression models to determine which one provides the highest accuracy.
- Various data visualization techniques are used to gain insights.

1. **Importing Libraries:**  
   - Libraries like `pandas`, `seaborn`, `numpy`, `matplotlib`, and various `sklearn` modules (e.g., `LinearRegression`, `RandomForestRegressor`, `DecisionTreeRegressor`) are imported.
   
2. **Loading and Inspecting Data:**  
   - Reads `car_prices.csv` and displays basic information about the dataset.

3. **Data Preprocessing:**  
   - Likely includes handling missing values, encoding categorical variables, and normalizing data.

4. **Model Training & Evaluation:**  
   - Several regression models are trained (Linear Regression, Ridge, Lasso, ElasticNet, Decision Tree, Random Forest, KNN).
   - Performance metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score are used to evaluate them.

5. **Visualization & Insights:**  
   - Graphs and plots are used to understand the relationship between features and car prices.

6. **Final Predictions:**  
   - The best-performing model is used to predict car prices on a random subset.
   - The pickle files for encoder and the model are saved and downloaded.
     
7. **Django Integration:**  
   - The saved models are loaded and the django website is created. 
