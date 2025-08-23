
# Loan Approval Prediction

This project aims to build a machine learning model to predict whether a loan will be approved based on applicant details such as income, employment status, credit history, and more. The solution is built using Python and leverages popular data science libraries for preprocessing, visualization, and modeling.
It was made in continuation of House Price Prediction (not connected directly but in real life they are connected) to emitate a bigger project.
---

### Dataset

The dataset contains information on loan applicants and whether their loans were approved or not. Downloaded from Kaggle Competition Season 10 episode 4 It includes features like:

- Applicant income
- Loan amount
- Loan term
- Credit history
- Property area
- Gender, marital status, and dependents

Data is typically divided into:
- `train.csv`: For training the model
- `test.csv`: For evaluation/prediction
- `sample_submission.csv`: For Kaggle-style submission format

---

### Libraries Used

- `pandas` and `numpy` – Data manipulation
- `matplotlib`, `plotly` and `seaborn` – Data visualization
- `scikit-learn` – Machine learning models and evaluation
- `xgboost` – Advanced boosting algorithm 

---

### Steps Covered

1. **Data Loading and Exploration**  
   - Understanding feature types and distributions
   - Handling missing values and outliers

2. **Data Preprocessing**  
   - Encoding categorical features  
   - Normalizing numerical features  
   - Splitting data into train/test sets

3. **Model Training**  

4. **Evaluation**  
   - Accuracy, Confusion Matrix, ROC-AUC, etc.

5. **Prediction and Submission**  
   - Generate predictions on test data  
   - Save output in submission format

---

### How to Run

```bash
git clone https://github.com/ndangi168/Loan-Approval-Predication.git
cd Loan-Approval-Predication
jupyter notebook loanApprovalPrediction.ipynb
```

---

### Example Output

Model performance metrics (Accuracy / AUC) will be shown after training.  
Final predictions will be stored in a CSV formatted for competition submission.

---

### TODO (Optional)

- Add more advanced ensemble methods
- Implement hyperparameter tuning
- Deploy using Streamlit or Flask

---

### License

This project is open-source and available under the [MIT License](LICENSE).
