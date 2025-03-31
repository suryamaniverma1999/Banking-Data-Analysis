📊 Banking Data Analysis Project

📝 Overview

This project analyzes a publicly available banking dataset to uncover patterns in customer behavior, marketing effectiveness, and financial trends. It includes data cleaning, exploratory data analysis (EDA), visualizations, and predictive modeling.

📂 Project Structure

/Banking-Data-Analysis
  /data              # Raw & cleaned datasets
  /notebooks        # Jupyter notebooks for step-by-step analysis
  /scripts          # Python scripts for automation
  /images          # Visualizations & plots
  /reports         # Summary reports & insights
  README.md        # Project documentation
  requirements.txt # Python dependencies
  .gitignore       # Ignored files

📊 Dataset Information

Source: Banking Dataset - Marketing Targets

Description: Contains customer demographics, account details, and responses to marketing campaigns.

Key Features:

age, job, marital, education, balance (Customer details)

loan, housing, contact, duration (Financial status)

campaign, previous, poutcome (Marketing campaign details)

y (Target variable - whether the customer subscribed to the term deposit)

🛠 Setup & Installation

# Clone the repository
git clone git@github.com:suryamaniverma1999/Banking-Data-Analysis.git
cd Banking-Data-Analysis

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

🚀 Running the Analysis

# Step 1: Data Cleaning
python scripts/data_cleaning.py

# Step 2: Exploratory Data Analysis (EDA)
python scripts/exploratory_analysis.py

# Step 3: Build and Evaluate Models
python scripts/modeling.py

📸 Visualizations

Plot

Description



Customer age distribution



Correlation between variables

🔍 Insights & Findings

Customers aged 30-40 are the most responsive to marketing campaigns.

Higher account balances correlate with a higher likelihood of subscribing.

Direct marketing is more effective than phone campaigns.

📌 Future Enhancements

Integrate SQL for better data management.

Implement a machine learning model to predict customer responses.

Automate reporting with Power BI or Tableau.

🤝 Contributing

If you'd like to contribute, feel free to fork this repository and submit a pull request!

📜 License

This project is licensed under the MIT License.
