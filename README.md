#  Machine Learning: Loan Approval Prediction

### End-to-End Binary Classification Model for Financial Risk Assessment

This project demonstrates a complete Machine Learning workflow, from data preprocessing to model evaluation, focused on building a classification model to predict the likelihood of loan approval. This is crucial for financial institutions to assess risk and automate decision-making.

##  Core ML Workflow and Analysis

The analysis is performed entirely within the `main_notebook.ipynb` file and is designed to run end-to-end without modification.

### Key Steps Performed:
1.  **Data Preprocessing:** Handled missing values, encoded categorical features, and applied log transformations to skewed numeric features.
2.  **Feature Standardization:** Applied standardization to numeric features to prepare them for modeling.
3.  **Data Splitting:** Divided the dataset into training and testing sets.
4.  **Model Training:** Trained and evaluated three classification models: Logistic Regression, Random Forest, and XGBoost.
5.  **Model Evaluation:** Generated comprehensive performance metrics for all models:
    * Accuracy, Precision, Recall, F1 Score, and ROC–AUC.
    * Confusion matrices and ROC curves. 
    * Feature importance plots.

## Software and Reproducibility

### 1. Project Directory Structure
The repository is structured to ensure file paths work universally. The dataset must remain in the `./data` folder.
group-7--project_report/ │ ├── main_notebook.ipynb (The primary analysis file) ├── data/ │   └── loan_approval_dataset.csv │ ├── extra_notebooks/ │   └── pca_analysis.ipynb (Optional PCA exploration) │ └── README.md
### 2. Required Python Packages
The notebook requires the following packages, which can be installed using `pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter`:
* Python 3.10 or higher
* Jupyter Notebook or JupyterLab
* `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`

### 3. How to Run the Project
The notebook is configured for easy reproduction:
1.  Navigate to the project directory in your terminal.
2.  Start Jupyter Notebook by running: `jupyter notebook`
3.  Open `main_notebook.ipynb`.
4.  In Jupyter, select: **Kernel → Restart & Run All Cells**.

***Reproducibility Note:*** The notebook uses `'random_state=42'` for consistent results. All file paths are relative to the project directory.
