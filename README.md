
# 🛒Market Basket Analysis Project

##  About the Project
This project applies **Market Basket Analysis** on a dataset of grocery transactions.  
The dataset contains **Arabic product names** representing items bought together by customers.  
The goal is to identify frequent itemsets and generate association rules that can help in understanding customer buying behavior.

---

##  Dataset
- **Source:** Local dataset with Arabic grocery items.  
- **Format:** Transactions of products purchased together.  
- **Example row:** "سكر, لبن, شاي"  

---

##  Steps in the Notebook
1. **Data Preprocessing**
   - Reading the dataset.
   - Cleaning and formatting transactions.

2. **Encoding Transactions**
   - Using `TransactionEncoder` to transform data into a binary matrix.

3. **Frequent Itemsets**
   - Applying **Apriori algorithm** to extract frequent item combinations.

4. **Association Rules**
   - Generating rules with `support`, `confidence`, and `lift` metrics.

5. **Insights**
   - Identifying which products are commonly bought together.

---

## Tools & Libraries
- Python  
- Pandas  
- Mlxtend  
- Matplotlib / Seaborn (for visualization)  

---

## Results
- Extracted frequent itemsets (e.g.,فراخ, بطاطس})  
- Generated association rules to support market decisions.  
- Insights can be used for:
  - Store layout optimization.
  - Product bundling and cross-selling.
  - Personalized recommendations.  

