# mobile-price-range-predictor
EDA and Model Building for determining mobile phones price ranges

1.Data Preparation:
  * Load train.csv and test.csv.
  * Clean and preprocess data (handle missing values, duplicates, etc.).

2.Dataset Analysis:
  * Analyze train.csv in DatasetAnalysis.ipynb (e.g., distributions, correlations).
  * Save insights in DatasetAnalysis_csv.csv.

3.Data Scaling:
  * Scale train.csv in ScaledDataSet.ipynb using sklearn.
  * Save the scaled data to ScaledDataSet.csv.

4.Model Training:
  * Use ScaledDataSet.csv in ModelTranning.ipynb.
  * Split data into training and validation sets and train the model.

5.Model Testing:
   * Load test.csv to evaluate model performance on unseen data.
