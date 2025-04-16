## 🎯 Project Objective:
Predict which customers are likely to churn (stop using the service) and send real-time alerts to the business team.

## 📦 Step-by-Step Project Structure:
1. Data Collection
- Use a sample telecom churn dataset (Kaggle) or simulate your own.
- Include features like:
- customer_id, tenure, monthly_charges, contract_type, support_calls, etc.

2. Exploratory Data Analysis (EDA)
- Identify trends in churned vs. retained customers.
- Visualize correlation between churn and other features.
    
3. Feature Engineering
- Encode categorical variables.
- Create new features like average_call_duration, late_payment_count.

4. Model Training
- Train a classification model (e.g. Random Forest).
- Evaluate with precision, recall, F1, confusion matrix.


## 🔧 Tools & Technologies:
- Python (main language)
- Pandas, NumPy, scikit-learn, XGBoost
- Seaborn, Matplotlib (for EDA/visualizations)
- FastAPI (serve the ML model)
- Excel to store results

## 🔧 Project Setup and Run:
1. Clone project at local machine
2. Install requied python librarry if not installed already
   - pip install pandas
   - pip install numpy
3. Open Project in VS-Code
4. First Run 'notebooks/EDA_and_model_training.ipynb'
