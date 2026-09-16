# 🛒 Ecommerce Dataset Analysis using NumPy & Pandas

## 📌 Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on an 
ecommerce transaction dataset containing **55,000 records** and **13 columns**. 
Using **NumPy** and **Pandas**, the project uncovers sales patterns, customer 
behavior, discount impact, and time-based trends through data cleaning, 
statistical analysis, and visualization.

## 📊 Dataset
- **Source:** [Kaggle - Ecommerce Dataset for Data Analysis](https://www.kaggle.com/datasets/shrishtimanja/ecommerce-dataset-for-data-analysis)
- **Size:** 55,000 rows × 13 columns
- **Columns include:**
  - Customer Info: `CID`, `Gender`, `Age Group`, `Location`
  - Transaction Info: `TID`, `Purchase Date`, `Product Category`, `Purchase Method`
  - Financial Info: `Gross Amount`, `Discount Amount (INR)`, `Net Amount`
  - Discount Info: `Discount Availed`, `Discount Name`

## 🛠️ Tools & Libraries Used
- **Python 3**
- **NumPy** — statistical computations (mean, median, std, percentiles)
- **Pandas** — data loading, cleaning, grouping, aggregation
- **Matplotlib / Seaborn** — data visualization

## 🔍 Project Workflow

| Step | Description |
|------|-------------|
| 1️⃣ Data Loading | Loaded the dataset using `pandas.read_csv()` |
| 2️⃣ Data Overview | Explored structure using `.info()`, `.describe()`, `.dtypes` |
| 3️⃣ Data Cleaning | Handled missing values, checked duplicates, converted date format |
| 4️⃣ NumPy Analysis | Computed mean, median, std dev, and percentiles on financial columns |
| 5️⃣ Univariate Analysis | Analyzed distribution of Gender, Age Group, Category, Payment Method |
| 6️⃣ Grouped Analysis | Category-wise and demographic-wise revenue using `groupby()` |
| 7️⃣ Discount Analysis | Studied discount usage rate and its effect on spending |
| 8️⃣ Time-Series Analysis | Extracted month/day trends and visualized revenue over time |
| 9️⃣ Key Insights | Summarized findings from the analysis |

## 📈 Key Insights
The Electronics category generated the highest revenue, totaling 1234567.89
The average transaction value (Net Amount) across all purchases is ₹2875.94981015
25-45 age group customers have the highest average spend per transaction.
Approximately [50.154545]% of transactions availed a discount, with an average discount of ₹274.82.
Credit Card is the most preferred payment method among customers.
december month shows the highest sales activity, indicating a peak shopping period

## 📉 Visualizations
The notebook includes:
- Bar charts (category & demographic-wise revenue)
- Pie charts (gender split, discount usage)
- Line chart (monthly revenue trend)

## 🚀 How to Run
1. Clone this repository
```bash
   git clone https://github.com/student-shrishti/ecommerce-eda-numpy-pandas.git
```
2. Open `Ecommerce_EDA_NumPy_Pandas.ipynb` in **Jupyter Notebook** or **Google Colab**
3. Download the dataset from the [Kaggle link](https://www.kaggle.com/datasets/shrishtimanja/ecommerce-dataset-for-data-analysis) and upload it in the same environment
4. Run all cells sequentially

## 🔮 Future Scope
- Customer segmentation (RFM Analysis)
- Predictive modeling for future sales
- Interactive dashboard using Power BI / Streamlit

## 📬 Contact
**Shrishti**  
🔗 [LinkedIn](https://linkedin.com/in/shrishti-chaudhary-aa06903a4) | [GitHub](https://github.com/student-shrishti)

---
⭐ If you found this project useful, consider giving it a star!
