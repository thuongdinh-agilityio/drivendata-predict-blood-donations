# Drivendata Warm Up: Predict Blood Donations

This project try to solve the competition [Warm Up: Predict Blood Donations](https://www.drivendata.org/competitions/2/page/5/)

## How to run

### Requirements
 
 - Python
 - Anacoda
 - xgboost 0.4.0 (install with conda: conda conda install -c aterrel xgboost=0.4.0)
 - scikit-learn 0.16

### Steps

1. $ cd <repo path>
2. $ jupyter notebook
3. Go to browser and enter http://localhost:8888 to access notebooks

## Folder structure

1. data: contains train.csv for machine learning and test.csv for create submission.
2. results: submission results.
3. helper: helper methods for loading and processing data.
4. 01_data_exploration_v01.ipynb: data exploration.
5. 02_machine_learning_v01.ipynb: baseline and essemble machine learning (GradientBoostingClassifier as final model).
6. 03_machine_learning_xgboost_v01.ipynb: xgboost machine learning (XGBClassifier as final model).
7. 04_machine_learning_apply_process_v01.ipynb: try to apply monitoring learning process for some models (SVC as final model).

## Performance summary

1. XGBClassifier: Log loss = 0.4550, 361/2058 (top 17%).
2. SVC: Log loss = 0.4988, 425/2056 (top 24%).
3. GradientBoostingClassifier: Log loss = 0.5194, 642/2022 (top 31%).