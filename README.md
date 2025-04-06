# 🛒 Market Basket Analysis

This project presents a Market Basket Analysis (MBA) performed on transactional data using association rule mining. The main objective is to identify patterns in customer purchases and discover strong associations between different items bought together. The insights drawn can help in product placement, recommendation systems, cross-selling strategies, and inventory management.

---

## 📊 Project Overview

- **Objective:** Discover associations between items purchased together using Apriori algorithm and Association Rule Mining.  
- **Dataset:** Transactional data containing 15 customer baskets.  
- **Techniques Used:**
  - Data Preprocessing
  - One-Hot Encoding
  - Apriori Algorithm
  - Association Rule Mining
  - Data Visualization

---

## 🛠️ Tools & Libraries

- Python  
- Pandas  
- MLxtend (for Apriori and association rules)  
- Matplotlib & Seaborn (for visualizations)  

---

## 📌 Key Steps

1. **Data Loading and Cleaning**  
   - Raw transactional data from a CSV was converted into a format suitable for analysis.  
   - Missing values were handled, and transactions were structured into item lists.

2. **Data Transformation**  
   - Data was transformed using one-hot encoding to apply the Apriori algorithm.

3. **Frequent Itemsets Mining**  
   - Used the Apriori algorithm to generate frequent itemsets with a minimum support threshold.

4. **Association Rule Generation**  
   - Association rules were extracted using confidence and lift metrics.  
   - Top rules were analyzed for actionable insights.

5. **Visualization**  
   - Bar plots for item frequency.  
   - Heatmaps for rule strength (support, confidence, lift).

---

## 📈 Results & Insights

- Several strong associations were discovered:
  - Example: `{milk} → {bread}` with high support and lift.
  - The combination `{eggs, milk}` frequently appeared in strong rules.
- Visualizations helped in quickly identifying the most frequent items and the most promising item combinations.

---

## 🔍 Use Cases

- **Retail Analytics:** Improve product placement and store layout.  
- **E-Commerce:** Power recommendation engines (e.g., "Customers also bought").  
- **Inventory Optimization:** Stock frequently co-purchased items together.
