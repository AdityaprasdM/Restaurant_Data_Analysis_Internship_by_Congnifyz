# Restaurant_Data_Analysis_Internship_by_Congnifyz
A data analysis project exploring restaurant trends, cuisines, pricing patterns, customer ratings, reviews, and geospatial insights using Python, Power BI, and Excel. Includes EDA, sentiment analysis, menu insights, service comparisons, and interactive visualizations.

🍽️ Restaurant Data Analysis Project
Data Analyst Internship — Cognifyz Technologies
📌 Project Overview

This project involves a complete end-to-end analysis of a restaurant dataset. The objective is to identify cuisine trends, price range behavior, rating patterns, customer sentiment, geospatial restaurant clusters, service insights, and business patterns using Python, Pandas, Matplotlib, Folium, Power BI, and Excel.

The analysis provides actionable insights into:

Customer preferences

Popular cuisines

High-performing cities

Price vs service adoption

Review-based sentiment

Restaurant chain distribution

Votes vs rating relationship

🗂️ Dataset Description

The dataset contains the following fields:

Restaurant ID

Restaurant Name

City

Cuisines

Latitude & Longitude

Price Range (1–4)

Aggregate Rating

Rating Text

Votes

Has Online Delivery (Yes/No)

Has Table Booking (Yes/No)

Data cleaning and transformation steps were applied:

Removed duplicates (based on Restaurant ID)

Split and normalized multi-cuisine entries

Cleaned Yes/No fields

Converted numeric fields

Standardized rating values

🧠 Key Objectives

Identify top cuisines and cuisine combinations

Determine cities with the highest restaurant density

Analyze price range distribution

Compare ratings for restaurants with and without online delivery

Extract positive and negative keywords from reviews

Analyze review length vs rating

Identify restaurant chains

Plot restaurants on maps using latitude & longitude

Check correlation between votes and ratings

Understand how price range affects service availability

🔍 Exploratory Data Analysis (EDA)
✔ Top Cuisines

Using explode + groupby, analyzed percentage of restaurants offering each cuisine.
Example:

Indian: 46%

North Indian: 43%

Chinese: 30%

✔ City-Level Analysis

Identified city with the most restaurants

Computed average rating per city

✔ Price Range Distribution

Analyzed price bands to understand affordability and spending patterns.

✔ Online Delivery vs Ratings

Restaurants offering online delivery showed higher ratings on average.

📝 Text & Sentiment Analysis

Removed stopwords using NLTK

Extracted repeated positive and negative keywords

Calculated review lengths and compared them with ratings

Found that longer reviews correspond to higher ratings

🌍 Geospatial Insights

Using Folium maps:

Plotted restaurants using latitude & longitude

Identified city clusters and high-density locations

Helpful for expansion and competitor mapping

🔗 Correlation & Service Analysis

Computed correlation between votes and rating

Positive correlation found → Higher-rated restaurants receive more votes

Verified that higher price range restaurants offer more services (delivery/booking)

📊 Visualizations

This project includes multiple charts (Python & Power BI):

Top cuisines bar chart

City restaurant distribution

Price range histogram

Delivery vs non-delivery comparison

Positive & negative keyword charts

Cuisine combination distribution

Votes vs rating scatter plot

Geospatial cluster map

All charts & dashboards are included in the visuals/ folder in the repository (you can add this folder).

🧪 Technologies Used

Python: Pandas, Matplotlib, NLTK, Folium

Power BI: Mapping & dashboards

Excel: Pivot tables, charts

Jupyter Notebook for analysis workflow

▶️ How to Run the Project
# Clone the repository
git clone https://github.com/your-username/restaurant-data-analysis.git

# Navigate to the project folder
cd restaurant-data-analysis

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook internship_project.ipynb

🧾 Folder Structure (Recommended)
├── data/
│   └── dataset.csv
├── notebooks/
│   └── internship_project.ipynb
├── visuals/
│   ├── top_cuisines.png
│   ├── price_range_chart.png
│   ├── map_cluster.png
│   └── votes_vs_ratings.png
├── README.md
└── requirements.txt

⭐ Conclusion

This project revealed crucial insights into cuisine popularity, customer engagement, price-based behavior, and geographical distribution of restaurants. It showcases practical data analytics skills, including EDA, visualization, sentiment analysis, and geospatial mapping.

🙌 Acknowledgment

This project was completed as part of the Data Analyst Internship at Cognifyz Technologies.

Contact: deviadityaprasad@gmail.com
