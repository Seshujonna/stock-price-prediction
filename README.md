#Stock Price Prediction using Machine Learning
This project aims to predict stock prices using machine learning algorithms based on historical data. The dataset used includes Tesla stock prices, containing features like Open, High, Low, Close, and Volume.

## Project Structure
  Data Collection: The dataset Tesla.csv contains historical stock price data.
  Data Preprocessing: Handled missing values and normalized the data.
  Feature Selection: Key features such as Open, High, Low, Close, and Volume were selected.
  Modeling: Three models were trained: Logistic Regression, Support Vector Classifier (SVC) with polynomial kernel, and XGBoost Classifier.
  Evaluation: The models were evaluated using ROC-AUC score on both training and validation datasets.

## Technologies Used
1. Python
2. Pandas, NumPy
3. Scikit-Learn, XGBoost
4. Jupyter Notebook

## How to Run
1. Install dependencies using pip install -r requirements.txt.
2. Load the dataset using the provided CSV file.
3. Run the Jupyter Notebook to train models and evaluate their performance.

## Results
The models were evaluated based on their ROC-AUC score, showing comparative performance on both training and validation datasets.

## Conclusion
This project demonstrates how machine learning can be used for stock price prediction. Future improvements can include hyperparameter tuning and advanced models like LSTM for time series forecasting.
