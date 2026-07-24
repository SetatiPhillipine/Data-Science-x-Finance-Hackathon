# User Manual

# Finance Fraud Detection System

**Project:** Data Science Club Finance & Digital Innovation Hackathon

**Version:** 1.0

**Team:** Fraud Detection Team

---

# Table of Contents

1. Introduction
2. System Overview
3. System Requirements
4. Software Installation
5. Project Setup
6. Running the Machine Learning Model
7. Running the React Dashboard
8. Using the System
9. Understanding the Results
10. Troubleshooting
11. Frequently Asked Questions
12. Conclusion

---

# 1. Introduction

Welcome to the Finance Fraud Detection System.

This system uses Data Science and Machine Learning techniques to analyse financial transaction data and identify potentially fraudulent transactions. The project was developed for the Data Science Club Finance & Digital Innovation Hackathon and demonstrates how machine learning can assist financial institutions in detecting suspicious activities.

---

# 2. System Overview

The system consists of four main components:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning Model
- React Dashboard

The workflow is illustrated below:

Transaction Dataset

↓

Data Cleaning

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Machine Learning Model

↓

Fraud Prediction

↓

React Dashboard

↓

Business Insights

---

# 3. System Requirements

## Hardware Requirements

- Windows 10 or later
- 8 GB RAM or higher
- Intel Core i5 / AMD Ryzen 5 (or equivalent)
- At least 2 GB free disk space

---

## Software Requirements

Install the following software before running the project:

- Python 3.12 or later
- Jupyter Notebook
- Visual Studio Code
- Git
- Node.js
- npm

---

## Python Libraries

Install all required Python packages using:

```bash
pip install -r requirements.txt
```

The project uses:

- pandas
- numpy
- matplotlib
- scikit-learn
- joblib
- openpyxl

---

# 4. Software Installation

## Step 1

Clone the GitHub repository.

```bash
git clone https://github.com/YourUsername/Fraud-Detection-System.git
```

---

## Step 2

Navigate to the project folder.

```bash
cd Fraud-Detection-System
```

---

## Step 3

Install the required Python libraries.

```bash
pip install -r requirements.txt
```

---

## Step 4

Open Jupyter Notebook.

```bash
jupyter notebook
```

If using JupyterLab:

```bash
jupyter lab
```

---

# 5. Project Setup

The project folder is organised as follows:

```
Fraud-Detection-System/

├── data/
├── docs/
├── notebooks/
├── src/
├── dashboard/
├── models/
├── images/
├── presentation/
├── README.md
└── requirements.txt
```

Place the transaction dataset inside:

```
data/raw/
```

---

# 6. Running the Machine Learning Model

Open the notebooks in the following order:

1. 01_Data_Exploration.ipynb
2. 02_Data_Cleaning.ipynb
3. 03_EDA.ipynb
4. 04_Model_Training.ipynb
5. 05_Model_Evaluation.ipynb
6. Final_Model.ipynb

Run every notebook from top to bottom.

After the final notebook completes, the trained model will be saved inside:

```
models/
```

Example:

```
trained_model.pkl
```

---

# 7. Running the React Dashboard

Navigate to the dashboard frontend folder.

```bash
cd dashboard/frontend
```

Install dependencies.

```bash
npm install
```

Start the development server.

```bash
npm start
```

The dashboard will normally open at:

```
http://localhost:3000
```

If the project includes a backend API:

Navigate to:

```bash
dashboard/backend
```

Install dependencies.

```bash
npm install
```

Start the backend server according to the framework used (for example, Flask, FastAPI, or Express).

---

# 8. Using the System

## Step 1

Load the transaction dataset.

---

## Step 2

Run the data cleaning notebook.

---

## Step 3

Perform Exploratory Data Analysis.

Review the generated charts and identify fraud patterns.

---

## Step 4

Train the machine learning model.

---

## Step 5

Evaluate model performance.

Review:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## Step 6

Open the React Dashboard.

Review:

- Total transactions
- Fraudulent transactions
- Legitimate transactions
- Fraud percentage
- Charts and graphs
- Model evaluation metrics
- Fraud predictions

---

# 9. Understanding the Results

The dashboard displays:

## Fraud Statistics

Shows the number of fraudulent and legitimate transactions.

---

## Charts

Visualise transaction trends and fraud distribution.

---

## Machine Learning Metrics

Displays:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Higher values generally indicate better model performance.

---

## Predictions

Transactions are classified as either:

- Fraudulent
- Legitimate

The prediction results assist analysts in prioritising investigations.

---

# 10. Troubleshooting

## Problem

ModuleNotFoundError

### Solution

Install missing packages.

```bash
pip install package_name
```

---

## Problem

Notebook does not open.

### Solution

Restart Jupyter Notebook and verify that it is installed correctly.

---

## Problem

React application will not start.

### Solution

Run:

```bash
npm install
```

Then:

```bash
npm start
```

---

## Problem

Dataset cannot be found.

### Solution

Verify that the dataset has been placed inside:

```
data/raw/
```

---

## Problem

Model does not produce predictions.

### Solution

Ensure that:

- Data cleaning completed successfully.
- Model training completed successfully.
- The trained model file exists inside the models folder.

---

# 11. Frequently Asked Questions

## What type of file should the dataset be?

CSV format.

---

## Which notebook should I run first?

01_Data_Exploration.ipynb

---

## Can the system analyse new datasets?

Yes, provided the new dataset follows the same structure used during model training.

---

## Which machine learning model is used?

The project may include Logistic Regression, Random Forest, Decision Tree, or another classification model selected during the hackathon.

---

## Where are the trained models stored?

```
models/
```

---

# 12. Conclusion

The Finance Fraud Detection System demonstrates how machine learning and data science can assist financial institutions in identifying suspicious transactions and reducing fraud-related losses.

By following this user manual, users can install the project, execute the machine learning workflow, launch the dashboard, and interpret the generated results. The modular design and comprehensive documentation make the system easy to understand, maintain, and extend for future enhancements.
