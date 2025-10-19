# 🏠 Housing.com Rental Data — Web Scraping, Cleaning, and Exploratory Data Analysis

## 📘 Overview
This project involves collecting real-estate rental data from **Housing.com** using **BeautifulSoup** and **Regular Expressions (Regex)**, followed by **data cleaning**, **preprocessing**, and **exploratory data analysis (EDA)**.  
The goal of this project is to extract meaningful insights on **rental trends**, **property characteristics**, and **city-based comparisons** to better understand the dynamics of India’s housing rental market.

---

## 🧰 Tools & Technologies
- **Web Scraping:** BeautifulSoup, Requests, Regex  
- **Data Cleaning & Analysis:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Data Storage:** CSV (Excel format)

---

## 🗂️ Project Structure

Housing_Rental_Data_Analysis/
│
├── data/
│ ├── raw/ # Raw scraped data
│ └── cleaned/ # Cleaned datasets (e.g., Cleaned Rental Data.csv)
│
├── notebooks/
│ ├── 01_Web_Scraping
│ ├── 02_Data_Cleaning & Preprocessing
│ ├── 03_EDA_Visualization
│
├── visuals/
│ ├── rental_trends.png
│ ├── price_distribution.png
│ └── city_comparison.png



## 🧾 Dataset Description

| Column Name | Description |
|--------------|-------------|
| **House Type** | Describes the configuration of the house (e.g., 1 BHK, 2 BHK, 3 BHK, Villa, etc.). |
| **Location** | Local area or neighborhood where the property is located. |
| **Price** | Monthly rental price of the property (in INR). |
| **Built up Area in sq.ft** | Total built-up area of the property in square feet. |
| **Furnishing Status** | Indicates the furnishing level — Fully furnished, Semi-furnished, or Unfurnished. |
| **Highlights/Insights** | List of key property features such as nearby landmarks, amenities, or safety features (scraped as a list). |
| **Agent Name** | Name of the listing agent or real-estate company. |
| **Verification Status** | Verification tag from Housing.com (e.g., Verified). |
| **No. of Customer Contacted** | Number of users who have contacted the agent for this property (a measure of popularity). |
| **City** | City name where the property listing belongs. |

---

## 📊 Key Objectives
- Automate the extraction of housing rental data from Housing.com.
- Clean and preprocess the scraped data for consistency and usability.
- Perform exploratory data analysis (EDA) to uncover:
  - Average rental prices by city.
  - Distribution of property sizes and prices.
  - Relationship between property type, furnishing status, and price.
  - Popular locations based on number of customer contacts.

---

## 🧠 Insights (Example Outcomes)
- **Furnished flats** tend to have a **higher average rent** compared to unfurnished ones.  
- **Customer contact count** reflects property popularity and demand.  
- **Built-up area and price** show a positive correlation across most cities.  
- **Certain areas** (e.g., city centers) consistently have higher average rents.
