Loan Interest Rate Analysis Dashboard

Table of Contents
Introduction
Features
Dataset
Installation
Usage
Exploratory Data Analysis (EDA)
Interactive Dashboard
Project Structure
Technologies Used
Contributing
License
Contact
Introduction
Welcome to the Loan Interest Rate Analysis Dashboard repository! This project aims to provide insightful analysis and interactive visualizations of loan interest rates across various borrower demographics such as age, income, and homeownership status. By leveraging Python's powerful data analysis libraries and Plotly Dash for interactive dashboards, this project enables stakeholders to make informed decisions based on comprehensive data exploration.

Features
Data Cleaning & Preprocessing: Handles missing values, duplicates, and ensures data consistency.
Exploratory Data Analysis (EDA): Provides statistical summaries and visualizations to uncover patterns and trends.
Interactive Dashboard: An intuitive web-based dashboard built with Dash, allowing users to filter and explore loan interest rates by key demographics in real-time.
Outlier Detection: Identifies and manages outliers to enhance data quality and model performance.
Normality Assessment: Evaluates the distribution of numerical features to inform further analysis.
Dataset
The dataset used in this project is a preprocessed loan dataset containing the following key features:

Age: Age of the borrower.
Income: Annual income of the borrower.
Homeownership Status: Type of home ownership (e.g., Rent, Own, Mortgage).
Employment Length: Duration of the borrower's employment.
Loan Intent: Purpose of the loan (e.g., Education, Medical, Venture).
Loan Grade: Credit grade of the loan.
Loan Amount: Amount of loan requested.
Interest Rate: Interest rate (%) of the loan.
Loan Status: Indicates whether the loan is in default (1) or not (0).
Income Percentage: Loan amount as a percentage of income.
Default History: Indicates if there's a default history (Yes/No).
Credit History Length: Length of credit history in years.
Note: Ensure that you have the preprocessed_data.csv file in the repository or provide instructions to obtain it.

Installation
To get started with this project, follow the steps below to set up your environment.

Prerequisites
Python 3.7 or higher
Pip (Python package installer)
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/loan-int-rate-dashboard.git
cd loan-int-rate-dashboard
Create a Virtual Environment (Optional but Recommended)
bash
Copy code
python -m venv venv
Activate the virtual environment:

Windows:
bash
Copy code
venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies
bash
Copy code
pip install -r requirements.txt
If requirements.txt is not present, you can install the necessary packages manually:

bash
Copy code
pip install pandas matplotlib seaborn plotly dash dash-bootstrap-components scikit-learn
Usage
Exploratory Data Analysis (EDA)
The EDA is conducted in a Jupyter Notebook named complete_EDA.ipynb. This notebook includes data cleaning, statistical analysis, and visualizations to understand the dataset better.

Launch Jupyter Notebook:

bash
Copy code
jupyter notebook
Open complete_EDA.ipynb:

Navigate to the notebook and run the cells sequentially to perform the analysis.

Interactive Dashboard
The interactive dashboard is built using Plotly Dash and can be run as a standalone Python script in VSCode or any Python IDE.

Navigate to the Dashboard Script:

Ensure you are in the repository directory.

Run the Dashboard Script:

bash
Copy code
python app.py
Access the Dashboard:

Open your web browser and go to http://127.0.0.1:8050 to view and interact with the dashboard.

Dashboard Features
Homeownership Filter: Select one or multiple homeownership statuses to filter the data.
Age Range Slider: Adjust the age range to focus on specific borrower age groups.
Income Range Slider: Filter borrowers based on their income range.
Interactive Plots: Visualize loan_int_rate distributions and comparisons across selected demographics.
Ensure that the credit_risk_dataset.csv file is present in the repository or provide the correct path in the script.

Project Structure
arduino
Copy code
loan-int-rate-dashboard/
├── app.py
├── complete_EDA.ipynb
├── credit_risk_dataset.csv
├── requirements.txt
├── README.md
├── LICENSE
└── assets/
    └── styles.css
app.py: Python script to run the Dash interactive dashboard.
complete_EDA.ipynb: Jupyter Notebook containing the EDA.
preprocessed_data.csv: Cleaned and preprocessed dataset.
requirements.txt: List of Python dependencies.
README.md: Project documentation.
LICENSE: Licensing information.
assets/styles.css: Custom styles for the dashboard (optional).
Technologies Used
Python: Programming language for data analysis and dashboard creation.
Pandas: Data manipulation and analysis.
Matplotlib & Seaborn: Data visualization libraries for EDA.
Plotly Dash: Framework for building interactive web dashboards.
Scikit-learn: Machine learning library for data preprocessing.
VSCode: Integrated development environment for coding.
Contributing
Contributions are welcome! If you have suggestions or improvements, please follow the steps below:

Fork the Repository

Create a New Branch

bash
Copy code
git checkout -b feature/YourFeatureName
Commit Your Changes

bash
Copy code
git commit -m "Add your message here"
Push to the Branch

bash
Copy code
git push origin feature/YourFeatureName
Open a Pull Request


Contact
Oluwasegun Oladipupo

Email: oluwasegunt48@gmail.com
Feel free to reach out for any questions, feedback, or collaboration opportunities!

Thank you for checking out the Loan Interest Rate Analysis Dashboard! We hope this tool provides valuable insights and aids in your decision-making processes.
