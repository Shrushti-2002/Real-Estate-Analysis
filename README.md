# Real-Estate-Analysis-Dashboard

📌 Project Overview

- This project analyzes a real estate dataset to understand the key factors that influence property prices.

- The dashboard was built using Power BI and focuses on identifying relationships between property characteristics (size, bedrooms, bathrooms, floors, age) and external factors (distance to city center, school rating, crime rate index) with property price.

- The objective is to transform raw housing data into meaningful business insights that help stakeholders make informed real estate investment decisions.

🎯 Business Objectives

The dashboard answers the following key questions:

- What is the average property price?

- How does property size affect price?

- Do more bedrooms and bathrooms increase value?

- Does distance from the city center reduce property prices?

- How do crime rates impact housing prices?

- Do better school ratings increase property value?

📂 Dataset Description

The dataset contains 20,000 property records with the following features:

- property_size_sqft

- bedrooms

- bathrooms

- floors

- age_of_property

- distance_to_city_center

- school_rating

- crime_rate_index

- price

🛠 Tools & Technologies Used

- Power BI Desktop

- Power Query (Data Cleaning)

- DAX (Data Analysis Expressions)

- Data Modeling & Visualization

🧹 Data Preparation

The following preprocessing steps were performed:

- Checked and corrected data types

- Removed inconsistencies and null values

- Created calculated column:

Price per SqFt = price / property_size_sqft

Created price segmentation column:

- Low

- Medium

- High

📊 Key Performance Indicators (KPIs)

KPI	Value = Total Properties 20,000,  Average Price $1,029,219, Avg Price per SqFt $563, Average Property Size 2,691 sq ft

📌 Key Insights

- Property size shows strong positive correlation with price.

- Homes closer to the city center tend to be more expensive.

- Higher school ratings are associated with higher property values.

- Higher crime rate areas show lower average property prices.

- Multi-floor properties tend to command premium pricing.
