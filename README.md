# 📊 Survey Data Analysis: Low-Income Households in Bulacan

This repository contains a Python + SQL-based data analysis project focused on understanding the **electricity consumption and living conditions** of **low-income households** in Bulacan, Philippines.

## 📌 Objective

To clean and analyze household survey data and extract meaningful insights about:
- Income levels and financial challenges
- Presence of students and their access to technology
- Energy budgets vs. actual bills
- Appliance ownership (essential vs. luxury)
- Struggles in paying electricity bills

## 📂 Project Structure

- `Survey.csv`: Raw survey data
- `Survey_Database.db`: SQLite database used for storing intermediate and final tables
- `notebook.ipynb`: Jupyter/Colab notebook performing all data operations and analysis
- `README.md`: Project overview and instructions

## 🧰 Tools Used

- **Python**: Data manipulation, analysis, and visualization
- **Pandas**: DataFrame operations
- **SQLite3**: SQL-based querying and table management
- **Matplotlib**: Visualizations (pie and bar charts)

## 🧪 Key Steps

### Part 1: Data Preparation
- Load CSV data into Pandas
- Create SQLite tables and perform basic SQL queries
- Filter households based on location (Bulacan) and student presence
- Create filtered and structured tables: `Main_Table`, `With_Students`, etc.

### Part 2: Data Analysis
- Focus on households earning **< Php 21,194/month**
- Compute average electricity bills and compare them with budgets
- Examine appliance ownership and identify access gaps
- Visualize struggles and failure to pay electricity bills
- Explore correlations between students, technology, and energy usage

## 📈 Key Insights

- Low-income households, on average, spend **Php 3,498.95** on electricity but only budget **Php 2,327.08**.
- Many households still lack access to essential technology despite having students at home.
- Significant percentage struggle or fail to pay their electric bills regularly.

## 🔚 Conclusion

This analysis highlights the pressing financial constraints faced by low-income families and their implications on education, access to technology, and energy security. The findings can support local policy decisions or aid organizations focusing on household energy access and poverty alleviation.

---

✅ For detailed analysis and visualizations, open the [notebook](notebook.ipynb).
