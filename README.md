
# 📦 Flipkart E-commerce Product Analysis – Capstone Project

## 📖 Description
This Capstone Project focuses on web scraping Flipkart product data and applying data science techniques to analyze and cluster products based on their price, rating, and reviews. The goal is to gain meaningful business insights by segmenting products into groups using unsupervised machine learning.

---

## 🔧 Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Selenium** & **BeautifulSoup** (Web Scraping)
- **Pandas**, **NumPy** (Data Handling)
- **Matplotlib**, **Seaborn** (Data Visualization)
- **Scikit-learn** (Clustering & Machine Learning)

---

## 🔎 Project Workflow

### 1. Web Scraping
- Data collected from **Flipkart** across multiple categories:
  - Home Accessories
  - Books
  - Office Supplies
  - Beauty Products
- Extracted fields: `Product Name`, `Price`, `Rating`, `Number of Reviews`

### 2. Data Cleaning & Preprocessing
- Removed missing or null values
- Converted data types (e.g., `price` & `rating` to float)
- Normalized and standardized data for clustering

### 3. Exploratory Data Analysis (EDA)
- Visualized distribution of prices and ratings
- Analyzed relationships between product price and ratings

### 4. Clustering (K-Means)
- Used **KMeans** to group similar products
- **Elbow Method** applied to find the optimal number of clusters
- Products clustered into:
  - Budget Items
  - Mid-range Products
  - Premium Offerings

#### 📌 Why Clustering?
- Helps businesses **understand customer segments**
- Enables **pricing strategy optimization**
- Useful for **targeted marketing**

---

## 📊 Key Results
- Identified distinct product clusters based on price and rating
- Cluster visualization clearly differentiated product types
- Elbow Method validated the choice of `k` (number of clusters)

---

## 💡 Future Improvements
- Include additional product attributes (discounts, brand, delivery time)
- Apply NLP to analyze review text
- Deploy the model in a web app or dashboard (e.g., using Streamlit or Power BI)
