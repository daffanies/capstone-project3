# capstone-project3-purwadhika

# Apartment Price Prediction - Daegu, South Korea

This repository contains the code and analysis for predicting apartment prices in Daegu, South Korea. The project utilizes a dataset of apartment listings to explore various features and build a machine learning model to predict apartment prices in this region.

### Project Introduction

The project aims to analyze and predict the pricing of apartments in Daegu. By understanding the various factors that influence the price, property owners and potential investors can make informed decisions. The notebook includes the following key components:

1. **Data Preprocessing**:
    - Cleaning and preparing the apartment listing dataset for analysis.
    - Handling missing values, encoding categorical variables, and normalizing data.

2. **Exploratory Data Analysis (EDA)**:
    - Visualizing and understanding the relationships between different features and the apartment prices.
    - Identifying key factors that significantly impact pricing.

3. **Feature Engineering**:
    - Creating new features from the existing data to improve model performance.
    - Selection of relevant features for model training.

4. **Modeling**:
    - Building and evaluating multiple machine learning models to predict apartment prices.
    - Comparison of model performance using metrics like RMSE, MAE, and R² score.

5. **Model Evaluation and Interpretation**:
    - Assessing the performance of the final model on the test data.
    - Interpretation of model results and understanding the key drivers of apartment prices.

6. **Business Insights and Recommendations**:
    - Providing actionable insights based on the model results.
    - Recommending strategies for property owners to optimize their listings for better pricing.

## How to Run

To run the notebook on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/apartment-price-prediction-daegu.git
    cd apartment-price-prediction-daegu
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the Jupyter Notebook:
    ```bash
    jupyter notebook ML_apartemen_final.ipynb
    ```

## Dependencies

The project requires the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

You can install all dependencies using the provided `requirements.txt` file.

## Dataset

The dataset used in this project is sourced from apartment listings in Daegu, South Korea. The data contains various features related to the properties, including location, size, amenities, and price.

## Results

The final model achieves a reasonable accuracy in predicting apartment prices. Detailed results and visualizations are provided in the notebook, including feature importance and error analysis.
