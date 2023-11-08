# Predict Customer Churn

- Project **Predict Customer Churn** of ML DevOps Engineer Nanodegree Udacity

## Project Description
This project aims to identify customers that are most likely to churn based on credit card. This is a clean version of `churn_notebook.ipynb`. The completed project will include a Python package that follows coding (PEP8) and engineering best practices.

## Files and data description
- Folders
    - Data      --> contains the dataset in csv format
    - images 
        - eda       --> contains output of the data exploration
        - results   --> contains model scores, confusion matrix, ROC curve
    - models        --> contains saved models in .pkl format
    - logs          --> log generated druing testing of library.py file

    - churn_library.py --> A library of functions to find customers who are likely to churn.
    - churn_notebook.ipnyb --> interactive lines of code to find customers who are likely to churn.
    - requirements.txt --> python package list which are using in this project
    - test_churn_script_logging_and_tests.py 
        - Contain unit tests for the *churn_library.py* functions. 
        - Log any errors and INFO messages. 
## Running Files

1. Install packages:
```bash
pip install -r requirements.txt
```
3. Run churn prediction:
```bash
python churn_library.py
```
4. Test churn prediction:
```bash
pytest  test_churn_script_logging_and_tests.py
```




