# Student Score Prediction

You are part of an AI Engineering team in AI Singapore (AISG) that builds AI solutions to solve
problem statements from the public and private sectors. Your current client is U.A Secondary School, a public educational institute in Singapore.
U.A Secondary School wants AISG to build a model that can predict the students’ O-level mathematics examination scores to identify weaker students prior to the examination timely.

Additional support can then be rendered to the students to ensure they are more prepared for the upcoming test. You are given access to U.A Secondary School's past students’ performance dataset (a link to retrieve the dataset can be found in the Data section below).

With the given dataset, you are to perform the following two tasks:
1. Exploratory Data Analysis
2. Build an End-to-end Machine Learning Pipeline

Task 1 - Exploratory Data Analysis (EDA)
Using the given dataset, which can be found in the Data section below, conduct an EDA and create an interactive notebook in Python that can be used as a presentation to explain the findings of your analysis. You should employ appropriate visualizations and statistical techniques to derive meaningful and relevant insights from the dataset.

Task 2: End-to-end Machine Learning Pipeline (MLP)
 The MLP should entails:
   ● Appropriate data preprocessing and feature engineering
   ● Appropriate use and optimization of algorithms/models (at least 3 models)
   ● Appropriate explanation for the choice of algorithms/models
   ● Appropriate use of evaluation metrics
   ● Appropriate explanation for the choice of evaluation metrics


1) 🏗 High-Level Architecture of Your ML Pipeline

            project_root/
            │
            ├── data/
            │   └── score.db
            │
            ├── notebook/
            │   └── Student_Score.ipynb
            │
            │
            ├── environment.yml
            ├── README.md


2) Logical Flow of the Pipeline

1. Load data from SQLite
2. Clean + preprocess
3. Feature engineering
4. Train-test split
5. Model training (≥ 3 models)
6. Hyperparameter tuning
7. Evaluation
8. Save best model