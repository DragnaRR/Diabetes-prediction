
# Diabetes Prediction using Random Forest & XGBoost

The aim is to predict about diabetes based on features like pregnancy, glucose concentration,
blood pressure, thickness, insulin, BMI, age and skin. 

It a comparison between 2 algorithms for binary classification, determining which works better for 
predicting the output 1 or 0 (Diabetes or not)

## Requirement
- Python 3.7.3
Required libraries:

- numpy 1.16.2
- pandas 0.24.2
- sklearn 0.20.3
- seaborn 0.9.0
- matplotlib 3.0.3
- xgboost 1.7.3
## Dataset
The PIMA Indians Diabetes (PID) dataset was used to train and evaluate the models. 
It has data of Pima Indians community near Phoenix, Arizona, which has 768 female patients with diabetes. 
There are 500 non-diabetic patients (negative) and 268 diabetic patients (positive) and in this dataset,
each with nine separate attributes. Table shows the attribute definitions as well as a short statistical overview.

| Features  | Mean ± std    | 
| :-------- | :------- | 
| Pregnant (F1) | 3.8 ± 3.37 |
| Glucose conc (F2) | 120.89 ± 31.97 |
| Blood Pressure (F3) | 69.10 ± 19.36 |
| Thickness (F4) | 20.54 ± 15.95 |
| Insulin (F5) | 79.81 ± 115.24 |
| BMI (F6) | 31.99 ± 7.88 |
| Pedigree (F7) | 0.47 ± 0.33 |
| Age (F8) | 33.24 ± 11.76 |
| Skin (F9) | 0.81 ± 0.63 |

[Link to the dataset](https://www.kaggle.com/datasets/kumargh/pimaindiansdiabetescsv)

## Flow Chart

![Flow Chart](https://github.com/DragnaRR/Diabetes-prediction/assets/95096810/a17c8b9f-f754-436e-9c0a-c317071c2926)







## Confusion matrix
In the confusion matrix, the rows represent the target classes and the columns the output classes for the testing target data set. The diagonal cells in each table show the number of correctly classified cases, and the off-diagonal cells show the misclassified instances.

![confusion matrix](https://github.com/DragnaRR/Diabetes-prediction/assets/95096810/c58e5acd-0388-40f3-9fc5-e4d8162cdf44)

[Link to the paper](http://www.tjprc.org/search.php)

[Download Paper](https://github.com/DragnaRR/Diabetes-prediction/files/11838083/paper.pdf)
