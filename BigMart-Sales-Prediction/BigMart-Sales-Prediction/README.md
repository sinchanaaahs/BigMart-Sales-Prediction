# Big Mart Sales Prediction

A machine learning project that predicts retail product sales using Python and XGBoost Regression.

## Objective
Predict `Item_Outlet_Sales` from product and outlet characteristics after cleaning and preprocessing the dataset.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Workflow
1. Load the Big Mart sales dataset
2. Inspect and clean missing values
3. Perform exploratory data analysis
4. Encode categorical variables
5. Split the data into training and test sets
6. Train an XGBoost Regressor
7. Evaluate the model using R² and RMSE
8. Visualize actual vs. predicted sales

## Dataset
Place the Big Mart training CSV in the `data/` folder and name it `Train.csv`.

The notebook includes a clearly labelled demo-data fallback so the workflow can be tested before the original dataset is added.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook BigMart_Sales_Prediction.ipynb
```

Then run the notebook from top to bottom.

## Note
The repository does not include a third-party dataset. Add the dataset you are permitted to use to `data/Train.csv`.
