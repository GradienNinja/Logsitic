# Loan Approval Classification

This project uses **Logistic Regression** to predict loan approval (`loan_status`) based on applicant information.  

The goal is to understand which features influence the approval and build a baseline classification model.

---

## Dataset

The dataset used in this project is from Kaggle:

- **Dataset:** [Loan Approval Classification Data](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data)  
- **Downloaded using:** `kagglehub`  

```python
import kagglehub
# Download latest version
path = kagglehub.dataset_download("taweilo/loan-approval-classification-data")
print("Path to dataset files:", path)
