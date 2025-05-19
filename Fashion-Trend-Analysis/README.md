# 👗 FashionTrendScraper

This project focuses on extracting fashion product data from an e-commerce website to identify and analyze current fashion trends. By collecting product names, prices, and ratings, it uncovers patterns in pricing, popularity, and keyword usage to guide trend forecasting and data-driven decision-making in the fashion industry.

---

## 📊 Problem Statement

Fashion e-commerce platforms host thousands of products, making it difficult to manually track emerging trends. This project solves that by using Python web scraping to collect relevant product data and visualize fashion insights based on:

- Product Titles (for keyword analysis)  
- Prices  
- Customer Ratings  

---

## 🧠 Objectives

- Automatically extract fashion product data from an online store.  
- Analyze average prices and rating distributions.  
- Identify high-priced and top-rated products.  
- Discover trending keywords in product titles.  
- Visualize patterns influencing fashion trends.

---

## 📁 Data Source

The data is scraped directly from an e-commerce website (for educational use only) and includes:

| Column        | Description                          |
|---------------|--------------------------------------|
| Product Name  | Title of the fashion item            |
| Price         | Listed price of the product          |
| Rating        | Customer rating (e.g., 4.5 out of 5) |

---

## 🔧 Tools & Libraries

- **Python**
- **BeautifulSoup** – HTML parsing  
- **Requests** – Sending HTTP requests  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **WordCloud** – Word frequency analysis  
- **Jupyter Notebook**

---

## ⚙️ Analysis Conducted

- Cleaned and formatted raw HTML data  
- Analyzed price and rating distribution  
- Extracted top 10 most expensive products  
- Generated a word cloud from product titles  
- Exported structured data for further analysis  

---

## 📌 Key Findings

- High ratings cluster around mid-range prices.  
- Keywords like “Luxury,” “Limited,” and “Exclusive” often associate with premium products.  
- 4-star and 5-star ratings dominate the dataset.

---

## 📈 Project Highlights

- 🔍 Scraped live fashion data from an e-commerce site  
- 🧹 Cleaned and structured the dataset  
- 📊 Visualized insights with charts and word clouds  
- 💾 Exported a clean dataset for future modeling

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/jubileeamechi/jubileeamechi-Python-Data-Science-Projects.git
cd jubileeamechi-Python-Data-Science-Projects/FashionTrendScraper
