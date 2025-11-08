💻 Data Analysis on Laptop Dataset
📘 Overview

This project performs exploratory data analysis (EDA) and machine learning modeling on a laptop dataset to uncover patterns and predict laptop prices based on key features such as brand, processor type, RAM, and storage.

The goal is to build an end-to-end workflow — from data cleaning and visualization to model training and evaluation — demonstrating strong data analytics and regression modeling skills.

🧰 Technologies Used

Python

Pandas, NumPy – Data manipulation and analysis

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine learning models and evaluation

Jupyter Notebook – Interactive development environment

📊 Project Workflow
1. Data Loading
df = pd.read_csv("laptop_data.csv")


The dataset is loaded and explored to understand its structure, size, and data types.

2. Data Preprocessing

Handling missing values

Converting categorical data to numerical using encoding

Feature scaling using StandardScaler

3. Exploratory Data Analysis (EDA)

EDA was performed using Seaborn and Matplotlib to visualize:

Price distribution

Relationships between RAM, CPU, and price

Brand-wise average prices

4. Feature Engineering

Derived or transformed new features such as:

Converting storage details into numerical form

Extracting CPU brand names and series


🚀 Results

✅ Successfully predicted laptop prices with good accuracy.
✅ Discovered that RAM size, CPU brand, and SSD capacity significantly affect price.
✅  Since random forest was good used it for high accuracy !


