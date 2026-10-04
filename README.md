# House Price Prediction

A machine learning project that predicts median house prices in California using Linear Regression and Random Forest.

## Dataset
California Housing dataset (from scikit-learn): 20,640 rows and 9 columns. Each row is a California district, described by median income, house age, average rooms, population, and location.

## What I Did
- Explored the data: checked for missing values (none found) and identified outliers
- Visualised the price distribution and the relationship between income and price
- Split the data into 80% training and 20% test sets
- Trained and compared two models: Linear Regression and Random Forest

## Results
| Model | R2 Score | Average Error |
|---|---|---|
| Linear Regression | 0.576 | $53,320 |
| Random Forest | 0.805 | $32,754 |

Random Forest performed much better, reducing the average prediction error by about $20,000.

## Tools Used
Python, pandas, numpy, matplotlib, scikit-learn

## How to Run
1. Install the libraries: `pip install -r requirements.txt`
2. Open `house_price_prediction.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells
