# Loan Approval Prediction
![Image_Alt]()

# 📌Project Overview

This project is a Loan Approval Prediction System that utilizes Machine Learning algorithms to predict whether a loan application should be approved. The model is trained on various financial and demographic features to assess creditworthiness.

# 📊Dataset

The dataset contains the following key attributes:

- **Applicant Income**: The monthly income of the applicant
- **Co-applicant Income**: Monthly income of co-applicant (if any)
- **Loan Amount**: Requested loan amount
- **Loan Amount Term**: Duration of the loan in months
- **Credit History**: Applicant’s credit history (0 or 1)
- **Property Area**: Urban, Semi-Urban, or Rural Marital Status, Gender, Education, Self-Employed: Demographic information

# 🛠️Technologies Used

- Python
- Pandas & NumPy (Data preprocessing)
- Matplotlib & Seaborn (Data visualization)
- Scikit-learn (Machine Learning models)
- Jupyter Notebook (Development environment)

  # 📌Steps Followed

1. **Data Preprocessing**
   
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling 

3. **Exploratory Data Analysis (EDA)**

    - Understanding feature distributions
    - Identifying correlations

4. **Model Selection & Training**

   - Used Random Forest, Logistic Regression, and Decision Trees
   - Evaluated models using accuracy, precision, recall, and F1-score

4. **Model Evaluation**

   - Optimized hyperparameters for best performance
   - Compared different ML models

# 📌Results & Insights

- The best model achieved 85% accuracy in predicting loan approvals.

- The feature importance analysis showed that credit history and applicant income were key predictors.

# 🔥Future Enhancements

- Deploy the model using Flask or FastAPI.

- Improve accuracy with ensemble models.

- Integrate with real-time data sources.
