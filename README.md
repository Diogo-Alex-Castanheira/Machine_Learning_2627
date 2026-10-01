MACHINE LEARNING

PLATYPUS CONSISTENCY

SEPTEMBER, 2026

I. INTRODUCTION

This homework is designed to help you with the final project by completing a compact version of the same workflow. You will work with the Everything & Then Some repeat-purchase data. Using train.csv and, if useful, the auxiliary clientes.csv table, you must explore and prepare the data, perform feature selection, build a simple binary-classification model, assess its performance, and generate predictions for test.csv.

II. DELIVERABLES

The deliverables for this task are:

Jupyter Notebook (or a zip of multiple notebooks) with your code and markdown comments inside.

A 2-page PDF file describing your project’s overall structure and rationale.

The file naming convention should follow Homework_GroupXX, where GroupXX should be your group number.

III. TASK & EVALUATION

Notebook:

1. Import and explore the data (3 points) Inspect train.csv and, if useful, clientes.csv. Describe the observations and variables, provide descriptive statistics, check data quality and inconsistencies, and explore relevant univariate and multivariate relationships. Explain the insights you obtain.

2. Clean and pre-process the data (5 points) Identify and handle missing values and anomalous or implausible observations. Deal with categorical variables. Decide whether and how the optional clientes.csv table should be integrated through customer_id. Review the supplied variables and create additional features if useful. Apply scaling when appropriate and justify your choices. All preprocessing decisions used for modelling must be reproducible and must not use information from test.csv to fit transformations.

3. Feature selection (3 points) Define and implement a clear feature-selection strategy using methods discussed in class. Present and justify the final feature set. Identifier-like variables should be treated critically rather than accepted automatically.

4. Build a simple model and assess performance (4 points) Treat the task as binary classification: predict repeat_purchase_90d. Choose an assessment strategy and suitable classification metric(s), explain why they fit the problem, train at least one model using train.csv, and generate predictions for every observation in test.csv. Keep ID unchanged so predictions can be submitted in the sample_submission.csv format.

(Extra 1 point) Be among the Top-5 Best Groups in the Kaggle Competition.

PDF file:

5. Describe the overall structure of your pipeline (5 points) Provide a schematic representation of the main stages and techniques in your pipeline. Summarise the preprocessing, optional customer-data integration, feature selection, modelling and assessment choices, and explain why each step is appropriate.

Readability and consistency will be considered during grading, so include sufficient comments and maintain a well-defined structure throughout your work.

Final grade = min(20, your points) Deadline: 26.10.2026 - 17:59
