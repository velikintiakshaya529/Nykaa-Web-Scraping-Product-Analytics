# Nykaa Web Scraping & Product Analytics

## 📌 Project Overview

This project focuses on collecting product data from Nykaa using web scraping and transforming the collected data into meaningful business insights through data cleaning, analysis, and visualization.

The project covers multiple product categories such as **Beauty, Healthcare, and Baby Care**. The cleaned dataset is analyzed using Python and presented through an interactive **Power BI dashboard**.

The main objective is to understand product pricing, discounts, customer reviews, ratings, brands, and category-level performance.

---

## 🎯 Objectives

- Scrape product information from Nykaa.
- Collect data from multiple product categories.
- Clean and preprocess the scraped dataset.
- Handle missing values and duplicate records.
- Analyze product prices, discounts, ratings, and reviews.
- Compare product performance across categories and brands.
- Identify top-performing products.
- Build an interactive Power BI dashboard.
- Generate useful insights from the collected data.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data collection and processing |
| Requests | Sending HTTP requests |
| BeautifulSoup | Web scraping and HTML parsing |
| Pandas | Data cleaning and analysis |
| Regular Expressions | Text and price extraction |
| Power BI | Interactive dashboard and visualization |
| Git & GitHub | Version control and project sharing |

---

## 📊 Data Collection

Product information was collected from Nykaa using Python-based web scraping techniques.

The scraping process collects relevant product attributes such as:

- Product Name
- Brand
- Category
- MRP
- Selling Price
- Discount
- Rating
- Reviews

### Product Categories

The dataset contains products from:

- Beauty
- Healthcare
- Baby

The final cleaned dataset contains **60 products**, with **20 products from each category**.

---

## 🧹 Data Cleaning

The scraped data was cleaned and prepared for analysis using Pandas.

The cleaning process included:

- Removing duplicate records
- Handling missing values
- Cleaning product names
- Standardizing category names
- Cleaning brand names
- Converting prices into numeric values
- Cleaning discount values
- Cleaning ratings and review counts
- Removing unnecessary columns
- Validating the final dataset

---

## 📈 Data Analysis

The analysis focuses on the following areas:

### Product Analysis
- Total number of products
- Product-wise selling price
- Top products by selling price
- Product ratings
- Product reviews

### Brand Analysis
- Brand-wise product performance
- Brand-wise selling price
- Comparison of brands across categories

### Category Analysis
- Category-wise sales/value
- Category-wise reviews
- Category-wise discounts
- Category-wise product distribution

### Pricing Analysis
- MRP vs Selling Price
- Discount vs Selling Price
- Average selling price
- Average discount

---

## 📊 Power BI Dashboard

The final dashboard provides an interactive overview of Nykaa's multi-category product data.

### KPI Cards

The dashboard includes:

- **Total Products:** 60
- **Total Product Value:** 34K
- **Average Selling Price:** 732.74
- **Average Discount:** 0.16
- **Total Reviews:** 9M

> KPI values may change if the dataset is updated or refreshed.

### Dashboard Visualizations

The dashboard contains:

1. **Brand-wise Sales**
2. **Category-wise Sales**
3. **Reviews by Category**
4. **Discount vs Selling Price**
5. **Top 10 Products by Sales**

### Interactive Filters

Users can filter the dashboard using:

- Category
- Brand
- Product Name

---

## 📷 Dashboard Preview

Add your Power BI dashboard screenshot inside the `images` folder and update the filename below.

```markdown
![Nykaa Product Analytics Dashboard](Nykaa Screenshot.png)
