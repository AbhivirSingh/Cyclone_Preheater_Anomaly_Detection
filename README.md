# Cyclone Preheater Anomaly Detection

## Overview
This project focuses on anomaly detection in cyclone preheaters using machine learning techniques. The dataset undergoes preprocessing, dimensionality reduction, and anomaly detection using the Isolation Forest algorithm.

## Project Structure
- **Data Preparation**
  - Importing dataset
  - Data cleaning
  - Handling missing values
  - Converting string to float where applicable
  
- **Exploratory Data Analysis (EDA)**
  - Distribution analysis using `distplot`
  - Correlation matrix visualization
  - Pair plots and box plots to identify trends and anomalies

- **Dimensionality Reduction**
  - Principal Component Analysis (PCA) to reduce six dimensions to two
  - Standardizing data using `StandardScaler`
  - 3D visualization of PCA components

- **Model Selection & Anomaly Detection**
  - Implemented Isolation Forest for detecting anomalies
  - Justification: Handles large datasets, robust against distribution assumptions, interpretable, and scalable

## Key Insights
- Highest anomalies occurred in **2017, 2018, and 2019**, peaking in **August and December**.
- **December 2018** recorded the highest anomaly count (>1200 cases).
- Seasonal patterns observed in late-year months.
- Out of **358,833** total records, **18,886** were identified as anomalies.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Open `Cyclone_Preheater.ipynb` and execute the cells sequentially.
3. Analyze the results and visualizations for anomaly detection.

## Contact
For any queries or contributions, feel free to reach out!

---
Thank you for exploring this project!

