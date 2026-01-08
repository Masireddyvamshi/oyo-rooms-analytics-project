<div align="center">
🏨 OYO Rooms — End-to-End Data Analysis Project

📊 Exploratory Data Analysis | 💡 Business Insights | 🧠 Data-Driven Decisions

</div>
📌 Project Overview

This project presents a complete end-to-end Exploratory Data Analysis (EDA) of OYO Rooms hotel data.
The analysis focuses on understanding how pricing, hotel type, city, amenities, and customer ratings influence hotel popularity and customer decision-making.

The project follows a real-world data analytics lifecycle, starting from raw scraped data and ending with actionable business insights.

❓ Business Problem

OYO operates across multiple cities with diverse hotel categories. However, both customers and business teams face challenges such as:

Wide price variation for similar hotels

Difficulty understanding how hotel type impacts pricing

Unclear relationship between ratings and popularity

Limited visibility into the role of amenities

This project aims to uncover data-driven explanations behind these patterns.

🎯 Project Objectives

Analyze hotel price variation across cities

Understand pricing behavior across hotel categories

Study customer ratings and review trends

Evaluate the impact of amenities on hotel popularity

Identify key drivers influencing pricing and customer preference

📊 Data Collection

Data collected from the OYO Rooms website

Only publicly available hotel information was used

Dataset represents a snapshot of hotels across multiple cities and hotel types

🧾 Dataset Overview

The dataset contains hotel-level information related to pricing, location, customer feedback, and amenities, along with derived analytical features created during preprocessing.

📋 Column Summary
🏨 Hotel Information

Hotel_Name – Name of the hotel as listed on the platform

Hotel_Type – Category such as Townhouse, Collection O, Super OYO, OYO Flagship

City – City where the hotel is located

Location – Specific locality within the city

💰 Pricing Details

Final_Price – Actual price paid after discounts

Original_Price – Price before discounts

Discount – Difference between original and final price

Taxes – Additional taxes applied

Price_Category – Derived grouping: Low, Medium, High

⭐ Customer Ratings & Reviews

Rating – Average customer rating

Number_of_Ratings – Total customer reviews

Rating_Category – Derived grouping: Poor, Average, Good, Excellent

🏷 Amenities & Popularity

Amenity_Count – Total number of amenities offered

Popularity_Score – Derived metric combining ratings and review volume

🧹 Data Cleaning & Preprocessing

The raw data was unstructured and text-heavy, requiring multiple preprocessing steps:

Removal of duplicates and missing values

Conversion of pricing and rating fields into numeric formats

Standardization of city names and hotel categories

Creation of derived analytical features

Cleaning of noisy text fields

🔤 Use of Regular Expressions (Regex)

Regex was used extensively to clean and structure scraped data:

Extracting numeric values from price strings

Cleaning rating and review text

Identifying hotel categories from hotel names

Removing unwanted symbols and inconsistencies

Regex significantly improved data quality and reliability.

📈 Exploratory Data Analysis (EDA)
🔹 Univariate Analysis

Price distribution

Rating distribution

Hotel type frequency

Amenity count distribution

🔹 Bivariate Analysis

City vs hotel price

Hotel type vs pricing

Rating category vs pricing

Amenity count vs popularity

🔹 Multivariate Analysis

Combined effect of city, hotel type, and price

Relationship between hotel type, rating, and popularity

Influence of amenities, ratings, and pricing together

📌 Key Insights

Hotel pricing varies significantly across cities

Hotel type strongly influences pricing

Higher ratings do not always mean higher prices

Hotels with more amenities tend to be more popular

Some budget hotels outperform premium hotels due to value-for-money

🧠 Business Recommendations

Optimize pricing strategies based on city-level demand

Improve amenity offerings to boost popularity

Promote high-performing budget hotels

Use popularity score alongside ratings for decision-making

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Regular Expressions (Regex)

Jupyter Notebook


📌 Future Scope

Price prediction using machine learning

Customer segmentation and clustering

Time-based pricing analysis

Interactive dashboards (Power BI / Tableau)

<div align="center">
👤 Author

Vamshidhar Masireddy
Aspiring Data Scientist | Data Analyst
Python | SQL | Power BI

</div>
