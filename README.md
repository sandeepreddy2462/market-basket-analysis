# Market Basket Analysis using Apriori Algorithm 🛒📊

This project performs Market Basket Analysis on transactional sales data using the Apriori algorithm to identify frequent itemsets and generate association rules.

## 📁 Project Structure

- `Market_Basket_Analysis.ipynb` - The complete analysis and model code (Google Colab notebook)

## 🚀 Features

- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of:
  - Top-selling products
  - Transaction sizes
  - Customer purchase patterns
- Association rule mining using Apriori

## 📦 Libraries Used

- `pandas`
- `matplotlib`
- `mlxtend`
  
## 🧠 How it Works

1. Load and clean the data
2. Analyze customer behavior
3. Apply Apriori algorithm to find frequent itemsets
4. Generate association rules (e.g., confidence, lift)

📊 Sample Output
Top 10 items bar chart

Sales trend line chart

Customer frequency histogram

Filtered association rules (lift ≥ 6, confidence ≥ 0.8)

🧪 Sample Recommendation
For a customer basket like:

python
Copy
Edit
["ALARM CLOCK BAKELIKE GREEN"]
The system suggests related frequently bought items using learned association rules.
