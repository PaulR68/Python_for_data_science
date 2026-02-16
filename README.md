# Hotel Cancellation Analysis & Prediction

## Project Overview

This project evaluates hotel cancellation rates to identify key determinants and forecast future cancellations. The analysis aims to provide tools for hotel management to optimize scheduling and revenue management by predicting customer behavior.

The study proceeds in three main phases:
1.  **Descriptive Statistics**: Visualization of dataset variables (seasonality, market segments, guest demographics).
2.  **Correlation Analysis**: Identification of variables strongly correlated with cancellations, such as deposit type and origin country.
3.  **Machine Learning**: Implementation of a Decision Tree Classifier to predict cancellation probabilities.

## Repository Structure

* `Project_code.ipynb`: The Jupyter Notebook containing the complete Python code for data cleaning, exploratory data analysis (EDA), and machine learning modeling.
* `bookings.txt`: The primary dataset containing 5,000 observations of hotel reservations.
* `country_codes_and_continents.csv`: Auxiliary dataset used for geographical analysis.
* `Python_Project_Group7.pdf`: The final comprehensive report detailing the methodology and findings.

## Methodology & Results

The analysis utilizes Python libraries (Pandas, Scikit-learn) to process the data.

* **Data Analysis**: The study highlights significant correlations, noting that specific market segments (e.g., Online TA) and seasons (summer) show distinct booking behaviors.
* **Model**: A Decision Tree model was trained and tuned using GridSearchCV to prevent overfitting.
* **Performance**: The optimized model (max_depth=10, min_samples_split=2) achieved a test accuracy of **79.39%**.

## Usage

1.  Clone this repository.
2.  Ensure the following dependencies are installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Open `Project_code.ipynb` in Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially to reproduce the analysis and model generation.

## Authors

* Gabriel Deregnaucourt
* Paul Ritzinger
