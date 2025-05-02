Customer Churn Analysis Project
Project Overview

This project analyzes customer churn using a telecom dataset. The main objective is to identify factors influencing customer churn and to build a predictive model that can classify customers as likely to churn or not. The analysis is performed in a Jupyter Notebook and includes data exploration, preprocessing, and modeling steps. Note: The model is not deployed as an application or API; all work is contained within the notebook.

Dataset

Source: /content/churn-bigml-80 (1).csv

Rows: 2666

Columns: 20

Target Variable: Churn (0 = No churn, 1 = Churn)

Key Features:

State, Account length, Area code

International plan, Voice mail plan, Number vmail messages

Total day/eve/night/intl minutes, calls, and charges

Customer service calls

Project Structure

Data Loading: Uses pandas to read the CSV file.

Exploratory Data Analysis: Summarizes data, checks for missing values, and explores distributions.

Feature Engineering: Encodes categorical variables (e.g., International plan, Voice mail plan) and creates new features as needed.

Modeling: Trains machine learning models to predict churn (details of the models not included in the snippet).

Visualization: Uses matplotlib and seaborn for data visualization.

Requirements

Python 3.x

Jupyter Notebook

Libraries:

numpy

pandas

matplotlib

seaborn

Install dependencies with:

bash
pip install numpy pandas matplotlib seaborn
Usage

Clone or download the repository containing the notebook and dataset.

Open customer_churn.ipynb in Jupyter Notebook.

Run all cells sequentially to perform the analysis.

Note: The model is not deployed as a web or REST API. All results are viewable within the notebook.

File Structure

text
customer_churn/
├── customer_churn.ipynb
└── churn-bigml-80 (1).csv




