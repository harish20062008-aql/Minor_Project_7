# Minor_Project_7
# 🛒 QuickCart Market Basket Analysis

## 📌 Project Overview
QuickCart Market Basket Analysis is a Data Mining and Unsupervised Machine Learning project that analyzes frequently purchased product combinations using Market Basket Analysis.

The project focuses on discovering frequent itemsets and identifying meaningful relationships between products using Support, Confidence, and Lift. These insights can help businesses improve product recommendations, cross-selling, bundle offers, and store placement strategies.

## 🎯 Objectives
- Discover frequently purchased product combinations
- Analyze frequent itemsets
- Calculate and interpret Support
- Generate meaningful association rules
- Identify useful product relationships
- Support cross-selling and recommendation strategies

## 📊 Dataset
- 5,000 Orders
- 26,878 Transaction Records
- 60 SKUs
- 12 Stores
- Average Basket Size: 5.38
- 256 Frequent Itemsets

## 🔍 Key Concepts

### Support
Measures how frequently an itemset appears in the transactions.

### Confidence
Measures the probability of purchasing one product when another product is purchased.

### Lift
Measures how strongly two products are associated compared with random occurrence.

- Lift > 1 → Positive association
- Lift = 1 → Independent relationship
- Lift < 1 → Negative association

## ⚙️ Methodology

Transaction Data
↓
Data Preprocessing
↓
Basket Transformation
↓
Transaction Encoding
↓
Apriori / FP-Growth
↓
Frequent Itemsets
↓
Association Rules
↓
Business Insights

## 🧠 Algorithms
- Apriori
- FP-Growth
- Association Rule Mining

## 📈 Key Product Associations
Some important product relationships identified in the project include:

- Toned Milk → White Bread
- Basmati Rice → Toor Dal
- Potato Chips → Cola
- Ghee → Poha
- Instant Coffee → Choco Cookies
- Hand Sanitizer → Face Wash

## 💼 Business Applications
- Frequently Bought Together recommendations
- Product bundling
- Cross-selling
- Personalized recommendations
- Store shelf placement
- Promotional offers
- Inventory planning

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- mlxtend
- Google Colab

## 📁 Project Files
- `frequent_itemsets.csv` — Frequent itemsets dataset
- `quickcart_frequent_itemsets_analysis.csv` — Analysed output
- Python programs for data analysis and visualization

## 🚀 Conclusion
QuickCart Market Basket Analysis demonstrates how transaction data can be transformed into actionable business insights by discovering product relationships and frequently purchased itemsets.

The project shows how Market Basket Analysis can support smarter recommendations, product bundling, and cross-selling strategies.

## 👨‍💻 Author
HARISH S

#Python #MachineLearning #DataMining #MarketBasketAnalysis #Apriori #FPGrowth #AssociationRules #Pandas #DataScience #QuickCart
