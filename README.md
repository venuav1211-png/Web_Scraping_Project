# 🧺 Washing Machine Market Analysis Using Web Scraping and Python

## 📌 Project Overview

This project focuses on collecting and analyzing washing machine product information from **Flipkart** using Python Web Scraping techniques.

The project uses Python libraries such as Requests, BeautifulSoup, Pandas, Regular Expressions, Matplotlib, and Seaborn to extract product information, clean raw data, perform feature engineering, and conduct Exploratory Data Analysis (EDA).

The main objective is to understand washing machine pricing, brand distribution, capacity, RPM, customer ratings, and machine types to generate meaningful business insights.

## 🎯 Project Objectives

- Scrape washing machine product details from Flipkart.
- Extract unique product links and product information.
- Create and store a raw dataset.
- Clean product prices using Pandas and Regex.
- Extract important product attributes.
- Perform feature engineering.
- Conduct Exploratory Data Analysis.
- Create meaningful data visualizations.
- Answer business-related questions.
- Provide data-driven business recommendations.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Requests | Sending HTTP requests |
| BeautifulSoup | HTML parsing and web scraping |
| Pandas | Data manipulation and cleaning |
| Regular Expressions | Data extraction |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Project implementation |

## 🔄 Project Workflow

### 1. Library Import
Imported the required Python libraries for web scraping, data processing, and visualization.

### 2. Web Scraping
- Accessed the Flipkart washing machine search page.
- Extracted unique product URLs.
- Inspected product cards.
- Collected product names and prices.

### 3. Raw Dataset Creation
Created a raw dataset containing product names, prices, URLs, and original product-card text.

### 4. Data Cleaning
- Cleaned price values.
- Converted prices into numeric format.
- Removed duplicate records.
- Checked missing values.

### 5. Feature Extraction Using Regex

Extracted the following product attributes:

- Brand
- Capacity (kg)
- RPM
- Power Rating
- Customer Rating
- Warranty
- Machine Type

### 6. Feature Engineering

Created three additional features:

- **Price Category:** Budget, Mid-Range, Premium
- **Capacity Category:** Small, Medium, Large
- **Discount Category:** Low, Medium, High, Unknown

### 7. Data Quality Validation

Validated extracted features and checked missing values before performing EDA.

### 8. Exploratory Data Analysis

Created nine visualizations to understand product characteristics and market patterns.

### 9. Business Analysis

Answered ten business questions and developed business insights and recommendations.

## 📊 Dataset Information

The collected dataset contains **29 product records and 15 columns** after feature extraction and engineering.

### Dataset Columns

| Column | Description |
|---|---|
| Product_Name_Raw | Original product name |
| Price_Raw | Original price text |
| URL | Product URL |
| Card_Text_Raw | Original product card text |
| Price | Cleaned product price |
| Brand | Washing machine brand |
| Capacity_kg | Machine capacity |
| RPM | Spin speed |
| Power_Rating | Star rating |
| Rating | Customer rating |
| Warranty | Warranty information |
| Machine_Type | Type of washing machine |
| Price_Category | Price classification |
| Capacity_Category | Capacity classification |
| Discount_Category | Discount classification |

### Dataset Files

- `raw_washing_machine_data.csv`
- `cleaned_washing_machine_data.csv`

## 📈 Data Visualizations

The project includes the following nine visualizations:

1. Washing Machine Price Distribution
2. Products Available by Brand
3. Washing Machine Capacity Distribution
4. RPM Distribution
5. User Rating Distribution
6. Price Comparison by Brand
7. Washing Machine Capacity vs Price
8. Products by Machine Type
9. Correlation Between Washing Machine Features

All visualizations are saved inside the `visualizations` folder.

## 💡 Business Questions Answered

1. What is the average washing machine price?
2. Which product has the highest price?
3. Which product has the lowest price?
4. Which brand has the most products?
5. What is the average price by brand?
6. What is the average price by capacity?
7. What is the average price by machine type?
8. Which products have the highest user ratings?
9. What is the average RPM?
10. What is the average price for each power rating?

## 🔍 Key Findings

Based on the notebook's collected dataset:

- Average washing machine price: ₹17,839.59
- Highest-priced product: IFB 9 kg washing machine – ₹39,490
- Lowest-priced product: VW 8.5 kg washing machine – ₹5,010
- Brand with the most listings: Whirlpool (5 products)
- Average RPM: 1,138.28
- Highest observed customer rating: 4.5

These findings represent the collected product listings and are not a complete representation of the entire washing machine market.

## 📌 Business Recommendations

- Maintain washing machine products across different price segments.
- Compare competitor prices regularly.
- Focus on commonly listed capacity ranges.
- Highlight verified customer ratings.
- Provide complete product specifications and warranty details.
- Use discount analysis to plan promotional strategies.
- Update market data periodically.
- Use collected data to support inventory planning.

## 📁 Project Structure

```text
Washing_Machine_Market_Analysis/
│
├── Washing_Machine_Market_Analysis (2).ipynb
│
└── washing_machine_project/
    │
    ├── raw_washing_machine_data.csv
    ├── cleaned_washing_machine_data.csv
    │
    └── visualizations/
        ├── 01_price_distribution.png
        ├── 02_brand_count.png
        ├── 03_capacity_distribution.png
        ├── 04_rpm_distribution.png
        ├── 05_rating_distribution.png
        ├── 06_price_by_brand.png
        ├── 07_capacity_vs_price.png
        ├── 08_machine_type.png
        └── 09_correlation_heatmap.png
```

*The dataset and visualization files are generated when the notebook is executed.*

## 🚀 How to Run This Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Install Required Libraries

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open the Project Notebook

Open `Washing_Machine_Market_Analysis (2).ipynb`.

### Step 5: Execute the Notebook

Run all cells sequentially to perform web scraping, data cleaning, feature extraction, feature engineering, EDA, and business analysis.

## ⚠️ Limitations

- The dataset represents product listings collected at the time of scraping.
- Website HTML structures may change, requiring updates to scraping code.
- Some product attributes may be missing from the original listings.
- The analysis is limited to the collected product records.
- Always follow the website's current terms of use, robots.txt, and applicable scraping policies.

## 🏁 Conclusion

This project demonstrates how Python Web Scraping and Exploratory Data Analysis can be combined to understand an online product market.

By collecting washing machine product information from Flipkart, cleaning the data, extracting useful attributes, and creating visualizations, this project provides insights into product pricing, brand distribution, capacity, RPM, and customer ratings.

It also demonstrates how raw web data can be transformed into meaningful business insights that support better decision-making.

---

## 👨‍💻 Author

**Bommishetti Venu**

**Project:** Washing Machine Market Analysis Using Web Scraping and Python

⭐ If you find this project useful, don't forget to star the repository!
