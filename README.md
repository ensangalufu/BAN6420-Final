# BAN6420-Final
Final assigment for BAN6420
BAN6420 FINAL ASSIGNMENT

Ernest Amon Nsangalufu
Msc in Data Analytics
Leaner ID :144867
Project Overview
This project is part of Final Assignment of the BAN6420 - course and involves  
Implementing t a Flask-based web application designed for data collection in preparation for a healthcare product launch. It stores user data in MongoDB, processes it using Python, and generates visualizations using Pandas and Matplotlib. The app is hosted on AWS

Key Features
1.	Web Application (Flask)
o	A simple webpage built with Flask to collect user details (Age, Gender, Income, Expenses) and store them in MongoDB.

2.	MongoDB Data Storage
o	User data is stored in MongoDB, with expense categories (utilities, entertainment, school fees, shopping, healthcare) and corresponding amounts.

3.	Data Processing
o	A Python class User processes the form data.
o	The data is exported to a CSV file for further analysis.

4.	Data Analysis
o	Load the CSV into a Jupyter Notebook to analyze:
	Highest income by age group.
	Gender distribution across spending categories.

5.	Data Visualization
o	Visualize the results using Matplotlib:
	Bar chart for ages vs. income.
	Pie chart for gender distribution in spending.

6.	AWS Deployment
o	The Flask application is deployed on AWS EC2 for remote access.


Setup Instructions
1.	Install required packages:
`pip install flask pymongo pandas matplotlib`

2.	Run the app:
python app.py

3.	Access the app at http://13.60.207.213/

4.	Open the Jupyter notebook and load the CSV for data visualization.

