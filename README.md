# Internship Selection Prediction Project

## Project Summary
This project uses predictive analytics to determine whether a student is likely to be selected for an internship based on academic performance, technical skills, experience, and interview-related factors.

## Project Objectives
- Explore and clean the internship selection dataset
- Identify key factors that influence internship selection
- Build and compare predictive models
- Evaluate model performance using classification metrics
- Generate insights and recommendations for students and recruiters
- Reflect on ethical considerations in hiring-related predictions

## Dataset Description and Source
Internship Selection Dataset
Source: Included in project repository (/data/Internship_Selection_Dataset.csv)

## Rationale

The Internship Selection Dataset was chosen because it represents a realistic and highly relevant business problem: predicting whether a candidate will be selected for an internship. Organizations today increasingly rely on data-driven approaches to evaluate candidates, considering multiple dimensions such as academic performance, technical skills, experience, and soft skills. This dataset captures these key attributes, including variables like CGPA, coding test scores, interview performance, projects, internships, and communication skills, making it well-suited for predictive modeling.

Additionally, the dataset is non-trivial due to its size (10,000 observations) and the diversity of features, including both numerical and categorical variables. This complexity allows for meaningful exploratory data analysis, data preprocessing, and the application of multiple machine learning models. The dataset supports the development of actionable insights that can help students understand how to improve their employability and assist organizations in making more informed and efficient hiring decisions.

## Exploratory Data Analysis (EDA)
Objective

The goal of the exploratory data analysis (EDA) is to understand the structure of the dataset, identify patterns and relationships between variables, and detect any issues such as outliers or imbalances that may affect modeling decisions.

It contains student-level information such as:
- CGPA
- Skills score
- Projects completed
- Internships completed
- Coding test score
- Interview score
- GitHub score
- College tier
- Placement training
- Selection outcome

**Target variable:** `selected`  
- `1` = Selected  
- `0` = Not selected  

Dataset source: Included in this repository under the `/data` folder.

## Tools and Libraries Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Google Colab Notebook
You can open and run the full analysis here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](Internship_Selection_Model.ipynb)

Direct link: [Internship Selection Colab Notebook](Internship_Selection_Model.ipynb)

## How to Run the Project
1. Open the Google Colab notebook using the link above.
2. Upload the dataset file: `Internship_Selection_Dataset.csv`.
3. Run each code cell from top to bottom.
4. Review the outputs, including:
   - Data cleaning results
   - EDA visualizations
   - Model performance table
   - Confusion matrix
   - Feature importance chart

## Repository Structure
```text
Internship-Selection-Prediction/
│
├── data/
│   └── Internship_Selection_Dataset.csv
│
├── notebooks/
│   └── Internship_Selection_Model.ipynb
│
├── visuals/
│   ├── model_comparison.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── report/
│   └── final_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
