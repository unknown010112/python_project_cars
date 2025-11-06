# 🚗 Car Sales Data Analysis

## 📊 Overview

This project is an Exploratory Data Analysis (EDA) of a car sales dataset. The goal is to extract 5 Key Insights into the car market, including manufacturer popularity, pricing trends, and the impact of features (like mileage and manufacturing year) on a car's value.

The entire project is executed in a single Python script, focusing on efficient data cleaning and generating a unified visual dashboard to present all findings.

## 🎨 Visualization Style

This project intentionally uses a **Dark Theme** for all plots (`dark_background` and the `Blues_r` palette) to ensure a professional and visually cohesive look.

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas:** For data processing and cleaning.
- **NumPy:** For numerical operations and aiding in the cleaning process.
- **Matplotlib:** For creating the main subplot framework.
- **Seaborn:** For generating advanced and attractive statistical visualizations.

## 🧽 Data Cleaning & Preparation

Before analysis, robust cleaning steps were performed to ensure the accuracy of the insights:

1.  **Missing Values:**
    - Numerical missing values (like `Price`) were filled with the column's **Median**.
    - Categorical missing values (like `Fuel type`) were filled with the column's **Mode**.
2.  **Duplicate Rows:**
    - All duplicate rows were checked and removed (`drop_duplicates()`) to ensure results were not skewed.

## 💡 Top 5 Insights & Analysis

The script generates a unified dashboard containing 5 key analyses.

**(Note: To save this image, add `plt.savefig('car_sales_dashboard.png', bbox_inches='tight')` before `plt.show()` in your code.)**

---

### 1\. 🏆 Top 10 Popular Manufacturers

- **Analysis:** A bar chart showing the number of cars listed for each manufacturer.
- **Insight:** Identifies which manufacturers dominate the market in terms of listing volume.

### 2\. 📉 Price vs. Mileage

- **Analysis:** A scatter plot comparing mileage to the car's price.
- **Insight:** Visually confirms the expected inverse relationship; as mileage increases, the price typically decreases.

### 3\. ⛽ Fuel Type Distribution

- **Analysis:** A pie chart showing the market share of each fuel type (Petrol, Diesel, Hybrid, etc.).
- **Insight:** Gives a quick snapshot of current market preferences or available stock types.

### 4\. 📈 Average Price by Year

- **Analysis:** A line plot tracking the average car price against its year of manufacture.
- **Insight:** Clearly shows how a car's age and depreciation trends directly impact its value.

### 5\. 💰 Top 10 Most Expensive Manufacturers

- **Analysis:** A bar chart ranking the top 10 manufacturers based on the average selling price of their vehicles.
- **Insight:** Identifies the luxury and high-end brands present in the dataset.

