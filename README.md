# Airbnb Price Prediction
Predicting Airbnb listing prices using machine learning techniques to help hosts optimize pricing strategies and travelers estimate fair costs.


## Project Overview
This project explores the relationship between Airbnb listing features (location, amenities, description text, etc.) and their price. It applies multiple machine learning models—including Linear Regression, Random Forest, Gradient Boosting, and Neural Networks—to predict log-transformed prices.

Additionally, text analysis on the description column is performed using TF-IDF vectorization, and stacked regression is experimented with to improve model performance.


## Dataset
The dataset comes from Airbnb listings, including features such as:

* Numerical: price, number of reviews, availability, etc.

* Categorical: room type, neighborhood, amenities

* Text: listing description

Dataset is not included in the repo due to size restrictions. The dataset will be imported while executing the code
[Link](https://www.kaggle.com/datasets/stevezhenghp/airbnb-price-prediction)

***************************************

## Features
* <b>Data preprocessing</b>: handling missing values, categorical encoding, text cleaning

* <b>Exploratory Data Analysis (EDA)</b>: distribution plots, correlations, feature engineering

* <b>Machine Learning models</b>: Linear Regression, Random Forest, Gradient Boosting, Neural Networks

* Text feature integration using <b>TF-IDF</b>

* Stacked regression experimentation

* Model comparison with evaluation metrics (MAE, RMSE, R²)

********************************
## Libraries used
1. nltk
2. kagglehub
3. numpy
4. pandas
5. matplotlib
6. seaborn
7. plotly
8. ipywidgets
9. scikit-learn
10. scipy
11. statsmodels
12. tensorflow



##  Setup Instructions

Follow the steps below to set up and run this project locally:

### Clone the repository
```bash
git clone https://github.com/your-username/Airbnb-Price-Prediction.git
cd Airbnb-Price-Prediction
```

### Create venv  and activate
```python
python -m venv venv

# Activate venv
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Install Jupyter Kernal inside venv
```bash
pip install ipykernel
python -m ipykernel install --user --name=airbnb_env --display-name "Python (Airbnb)"
```

### Start Jupyter Notebook
```bash
jupyter notebook
```

