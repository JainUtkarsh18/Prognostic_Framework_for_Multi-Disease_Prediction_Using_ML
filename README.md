# Prognostic_Framework_for_Multi-Disease_Prediction_Using_ML

## Steps for Execution:  
1. **STEP 1:** Data Collection: Source from EHRs, Kaggle, UCI Repository, or public datasets. Include features such as glucose levels, blood pressure, heart rate, etc.
2. **STEP 2:** Data Preprocessing: Handle missing values, normalize data, encode categorical values.
3. **STEP 3:** Model Selection: Train and evaluate models like SVM, Logistic Regression, Random Forest. Choose best model per disease using metrics (Accuracy, F1, Recall).
4. **STEP 4:** Train/Test Split: Use train/test split and cross-validation to avoid overfitting.
5. **STEP 5:** Model Training and Saving: Train the models and serialize them using pickle.     
6. **STEP 6:** Build Streamlit UI: Accept user input and display predictions interactively. 
7. **STEP 7:** Deployment: Deploy locally or on cloud (Streamlit Cloud, Heroku).   
