This is my google drive link to check my project = https://drive.google.com/drive/folders/1AD5RIWSyrieAp0A29q7PuoumBtV2brwW?usp=sharing

🛍️ Myntra Fashion Clothing Data Analysis Project
📌 Project Overview

This project involves cleaning, analyzing, and extracting insights from the Myntra Fashion Clothing dataset, which contains detailed information about fashion products such as brand, category, price, discount offers, sizes, and customer ratings. The objective of this project is to perform structured data cleaning, exploratory data analysis, and data retrieval using Excel lookup functions to gain meaningful business insights.

📂 Dataset Description

Source: Myntra Fashion Clothing Dataset

Total Records: 526,564

Total Columns: 13

Key Columns:

Product_id

Brand

Category

Gender

OriginalPrice

DiscountPrice

DiscountOffer

SizeOption

Rating

Reviews

🎯 Project Objectives

Clean and preprocess unstructured fashion data

Standardize discount formats

Handle missing and duplicate values

Analyze pricing and discount trends

Retrieve product details using Excel lookup functions

Label products based on discount percentage

🧹 Data Cleaning and Preparation

The following data cleaning steps were performed:

Removed duplicate product records

Standardized the DiscountOffer column into a uniform format

Filled missing DiscountPrice values using category-wise average price

Replaced missing values in SizeOption with "Not Available"

📊 Data Analysis Tasks

Calculated average original price for products with ratings greater than 4

Counted products offering more than 50% discount

Identified products available in size "M"

Created a new column DiscountLabel:

High Discount → Discount > 50%

Low Discount → Discount ≤ 50%

🔍 Data Retrieval & Lookup (Excel)

Used VLOOKUP/XLOOKUP to retrieve brand, price, and rating using Product ID

Used INDEX & MATCH to find discount price

Used nested XLOOKUP to fetch values from any column using Product ID



📈 Key Insights

High-rated products tend to have higher average original prices

Discounts above 50% significantly increase product visibility

Size “M” is one of the most commonly available sizes

Certain brands dominate the fashion marketplace

📁 Project Structure
Myntra-Fashion-Data-Analysis/
│
├── data/
│   └── Myntra_Fashion_Clothing_uncleaned.csv
│
├── notebooks/
│   └── Data_Cleaning_and_Analysis.ipynb
│
├── excel/
│   └── Lookup_Operations.xlsx
│
├── README.md

🚀 Applications of the Project

E-commerce business analysis

Pricing and discount strategy optimization

Customer behavior analysis

Fashion trend identification



⭐ Acknowledgment

This project was created for learning and academic purposes to understand real-world data cleaning, analysis, and Excel lookup techniques using a large-scale fashion dataset.
