This project analyzes the Heart Failure Clinical Records Dataset using various machine learning models to determine feature importance.
# Dataset

The dataset used is heart_failure_clinical_records_dataset.csv, which contains clinical records for heart failure patients, thanks to *[UCI](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)*.

# Features
Data preprocessing and visualization
Model training using:
Random Forest, 
Gradient Boosting, 
Decision Tree, 
Logistic Regression, 
Feature importance analysis and visualization

# Requirements
All required Python packages are listed in requirements.txt.

# How to Run
**1. Clone the repository:**

```sh
git clone https://github.com/AliG2008/ML-with-HF.git
cd ML-with-HF
```
**2. Create and activate a virtual environment (recommended):**

```sh
python -m venv env
.\env\Scripts\Activate.ps1
```
**3. Install dependencies:**

```sh
pip install -r requirements.txt
```

**4. Run the analysis:**

  -Open heart_failure.ipynb in Jupyter Notebook or VS Code.
  
  -Run all cells to execute the analysis and view results.

# Notes
Make sure the dataset file (heart_failure_clinical_records_dataset.csv) is present in the project directory.
The notebook visualizes feature importances for each model.

