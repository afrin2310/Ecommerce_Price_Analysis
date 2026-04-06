# 📊 E-Commerce Price Analysis using Web Scraping

## 📌 Project Overview

This project focuses on extracting product data from an e-commerce website using web scraping techniques and performing data analysis to uncover pricing trends and insights.

The data is collected from a practice website and includes product title, price, and rating. The project demonstrates end-to-end data analytics workflow from data collection to visualization.

---

## 🎯 Objectives

* Scrape product data from multiple web pages
* Clean and preprocess raw data
* Perform exploratory data analysis (EDA)
* Visualize pricing and rating patterns
* Generate meaningful business insights

---

## 🛠️ Tech Stack

* Python
* Google Colab
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```
ecommerce-price-analysis/
│── Ecommerce_Price_Analysis.ipynb
│── books_data.csv
│── README.md
```

---

## 🔍 Data Collection

* Scraped data from: [http://books.toscrape.com/](http://books.toscrape.com/)
* Extracted features:

  * Product Title
  * Price
  * Rating

---

## 🧹 Data Cleaning

* Removed special characters from price (handled encoding issues like `Â£`)
* Converted price to numeric format
* Mapped rating text (One, Two, etc.) to numerical values

---

## 📊 Data Analysis & Visualization

* Price distribution analysis
* Rating distribution analysis
* Identified trends between price and ratings

---

## 📈 Key Insights

* Most products fall within a mid-range price category
* Higher-rated products tend to have slightly higher prices
* Majority of products have ratings between 3 and 5

---

## 🚀 How to Run the Project

1. Open Google Colab
2. Upload the notebook file
3. Run all cells step-by-step
4. The dataset will be generated automatically

---

## ⚠️ Challenges Faced

* Encoding issues in scraped data (`Â£` instead of `£`)
* Handling missing or inconsistent values
* Preventing request blocking using headers

---

## 💼 Resume Description

Developed a web scraping and data analysis pipeline using Python. Extracted and processed product data from multiple web pages, performed exploratory data analysis, and generated insights using data visualization techniques.

---

## 🌟 Future Improvements

* Build an interactive dashboard using Streamlit
* Implement real-time price tracking
* Add machine learning model for price prediction

---

## 👩‍💻 Author

Afrin Banu Z
  (B.Tech. Artificial Intelligence and Data Science)


