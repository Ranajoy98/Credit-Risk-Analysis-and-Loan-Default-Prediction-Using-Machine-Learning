# Credit Risk Analysis and Loan Default Prediction Using Machine Learning

## Overview
This project focuses on analyzing credit risk and predicting loan default probabilities using machine learning models. It explores borrower characteristics, evaluates influential factors in loan defaults, and implements predictive models to assess default risk.

## Dataset
The dataset used in this project is **credit_risk_dataset.csv**, which contains various borrower attributes such as:
- Personal details (age, income, employment length)
- Loan-related features (intent, grade, amount)
- Credit history data (default history, credit length)
- Loan status (defaulted or not)

## Libraries Used
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib & Seaborn**: Data visualization
- **Plotly**: Interactive visualizations
- **Scikit-Learn**: Machine learning preprocessing and modeling
- **XGBoost**: Gradient boosting model for classification

## Data Preprocessing
1. **Handling Missing Values**: Null values are removed from the dataset.
2. **Encoding Categorical Features**: Label encoding is applied to categorical variables.
3. **Feature Scaling**: StandardScaler is used to normalize numerical features.
4. **Data Splitting**: The dataset is split into training (80%) and testing (20%) sets.

## Exploratory Data Analysis (EDA)
- Distribution of loan statuses is visualized using a bar chart.
- Box plots analyze how borrower characteristics (age, income, employment length, credit history) impact default risk.
- Insights:
  - Higher income, longer employment, and extended credit history reduce default risk.
  - Younger borrowers or those with limited credit history are more likely to default.

## Machine Learning Models
The following models are implemented:
1. **Random Forest Classifier**
2. **XGBoost Classifier**

### Model Evaluation Metrics
- **Accuracy Score**
- **AUC-ROC Score**
- **Classification Report (Precision, Recall, F1-Score)**
- **Confusion Matrix Visualization**

#### Results:
- Both models achieve **~93% accuracy**.
- **XGBoost performs better** than Random Forest, with a slightly higher recall (73% vs. 69%).
- AUC-ROC scores (~0.85) indicate strong model effectiveness.

## Feature Importance Analysis
- The **Random Forest model** is used to extract feature importance.
- The top 10 influential factors in loan default prediction are visualized using a bar chart.

## Conclusion
- Machine learning can effectively predict loan defaults with high accuracy.
- Income, employment length, and credit history length are significant factors in predicting default risk.
- XGBoost outperforms Random Forest in identifying defaulters.

## Author
**Ranajoy Saha**

## License
This project is licensed under the MIT License.

