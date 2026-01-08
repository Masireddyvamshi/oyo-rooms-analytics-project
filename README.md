🏨 OYO Rooms End-to-End Data Analysis Project
📌 Project Overview

This project presents a complete end-to-end Exploratory Data Analysis (EDA) of OYO Rooms hotel data.
The analysis focuses on understanding how pricing, hotel type, city, amenities, and customer ratings influence hotel popularity and customer decision-making.

The project follows a real-world data analytics lifecycle, starting from raw scraped data and ending with meaningful business insights.

❓ Business Problem

OYO operates across multiple cities with different hotel categories.
However, customers and businesses face challenges such as:

Large price variation for similar hotels

Difficulty understanding how hotel type affects pricing

Unclear relationship between ratings and actual popularity

Limited visibility into the role of amenities

This project aims to uncover data-driven answers to these challenges.

🎯 Project Objectives

Analyze hotel price variation across cities

Understand pricing behavior across hotel categories

Study customer ratings and review patterns

Evaluate the impact of amenities on hotel popularity

Identify key drivers influencing hotel pricing and popularity

📊 Data Collection

Data was collected from the OYO Rooms website

Only publicly visible hotel information was used

The dataset represents a snapshot of hotel listings across multiple cities and hotel types

🧾 Dataset Overview

The dataset contains hotel-level information related to pricing, location, customer feedback, and amenities.
It also includes derived features created during preprocessing to support deeper analysis.

📋 Column Summary
🏨 Hotel Information

Hotel_Name
Name of the hotel as listed on the OYO platform.

Hotel_Type
Category of the hotel such as Townhouse, Collection O, Super OYO, or OYO Flagship.
This reflects the service level and brand positioning of the property.

City
City in which the hotel is located.

Location
Specific area or locality within the city.

💰 Pricing Details

Final_Price
The actual price paid by the customer after applying discounts and offers.

Original_Price
The listed price before discounts were applied.

Discount
The price difference between the original price and the final price.

Taxes
Additional taxes applied to the booking amount.

Price_Category
A derived column grouping hotels into Low, Medium, or High price ranges.

⭐ Customer Ratings & Reviews

Rating
Average customer rating given to the hotel.

Number_of_Ratings
Total number of customer reviews submitted for the hotel.

Rating_Category
A derived column classifying ratings into categories such as Poor, Average, Good, and Excellent.

🏷 Amenities & Popularity

Amenity_Count
Total number of amenities offered by the hotel.

Popularity_Score
A derived metric combining rating and number of ratings to represent overall customer popularity.

🧹 Data Cleaning & Preprocessing

The raw data was text-heavy and unstructured, requiring extensive preprocessing:

Removal of missing values and duplicates

Conversion of price and rating fields into numeric format

Standardization of city names and hotel types

Creation of derived columns for analytical purposes

Cleaning of noisy text fields

🔤 Use of Regular Expressions (Regex)

Regular Expressions were used to clean and transform raw scraped data:

Extracting numeric values from price strings

Cleaning rating and review text

Identifying hotel types from hotel names

Removing unwanted symbols and inconsistencies

Regex played a key role in improving data quality, accuracy, and consistency.

📈 Exploratory Data Analysis (EDA)
🔹 Univariate Analysis

Distribution of hotel prices

Distribution of customer ratings

Frequency of hotel types

Amenity count distribution

🔹 Bivariate Analysis

City vs final hotel price

Hotel type vs pricing

Rating category vs pricing

Amenity count vs popularity

🔹 Multivariate Analysis

Combined impact of city, hotel type, and price

Relationship between hotel type, rating, and popularity

Influence of amenities, ratings, and price together

📌 Key Insights

Hotel prices vary significantly across cities

Hotel type is a strong determinant of pricing

Higher ratings do not always lead to higher prices

Hotels offering more amenities tend to achieve higher popularity

Some budget hotels outperform premium hotels due to value-for-money offerings

🧠 Business Recommendations

Optimize pricing strategies based on city-level demand

Improve amenity offerings to boost hotel popularity

Promote high-performing budget hotels for customer acquisition

Use popularity score alongside ratings for better decision-making

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Regular Expressions (Regex)

Jupyter Notebook


📌 Future Scope

Price prediction using machine learning models

Customer segmentation and clustering

Time-based pricing analysis

Interactive dashboards using Power BI or Tableau

👤 Author

Vamshidhar Masireddy
Aspiring Data Scientist | Data Analyst
Python | SQL | Power BI
