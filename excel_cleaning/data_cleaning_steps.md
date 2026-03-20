# 🧹 Data Cleaning Process (Excel)

## 📌 Objective

The goal of this step is to transform the raw retail dataset into a clean, structured, and analysis-ready format suitable for SQL querying, machine learning, and dashboard visualization.

---

## 📂 Dataset Information

* Source: Superstore Dataset (Kaggle)
* Format: Excel (.xlsx)
* The dataset was relatively clean but required additional preprocessing for consistency and usability.

---

## 🔍 Step 1: Initial Data Inspection

* Reviewed dataset structure and column names
* Checked for missing values and inconsistencies
* Verified data types (dates, numerical, categorical)

---

## 🧹 Step 2: Data Cleaning

* Removed duplicate records to ensure data integrity
* Checked and handled missing/null values
* Standardized text fields (e.g., Region, Category)
* Removed extra spaces using TRIM function

---

## 🔧 Step 3: Data Transformation

* Converted **Order Date** into proper date format
* Extracted:

  * Order Month
  * Order Year
* Ensured Sales, Profit, and Quantity were in correct numeric format

---

## 🧠 Step 4: Feature Engineering

Created new columns to enhance analysis:

* **Profit Margin** = Profit / Sales
* **Order Month** for time-based analysis
* Standardized categorical values for consistency

---

## ✅ Step 5: Final Validation

* Ensured no duplicate rows remain
* Verified no critical missing values
* Confirmed consistent formatting across all columns

---

## 💾 Output

The cleaned dataset was saved as:

`data/clean_data.xlsx`

This dataset is now ready for:

* SQL-based analysis
* Python (EDA & Machine Learning)
* Power BI / Tableau dashboards

---

## 💡 Key Takeaway

Even though the dataset was relatively clean, additional preprocessing ensured it is fully optimized for analytical workflows and real-world business use cases.
