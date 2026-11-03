# Ames House Price Prediction using Linear Regression*

## OBJECTIVE
The main goal of this project is to predict the sale price of a house based on its features like Lot Area, Neighborhood, Basement Area, and Garage capacity. This helps buyers and sellers to estimate a fair price for a property.

## DATASET
- *Name:* House Prices Dataset (Ames Housing)
- *Source Link:* https://www.kaggle.com/code/hnazari8665/ames-housing-dataset
- *Rows & Columns:* ∼1460 rows x ∼80 columns 
- *Key Columns:*
   - LotArea – Lot size of the property
- OverallQual – Overall material and finish quality
- GrLivArea – Above-ground living area
- BedroomAbvGr – Number of bedrooms
- FullBath – Number of full bathrooms
- YearBuilt – Year the house was built
- SalePrice – Target variable to be predicted


## TOOLS USED
- *Language:* Python (Jupyter Notebook)
- *Libraries Used:*
    - pandas
    - 
## STEPS FOLLOWED
1. Data Cleaning: Handled missing values using median, removed duplicates using `drop_duplicates()`.
2. Encoding:Converted categorical column `Neighborhood` into numerical using LabelEncoder.
3. Splitting: Separated features (X) and target (y) and split into 80% training and 20% testing.
4. Modelling: Trained a Linear Regression model using `model.fit()`.
5. Evaluation: Predicted on test data and calculated R2 Score.

## KEY INSIGHTS
1. The model achieved an *R2 Score of 0.73 (73.17%)*, which is a good fit for Linear Regression.
2. Lot Area and Total Basement Area have a strong positive correlation with SalePrice.
3. Neighborhood is a key factor that influences the house price significantly.
4. Data cleaning (filling nulls) improved model accuracy from ∼65% to 73%.
5. Linear Regression is suitable for this dataset as the target is a continuous variable, not classification.
6. Scaling was not required for this basic model but can improve performance with advanced models.

6. Screenshots or Output
- Model Prediction Output: Predictions are in dollar values (e.g., 203601.41, 79560.32).
- *Final Result:* `R2 Score = 0.7317722586876623`
- Screenshots of code execution and R2 score are added in the `/screenshots` folder.

7. How to Run or Open
1. Clone the repository: `git clone https://github.com/your-username/house-price-prediction.git`
2. Open Jupyter Notebook: `jupyter notebook`
3. Open file `house_price_prediction.ipynb`
4. Run all cells from top to bottom to get the same R2 score.
5. Requirements: `pip install pandas scikit-learn`

8. Author
- *Name:* [Ninte Peru Ividuthe Type Cheyyu]
- *Batch:* [Ninte Batch - Eg: B5 Data Sciencee
