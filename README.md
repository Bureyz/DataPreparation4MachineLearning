# Data Preparation for Machine Learning - Workshop

Training materials for Data Preparation fundamentals in Databricks environment.

## Overview

This training covers essential data preparation techniques for Machine Learning projects using PySpark and Databricks.

**Business Case:** Customer Segmentation for RetailMax - a multi-category retail chain.

## Structure

```
├── demo/                    # Instructor-led demonstrations
│   ├── 00_Setup.ipynb
│   ├── 01_EDA_and_Validation.ipynb
│   ├── 02_Data_Splitting.ipynb
│   ├── 03_Data_Imputing.ipynb
│   ├── 04_Feature_Transformation.ipynb
│   ├── 05_Feature_Engineering.ipynb
│   ├── 06_ML_Pipelines.ipynb
│   ├── 07_Feature_Store_MLflow.ipynb
│   └── 08_GenAI_and_Vector_Search.ipynb
│
├── workshop/                # Hands-on exercises
│   ├── 00_Workshop_Setup.ipynb
│   ├── 01_Workshop_Data_Exploration.ipynb
│   ├── 02_Workshop_Data_Cleaning_and_Features.ipynb
│   └── 03_Workshop_ML_Pipeline.ipynb
│
└── dataset/                 # Sample data
    ├── customers/
    ├── products/
    └── orders/
```

## Topics Covered

| Module | Topic | Key Concepts |
|--------|-------|--------------|
| 1 | EDA & Validation | Data profiling, quality checks, skewness |
| 2 | Data Splitting | Train/Test split, stratification, time-based split |
| 3 | Data Imputing | dropna, fillna, Imputer, missing flags |
| 4 | Feature Transformation | StringIndexer, OneHotEncoder, Scalers |
| 5 | Feature Engineering | Log transform, interaction features, VectorAssembler |
| 6 | ML Pipelines | Spark ML Pipeline, reproducibility |
| 7 | Feature Store & MLflow | Feature tables, model registry |

## Requirements

- Databricks Runtime 14.x LTS or newer
- Unity Catalog enabled
- Python 3.10+

## Workshop Flow

1. Run `00_Workshop_Setup.ipynb` to prepare environment
2. Complete exercises in `01_Workshop_Data_Exploration.ipynb`
3. Clean data in `02_Workshop_Data_Cleaning_and_Features.ipynb`
4. Build ML pipeline in `03_Workshop_ML_Pipeline.ipynb`

## Key Learning Objectives

By the end of this training, participants will be able to:

- Perform exploratory data analysis (EDA) on real-world datasets
- Identify and resolve data quality issues
- Prevent data leakage in ML workflows
- Build customer-level features (RFM analysis)
- Create reproducible ML pipelines in Spark
- Track experiments using MLflow

## License

Internal training materials.
