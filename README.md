Amazon Sales Dataset EDA






Project Overview
This repository contains the code and analysis for my Exploratory Data Analysis (EDA) project on the Amazon Sales Dataset from Kaggle. The goal of this project is to uncover insights into sales patterns and trends, identify top-selling products, and visualize key metrics such as Units Sold, Total Revenue, and Total Profit.

Table of Contents
Project Overview
Dataset
Project Structure
Installation
Usage
Results
Key Insights
Contributing
License
Acknowledgements
Dataset
The dataset used in this project is the Amazon Sales Dataset, which includes detailed sales data for various products.

Project Structure
css
Copy code
├── data
│   ├── amazon_sales_data.csv
├── notebooks
│   ├── Amazon_Sales_EDA.ipynb
├── README.md
├── requirements.txt
data/: Contains the dataset file.
notebooks/: Contains the Jupyter notebook with the EDA.
src/: Contains Python scripts for data preparation and visualization.
README.md: Project documentation.
requirements.txt: List of required Python packages.
Installation
To run this project, you need to have Python 3.8+ installed. Clone the repository and install the required packages:

bash
Copy code
git clone https://github.com/yourusername/amazon-sales-eda.git
cd amazon-sales-eda
pip install -r requirements.txt
Usage
Data Preparation: Run the data preparation script to clean and preprocess the dataset.
bash
Copy code
python src/data_preparation.py
Exploratory Data Analysis: Open the Jupyter notebook to explore the data and visualize insights.
bash
Copy code
jupyter notebook notebooks/EDA.ipynb
Results
Key Metrics Visualized
Units Sold: Distribution and trends
Total Revenue: Top-performing products and categories
Total Profit: Profit margins and profitability analysis
Visualizations
Interactive plots created using Plotly
Static plots created using Matplotlib
Key Insights
Top-Selling Products: Identified the highest selling products across different categories.
Seasonal Trends: Observed seasonal variations in sales.
Revenue and Profit Analysis: Analyzed which products and categories generated the most revenue and profit.
Contributing
Contributions are welcome! Please fork the repository and create a pull request to propose changes.

License
This project is licensed under the MIT License.

Acknowledgements
The dataset is sourced from Kaggle.
Thanks to OpenAI's ChatGPT for assisting with the visualization code.
