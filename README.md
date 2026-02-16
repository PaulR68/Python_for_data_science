# Hotel Cancellation Analysis & Prediction

## Project Overview
This project evaluates hotel cancellation rates to identify key determinants and forecast future cancellations. [cite_start]The analysis aims to provide tools for hotel management to optimize scheduling and revenue management by predicting customer behavior[cite: 7, 9].

The study proceeds in three main phases:
1.  [cite_start]**Descriptive Statistics:** Visualization of dataset variables (seasonality, market segments, guest demographics)[cite: 11].
2.  [cite_start]**Correlation Analysis:** Identification of variables strongly correlated with cancellations, such as deposit type and origin country[cite: 13, 177].
3.  [cite_start]**Machine Learning:** Implementation of a Decision Tree Classifier to predict cancellation probabilities[cite: 14].

## Repository Structure

* **`Project_code.ipynb`**: The Jupyter Notebook containing the complete Python code for data cleaning, exploratory data analysis (EDA), and machine learning modeling.
* [cite_start]**`bookings.txt`**: The primary dataset containing 5,000 observations of hotel reservations[cite: 34].
* **`country_codes_and_continents.csv`**: Auxiliary dataset used for geographical analysis.
* **`Python_Project_Group7.pdf`**: The final comprehensive report detailing the methodology and findings.

## Methodology & Results

The analysis utilizes Python libraries (Pandas, Scikit-learn) to process the data.

* [cite_start]**Data Analysis:** The study highlights significant correlations, noting that specific market segments (e.g., Online TA) and seasons (summer) show distinct booking behaviors[cite: 65, 169].
* **Model:** A Decision Tree model was trained and tuned using `GridSearchCV` to prevent overfitting.
* [cite_start]**Performance:** The optimized model (max_depth=10, min_samples_split=2) achieved a test accuracy of **79.39%**[cite: 222].

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
