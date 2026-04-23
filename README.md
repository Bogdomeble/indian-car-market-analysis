
# Used Car Price Analysis - India 

This project analyzes the used car market in India using data from Cardekho.com. The goal is to identify key factors influencing vehicle resale value and to build a predictive model.

##  Project Overview
The analysis explores how technical specifications (engine, power, mileage), ownership history, and market factors (brand, seller type, transmission) affect car prices.

**Key Findings:**
* **Engine Power** is the strongest positive predictor of price.
* **Manual Transmission** and **Vehicle Age** are the primary factors that decrease value.
* **Decision Tree Regressor** outperformed linear models, achieving an R² score of ~0.96.

##  Features
* **Data Cleaning:** Extracting numerical values from strings (e.g., BHP, CC, kmpl) and handling missing data.
* **Feature Engineering:** Calculating vehicle age and grouping rare brands.
* **EDA:** Visualizing distributions and correlations using Seaborn and Matplotlib.
* **Modeling:** Comparing Simple Linear Regression, Multiple Regression, and Decision Tree Regressors.

##  Getting Started

### Prerequisites
Make sure you have Python installed. It is recommended to use a virtual environment.

### Installation
1. Download the `Car details v3.csv` dataset from Kaggle and place it in the project folder.
2. Install the required libraries:
```bash
pip install -r requirements.txt
```

### Usage

To explore the analysis and run the models, start the Jupyter Notebook server in your project directory:

```bash
jupyter notebook
```
This will open a new tab in your web browser. From there, open the provided .ipynb file (e.g., SAD_projekt.ipynb) and execute the cells sequentially to see the data cleaning process, visualizations, and model evaluations.

##  Dependencies
* jupyter
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy



