# XGBoost Optimisation: Used Car Price Prediction

A Project to study Hyperparameter Tuning to improve the model accuracy.



## Project Overview
This project is part of the Coursera Project Network's Hands-On Certification Project.

### Problem Statement:

- Create Machine Learning Models to predict the car price.
- Compare the accuracies with and without the Hyperparameter Tuning.

## Installation & Setup

### Resources Used

- Editor/IDE: Jupyter Notebook
- Environment/Backend: Conda
- Python Version: 3.9

### Python Packages Used

- General Purpose: zipfile, math
- Data Wrangling: numpy, pandas, category_encoders
- Data Visualization: matplotlib, seaborn, plotly.express
- Machine Learning: sklearn, xgboost

## Data
The dataset `used_car_price.csv` is taken from Kaggle.

## Code Structure
```
├── data
│   └── used_car_price.csv
├── src
│   ├── XGBoost-Optimisation.ipynb
│   └── used_car_price.csv
├── .gitignore
└── README.md
```

## Results & Evaluation

### Model Comparison Report

We were able to improve the Model Accuracy after tuning the Hyperparameters of XGBoost Algorithm.

Here is the model comparison report:

| Model | RMSE | R-Squared |
| --- | --- | --- |
| XGBoost - Baseline | 6678.044 | 0.8176 |
| XGBoost - GridSearchCV | 4988.293 | **0.8982** |
| XGBoost - RandomSearchCV | 4988.293 | **0.8982** |

### Conclusion

**XGBoost** is a very powerful algorithm that comes with great default parameters. We were able to improve the accuracy for the `Used_Car_Price` Dataset to **89.82**%.

## Future Work
The same dataset can be treated with other classifiers such as Random Forest Classifier, with Hyperparameter Tuning to compare the results with XGBoost.

## License

[MIT](https://choosealicense.com/licenses/mit/)

