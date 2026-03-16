
# Data Preprocessing Engine

This project is about making a data preprocessing engine. We use Python and Scikit-Learn for this. The goal is to automate data preprocessing tasks. We want to build a pipeline that prepares raw datasets for machine learning.

## Project Objective

Real-world datasets often have problems. They have missing values, categorical variables, inconsistent formats and features that need scaling.

This project finds those issues through data analysis. We implement an automated preprocessing pipeline to handle them.

The result is a workflow. It converts datasets into a clean numerical format. This format is suitable for machine learning models.

## Workflow

The project follows steps:

1. We audit the data.

2. We analyze feature values.

3. We decide on a missing value handling strategy.

4. We. Encode features.

5. We construct a preprocessing pipeline.

Each step is in a notebook. This keeps the workflow modular and easy to understand.

## Preprocessing Techniques

The preprocessing pipeline does the following:

- It imputes missing values for features.

- It imputes missing values for features.

- It handles variables using One-Hot Encoding.

- It scales features using StandardScaler.

- It transforms columns using ColumnTransformer.

- It automates preprocessing using Scikit-Learn Pipelines.

## Project Structure

```

data-preprocessing-engine/

│

├── README.md

├── requirements.txt

│

├── data/

│   ├── raw/

│   │   └── adult.csv

│   │

│   └── processed/

│       └── adult_preprocessed.csv

│

├── notebooks/

│   ├── 01_raw_data_audit.ipynb

│   ├── 02_feature_value_analysis.ipynb

│   ├── 03_missing_value_handling_strategy.ipynb

│   ├── 04_feature_parsing_encoding_analysis.ipynb

│   └── 05_preprocessing_pipeline_engine.ipynb

│

└── pipelines/

└── preprocessing_pipeline.pkl

```

## Technologies Used

- Python

- Pandas

- NumPy

- Scikit-Learn

- Matplotlib

- Seaborn

- Joblib

## Output

The project produces two things:

1. A processed dataset ready for machine learning.

2. A serialized preprocessing pipeline (`preprocessing_pipeline.pkl`). We can reuse this to transform datasets consistently.

## Author

This project was developed as part of a machine learning workflow. The focus is, on building a reusable data preprocessing pipeline.