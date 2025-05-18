# Market Basket Analysis using Apriori Algorithm 🛒📊

This project performs Market Basket Analysis on transactional sales data using the Apriori algorithm to identify frequent itemsets and generate association rules.

## 📁 Project Structure

- `Market_Basket_Analysis.ipynb` - The complete analysis and model code (Google Colab notebook)
- `index.html` & `recommendations.html` (optional) - Web interface for item recommendations
- `requirements.txt` (optional) - Python dependencies

## 🚀 Features

- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of:
  - Top-selling products
  - Transaction sizes
  - Customer purchase patterns
- Association rule mining using Apriori
- Simple Flask web app to provide item recommendations based on selected items

## 📦 Libraries Used

- `pandas`
- `matplotlib`
- `mlxtend`
- `flask`, `flask-ngrok`

## 🧠 How it Works

1. Load and clean the data
2. Analyze customer behavior
3. Apply Apriori algorithm to find frequent itemsets
4. Generate association rules (e.g., confidence, lift)
5. Provide item suggestions using Flask web app

## 🔗 Run Locally

To run the Flask app locally:

```bash
pip install flask flask-ngrok mlxtend openpyxl
python app.py

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
