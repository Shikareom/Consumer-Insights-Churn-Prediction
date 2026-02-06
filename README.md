# ConsumerInsights: Behavioral Analytics & Churn Prediction System

This project identifies high-risk customers and understands the behavioral triggers behind service cancellation using a Random Forest model.

## 🔗Project Results
* **Accuracy**: 78%
* **Top Drivers**: Total Charges, Tenure, and Monthly Charges
* **Recall**: 47% (Room for improvement by tuning class weights or using SMOTE)

## 🔗File Structure
* `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Raw dataset.
* `churnPrediction.ipynb`: Complete analysis and predictive pipeline.

## 🔗How to Use
1. Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`
2. Run the `churnPrediction.ipynb` notebook to see EDA and model performance.
3. Use the `predict_proba` section at the end to test new customer data.
