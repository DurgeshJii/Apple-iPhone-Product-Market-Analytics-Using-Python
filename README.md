# Apple-iPhone-Product-Market-Analytics-Using-Python
A Python-based Exploratory Data Analysis project analyzing 62 Apple product listings from Flipkart to uncover relationships between sale price, discounts, customer ratings, reviews, and product specifications.

# Project Overview

This project uses Pandas, NumPy, Matplotlib, Seaborn, and SciPy to analyze Apple iPhone marketplace data and answer practical business questions around customer engagement and pricing.

# Key Questions
Which iPhones have the highest star ratings?
How many ratings do the highest-rated iPhones have?
Which iPhone has the highest number of reviews?
What is the relationship between sale price and number of ratings?
What is the relationship between discount percentage and number of ratings?
What are the cheapest and most expensive iPhones in the dataset?
# Key Findings
Analysis	Finding
Dataset	62 products, 11 columns
Average Sale Price	₹80,073.89
Average Discount	9.95%
Average Star Rating	4.58/5
Highest Rating	4.7/5
Highest-rated variants	iPhone 11 Pro Max variants
Ratings of highest-rated variants	1,078 each
Most-reviewed iPhone	iPhone SE (White, 256 GB)
Highest Reviews	8,161
Price vs Ratings	Pearson r = -0.70
Discount vs Ratings	Pearson r = +0.68
Cheapest iPhone	iPhone SE (White, 64 GB) — ₹29,999
Most Expensive iPhone	iPhone 12 Pro (Silver, 512 GB) — ₹1,40,900
# Visualizations

The project includes visualizations for:

Top 10 Highest-Rated iPhones
Sale Price vs. Number of Ratings
Discount Percentage vs. Number of Ratings

The correlation visualizations use regression lines to make the relationships easier to interpret.

# Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
# Project Workflow
Raw Flipkart Data
       ↓
Data Loading
       ↓
Data Inspection
       ↓
iPhone Filtering
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Correlation Analysis
       ↓
Data Visualization
       ↓
Business Insights
# Important Insight

The analysis found a strong negative association between iPhone sale price and number of ratings (r = -0.70) and a positive association between discount percentage and number of ratings (r = +0.68).

These results indicate that, within this dataset, lower-priced and more-discounted products tended to show greater customer engagement.

 Note: These are correlations within the available Flipkart dataset and should not be interpreted as proof of causation or as a representation of the entire Indian smartphone market.

# Repository Contents
Apple-iPhone-Product-Analytics/
│
├── Apple Sales Python Project.ipynb
├── Apple Sales Python Project.pdf
├── apple_products xl data.csv
├── top_rated_iphones.png
├── saleprice_vs_ratings.png
├── discount_vs_ratings.png
└── README.md
Outcome

This project demonstrates an end-to-end EDA and business analytics workflow, from raw e-commerce data to statistical analysis, visualization, and actionable insights.

# By- Durgesh Yadav
