# Task 4: Personal Expense Analytics

## 🏢 Internship Details
| Field | Details |
|-------|---------|
| **Company** | Codtech IT Solutions Private Limited |
| **Domain** | Data Analytics |
| **Intern Name** | MD SAHIL ANSARI |
| **Intern ID** | CITS3147 |
| **Task** | Task 4 – Personal Expense Analytics |

---

## 📌 Objective
To analyze 3 months of personal expense data (January–March 2024) to:
- Understand spending patterns across categories and subcategories
- Track monthly and daily spending trends
- Evaluate payment mode preferences
- Compare actual spending against budgets
- Identify recurring vs one-time expenses
- Recommend actionable savings strategies

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `personal_expenses.csv` | 77 expense records across 3 months |
| `personal_expense_analytics.ipynb` | Jupyter Notebook with full analysis |
| `README.md` | Project documentation |

---

## 📊 Dataset Description

The dataset contains **77 expense records** with **13 columns**:

| Column | Description |
|--------|-------------|
| ExpenseID | Unique ID for each expense |
| Date | Date of the expense |
| Category | High-level category (e.g. Food & Dining, Shopping) |
| Subcategory | Sub-type (e.g. Groceries, Restaurant, Fuel) |
| Description | What the expense was for |
| Amount | Amount spent in ₹ |
| PaymentMode | UPI / Cash / Credit Card / Net Banking |
| Location | Where the purchase was made |
| IsRecurring | Yes / No — whether it recurs monthly |
| Month | Month name |
| Week | Week number of the year |
| DayOfWeek | Day name (Monday–Sunday) |

---

## 📈 Analysis Performed

1. **Category-wise Spending** – Bar chart and pie chart of total spending share
2. **Subcategory Breakdown** – Top 12 subcategories by spending
3. **Monthly Spending** – Bar chart and stacked monthly comparison
4. **Daily Spending Trend** – Line chart with average spending reference line
5. **Payment Mode Analysis** – Pie chart and transaction count bar chart
6. **Day-of-Week Pattern** – Weekday vs weekend spending analysis
7. **Recurring vs Non-Recurring** – Split by amount and transaction count
8. **Category-Month Heatmap** – Spending intensity matrix
9. **Top 10 Expenses** – Horizontal bar chart of biggest individual spends
10. **Budget vs Actual** – Side-by-side comparison per category with status

---

## 🛠️ Technologies Used

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Tool:** Jupyter Notebook

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
2. Place `personal_expenses.csv` in the same folder as the notebook
3. Launch Jupyter:
   ```bash
   jupyter notebook personal_expense_analytics.ipynb
   ```
4. Run all: **Kernel → Restart & Run All**

---

## 💡 Key Insights

- **Food & Dining** is the #1 spending category across all months
- **February** had the highest spending due to Valentine's Day events
- **UPI** is the most preferred payment method
- **Weekends** account for disproportionately higher spending
- **Recurring expenses** form a stable, predictable portion of the budget

---

*This project was completed as part of the Codtech IT Solutions Data Analytics Virtual Internship.*
