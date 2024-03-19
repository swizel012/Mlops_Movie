MLOpsMovie
==============================

The movie dataset is collected and explored. Suitable data handling techniques are applied,including handling missing data and outliers appropriately. Feature engineering involving creating additional features and transforming existing features are applied.The dataset is then split into training and testing set for prediction of %Gross. The various other independent features act as independent variables incluencing the success of a movie. The model is then evaluated.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    |                         Linear Regression
    │
    ├── notebooks          <- Jupyter notebooks
    │
    ├── references         <- Data dictionary
    │
    ├── reports            <- Generated analysis as sweetvizHTML
    │   └── figures        <- Generated figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │      └── visualize.py



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
