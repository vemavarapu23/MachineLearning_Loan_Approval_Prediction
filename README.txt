
How to Run 'main_notebook.ipynb'

1. Project Directory Structure

After unzipping the submitted file, the directory should have the following structure:

  
group-7--project_report/
│
├── project_report.pdf
├── main_notebook.ipynb
├── main_notebook.html
│
├── data/
│   └── loan_approval_dataset.csv
│
├── extra_notebooks/
│   └── pca_analysis.ipynb
│
└── README.txt

The dataset must remain in the './data' folder.
The notebook loads the file using a relative path, so no changes are necessary.

---------------------------------------------------------------------------------------------

2. Software Requirements

The notebook requires the following Python packages:

* Python 3.10 or higher
* Jupyter Notebook or JupyterLab
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* xgboost

These can be installed using:
  
pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter

---------------------------------------------------------------------------------------------

3. Opening the Notebook

1. Navigate to the project directory (the folder containing this README).
2. Start Jupyter Notebook:

jupyter notebook

3. Open:

main_notebook.ipynb

---------------------------------------------------------------------------------------------

4. Running the Notebook

The notebook is designed to run end-to-end without modification.

In Jupyter, select:

Kernel → Restart & Run All Cells

Running all cells will automatically:

1. Load the dataset from './data/loan_approval_dataset.csv'
2. Perform basic dataset auditing
3. Encode categorical variables ('education', 'self_employed', 'loan_status')
4. Apply log transformations to skewed numeric features
5. Standardize numeric features
6. Split the dataset into training and testing sets
7. Train and evaluate:

   * Logistic Regression
   * Random Forest
   * XGBoost
8. Generate:

   * Accuracy, Precision, Recall, F1 Score, ROC–AUC
   * Confusion matrices
   * ROC curves
   * Feature importance plots

All file paths are relative to the project directory, so the notebook can run on any machine that preserves the folder structure shown above.

---------------------------------------------------------------------------------------------

5. Reproducibility Notes

* The notebook uses 'random_state=42' for consistent, repeatable results.
* No external data sources or internet access are required.
* If errors occur, confirm:

  * The dataset is located at './data/loan_approval_dataset.csv'
  * The Python packages listed above are installed
  * The folder structure has not been modified

---------------------------------------------------------------------------------------------

6. Extra Notebooks

The './extra_notebooks' folder includes:

 pca_analysis.ipynb
  This notebook contains optional PCA exploration performed during the project.
  It is not required for running the main project code.

---------------------------------------------------------------------------------------------

7. Utils Folder

No 'utils/' folder is included, as no helper code files were used.

---------------------------------------------------------------------------------------------

8. Contact

If the notebook does not run as expected, ensure the folder structure and file locations match this README.

---------------------------------------------------------------------------------------------

