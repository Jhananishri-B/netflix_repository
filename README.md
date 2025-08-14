Netflix Data Analysis:

Overview

This project performs an exploratory data analysis (EDA) on a dataset of Netflix titles. The primary goal is to gain a foundational understanding of the data, including its structure, key characteristics, and distribution of content types. The analysis is conducted using Python with the pandas, numpy, and matplotlib libraries.

Features:

The NETFLIX.ipynb notebook includes the following analysis steps:

Data Loading and Inspection:
The netflix_titles.csv file is loaded into a Pandas DataFrame. The initial rows, shape, column names, and data types are inspected to understand the dataset's structure.

Data Cleaning: 
The code checks for and addresses missing values and duplicate entries to ensure data quality.

Descriptive Statistics: 
The project generates descriptive statistics for both numerical and categorical columns, providing a summary of the data's distribution.

Unique Value Counts:
It counts the number of unique values in each column to understand data cardinality.

Exploratory Data Analysis (EDA):
The notebook includes a bar chart to visualize the distribution of movies versus TV shows and identifies the most frequent country represented in the dataset.

Project Structure
.
├── NETFLIX.ipynb
└── netflix_titles.csv
NETFLIX.ipynb: This is the Jupyter notebook containing all the Python code for data loading, cleaning, and exploratory data analysis.

netflix_titles.csv: 
The dataset used for the analysis, which contains information on various Netflix titles.

Requirements
To run this code, you need to have the following libraries installed in your Python environment:
pandas
numpy
matplotlib

You can install these dependencies using pip:

pip install pandas numpy matplotlib
How to Run the Code
Ensure you have a Jupyter environment set up.

Place the NETFLIX.ipynb file and the netflix_titles.csv dataset in the same directory.

Open the Jupyter notebook from your terminal or JupyterLab.

Run the cells in the notebook sequentially to see the analysis and visualizations.

1)Plot a bar chart for the count of Movies vs TV Shows.

<img width="735" height="563" alt="image" src="https://github.com/user-attachments/assets/81841d59-d0dc-41d7-9f11-02a6f7e230d7" />

2)Scatter plot of release_year vs count of titles.

<img width="817" height="535" alt="image" src="https://github.com/user-attachments/assets/85a99981-f1b8-495f-9b87-66a5f9448b75" />

3)Create a histogram of movie durations (in minutes).

<img width="832" height="560" alt="image" src="https://github.com/user-attachments/assets/993bc748-b96c-4934-a23d-fcf3efaa5f8e" />

4)Bar chart of the number of titles added per year (based on date_added).

<img width="1122" height="713" alt="image" src="https://github.com/user-attachments/assets/8644a5bb-a9b0-4315-9e08-5f572315e98b" />

5)PLOTTING TOP 10 GENERES ON NETFLIX.

<img width="933" height="754" alt="image" src="https://github.com/user-attachments/assets/0aa29f77-9e54-4581-95b0-d9eada7333d3" />




