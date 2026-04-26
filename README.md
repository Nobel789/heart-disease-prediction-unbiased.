# Heart Disease Prediction with an Unbiased Healthcare Dataset

This repository presents a healthcare machine learning project focused on predicting heart disease from a curated dataset designed to reduce demographic bias. The project emphasizes both predictive modeling and fairness awareness, making it relevant to healthcare analytics, public health, and responsible AI in medicine.

## Why This Project Matters

Heart disease prediction is a widely used healthcare machine learning problem, but model quality depends heavily on the quality and representativeness of the data. A dataset that over-represents or under-represents certain groups can lead to unfair or less reliable outcomes.

This project highlights a fairness-aware approach by working with a cleaned and more balanced medical dataset and by paying attention to demographic fields such as age, gender, race, and insurance status.

## Project Overview

The project uses a dataset of **8,301 patient records** to study heart disease prediction in a healthcare setting. In addition to predictive modeling, the workflow includes privacy, data quality, and fairness considerations.

## Key Features

- **Privacy-aware preparation**: sensitive identifiers such as `PatientID` are removed.
- **Data quality checks**: the dataset is reviewed for missing values and basic consistency.
- **Fairness-focused framing**: demographic and socioeconomic fields are considered to reduce bias risk.
- **Healthcare relevance**: the problem is directly aligned with clinical risk prediction and health data analysis.

## Dataset Highlights

The project references healthcare variables such as:

- `Gender`
- `Age`
- `Race`
- `Insurance`

These variables are important not only for prediction, but also for understanding whether a model may behave differently across patient groups.

## Typical Workflow

This project is structured around a standard healthcare ML pipeline:

1. Load and inspect the medical dataset
2. Remove sensitive or unnecessary identifiers
3. Check for missing values and basic quality issues
4. Explore demographic and clinical variables
5. Prepare data for prediction
6. Train and evaluate a heart disease prediction model
7. Review the project from a fairness and healthcare perspective

## Tech Stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Skills Demonstrated

- healthcare data cleaning
- fairness-aware analysis
- clinical risk prediction
- exploratory data analysis
- machine learning on structured medical data
- privacy-conscious preprocessing

## Who This Project Is For

This repository is especially relevant for:

- healthcare data analyst portfolios
- public health data projects
- beginner machine learning roles in healthcare
- fairness-aware medical AI case studies

## Portfolio Value

This project is a good portfolio piece because it does more than standard heart disease classification. It also shows awareness of real healthcare issues such as data quality, patient privacy, and bias across demographic groups.

## Future Improvements

Potential next steps for the project include:

- adding model evaluation metrics such as accuracy, recall, F1-score, and ROC-AUC
- comparing multiple machine learning models
- adding visualizations for subgroup analysis
- documenting limitations of fairness claims more explicitly
- including a deployment demo or simple prediction app
