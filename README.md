# EDA
🥗 File 1 :  Zomato Dataset Exploratory Data Analysis (EDA)
📖 Overview

This project performs Exploratory Data Analysis (EDA) on the Zomato Restaurants Dataset.
The goal is to understand restaurant trends across countries, cities, cuisines, and ratings, and to visualize insights using Python data analysis libraries.

🧰 Tools & Libraries

Python 3

Pandas – for data manipulation

NumPy – for numerical operations

Matplotlib & Seaborn – for data visualization

Google Colab – for interactive analysis and plotting

📂 Dataset

File: zomato.csv
Source: Zomato restaurant data (Kaggle / Colab Drive)
Rows: 9551
Columns: 21

Key Columns:

Restaurant Name

Country Code

City

Cuisines

Average Cost for two

Aggregate rating

Votes

📊 Data Analysis Steps

Data Loading

Imported dataset using Pandas and verified basic information using .info() and .describe().

Data Cleaning

Checked for missing values.

Standardized column names and encoded categorical variables where necessary.

Exploratory Data Analysis

Univariate Analysis: Distribution of numerical and categorical variables.

Bivariate Analysis: Relationships between features such as price range vs rating, country vs rating, etc.

Multivariate Analysis: Combination of categorical and numerical relationships.

Visualizations

Country-wise restaurant distribution (pie chart and bar chart)

Top cuisines by popularity

Rating distribution across countries

Relationship between cost and rating

Votes vs Aggregate Rating correlation

📈 Insights

Majority of restaurant data comes from India, followed by the United States and United Kingdom.

North Indian and Chinese cuisines dominate the dataset.

Higher-rated restaurants often have moderate price ranges.

Most restaurants do not offer online delivery.

Aggregate ratings are positively correlated with number of votes.

📁 Project Structure
📦 zomato-eda
├── zomato.csv
├── Zomato_EDA.ipynb          # Colab notebook
├── plots/                    # Folder containing generated plots
├── README.md
└── requirements.txt           # Python dependencies

⚙️ How to Run

Clone the repository:

git clone https://github.com/<your-username>/zomato-eda.git
cd zomato-eda


Install dependencies:

pip install -r requirements.txt


Open and run the notebook in Jupyter or Google Colab:

jupyter notebook Zomato_EDA.ipynb

📌 Future Work

Add interactive dashboards using Plotly or Power BI.

Predict restaurant ratings using machine learning.

Analyze geospatial patterns (latitude & longitude).

🧑‍💻 Author

Your Name
📧 kyaseen228@gmail.com
🌐 https://github.com/myk225


