# Amazon-Products-Sales-Dataset-2023


## Overview 

In this project, I conducted a comprehensive analysis of Amazon product data, focusing specifically on baby products, using Python's Pandas library and various data visualization tools. The analysis aimed to uncover key insights, including identifying top-selling products, discount prices, ratings, and profitability. Through detailed exploration and visualization, I highlighted trends in product performance, profitability, and customer preferences. This analysis provides actionable insights to guide data-driven strategies for optimizing product promotions, pricing, and inventory management.


## Questions

* What are the top selling_products that have the highest sales?

* Which products generate the most profit?

* Are there specific products with unusually high or low ratings?

* Is there a correlation between product profit and discount percentage? Is there a correlation between discount_price and discount_percentage?



## Data source

* The Amazon Products Sales Dataset 2023 was taken from Kaggle : (https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset/data?select=Baby+Products.csv)

## Data Processing and Transformation 

* Data cleaning: 
- Handling missing values by either imputing them with suitable replacements (e.g., mean, median...) or dropping rows/columns where data was insufficient.
- Ensuring correct data types for all columns (e.g., converting discount_price to float format and numeric columns to appropriate numerical types).

* Featur selection:
- Selected key columns for analysis, including product, main_category, sub_category, ratings,	discount_price,	actual_price, discount_percentage and profit, while dropping irrelevant columns like image, link, no_of_ratings.

- Creating new features like discount_percentage and profit to provide more detailed insights into the impact of discount_percentage on sales and profit.


* Data Transformation:
 - Grouping Numerical Columns: Grouping numerical columns like Age and Previous Purchases into meaningful bins (e.g., age groups like "18-25"...) to make the data easier to analyze and interpret.

- Incorporating Profit and Discount Metrics: understanding the correlation between discount_percentage and profit and determining the impact of discounts on sales profitability.

- Converting Data Types: Ensuring columns are converted to appropriate data types.

* Aggregation:
- Summarizing sales data by discount_price, discont_percentage, profit... to understand performance trends.


## Best practices and how to Replicate and run the project

### Prerequisites for Replicating the Analysis

1. Git:
* Git is required to clone the repository to your local machine. You can follow the installation instructions available at this website [here](https://github.com/git-guides/install-git) 

2. Visual Studio Code (VSC)
The analysis was conducted using Jupyter Notebook within Visual Studio Code (VSC). To get started with VSC:

- Download and install Visual Studio Code from [here](https://code.visualstudio.com/Download)
- Once installed, open VSC and ensure the Jupyter extension is installed. You can search for the Jupyter extension in the Extensions view (Ctrl+Shift+X) and install it.

3. Jupyter Notebook
After installing VSC and the Jupyter extension, you need to install Jupyter Notebook itself. Follow these steps:
* Open a terminal in VSC and install Jupyter by running the command:
         pip install notebook
* After installation, you should be able to run Jupyter notebooks inside VSC. For more detailed instructions, refer to the official documentation [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html)


4. CSV File: 
* Download the required CSV file and place it in the project folder on your local machine. This file is necessary for running the analysis.


### Getting started to Replicate and Run the Project

1. Clone the Repository:
* Clone the project repository to your local machine by using the following URL: https://github.com/JamilaAr/Amazon-Products-Sales-Dataset-2023
* Run the following command in your terminal: git clone https://github.com/JamilaAr/Amazon-Products-Sales-Dataset-2023

2. Create and Activate a Virtual Environment:
* Set up a virtual environment and install the required packages from requirements.txt:

- For Linux/Mac:
  
* `python3 -m venv venv`
* `source venv/bin/activate`
* `pip install -r requirements.txt`
  
- For Git Bash(Windows):
  
* `python -m venv venv`
* `source venv/Scripts/activate`
* `pip install -r requirements.txt`


3. Deactivate the Virtual Environment (After Use):
  
`deactivate`
      
4. Ensure that the CSV file is placed in the main project directory.

5. Run the .ipynb file:
Open and execute the following file for analysis:

* Baby_Products.ipynb

## I will be presenting a Tableau dashboard to analyze Baby_Products. This interactive visualization provides clear and dynamic insights into sales patterns and profitability.

* Explore sales trends for top product and categories.

* Analyze Baby Products profitability

[Click on the link](https://public.tableau.com/views/RetailSalesandCustomerShoppingTrends/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusion

The Amazon Products Sales project delivered valuable insights into the sales performance of baby products. Key findings included identifying top-selling and highly profitable products by analyzing discount percentages, ratings, and overall sales trends. Additionally, the analysis revealed a moderate positive correlation between discount_percentage and profit, indicating that as discounts increase, profitability also tends to improve. These insights can help refine promotional strategies and enhance decision-making for future product offerings.