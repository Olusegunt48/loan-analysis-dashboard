# Loan Interest Rate Analysis Dashboard  

This repository contains an interactive dashboard designed to explore and analyze loan interest rates (`loan_int_rate`) across various borrower demographics, including **age**, **income**, and **homeownership status**. Built with Python using **Dash**, this project provides advanced visualizations and filtering capabilities to uncover trends and insights in loan data.  

## Table of Contents  
1. Overview  
2. Features  
3. Dataset  
4. Installation  
5. Usage  
6. Project Structure  
7. Technologies Used  
8. Contributing  
9. License  

## Overview  
This project is a part of an exploratory data analysis (EDA) task aimed at creating a comparative, interactive dashboard to visualize loan interest rates across key demographic features. The goal is to enable users to filter and explore data trends in real time, supporting better decision-making and identifying patterns that influence loan interest rates.  

## Features  
- **Interactive Visualizations**: Compare loan interest rates (`loan_int_rate`) across borrower demographics.  
- **Advanced Filters**: Filter data by age groups, income levels, and homeownership status.  
- **Real-Time Insights**: Dynamically update charts and visualizations using Dash callbacks.  
- **User-Friendly Interface**: Simplified navigation and interaction for both technical and non-technical users.  

## Dataset  
The dataset used for this project contains information about loans, including:  
- `loan_int_rate`: Loan interest rates.  
- Borrower demographics: `age`, `income`, `homeownership_status`, etc.  

### Data Preprocessing  
- Handled missing values using **group-based imputation**.  
- Detected and addressed outliers using **Interquartile Range (IQR)**.  
- Verified the distribution of numerical columns through skewness, kurtosis, and visualization.  
- Converted column headers to lowercase for consistency.  

## Installation  
To set up the project on your local machine, follow these steps:  
1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/loan-int-rate-dashboard.git  
   cd loan-int-rate-dashboard  
