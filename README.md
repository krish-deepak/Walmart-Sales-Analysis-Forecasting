
# Walmart Black Friday Sales: A Statistical Analysis of Customer Behavior

### 1. Business Problem
The management team at Walmart aims to understand customer purchasing behavior during the Black Friday event to make better data-driven decisions. The core objective is to statistically analyze and compare the purchase amounts across different demographic segments—specifically **Gender**, **Marital Status**, and **Age**—to tailor marketing and sales strategies effectively.

### 2. Dataset
The analysis was performed on a transactional dataset from Walmart's Black Friday sales, capturing 550,068 transactions. Key features include `User_ID`, `Gender`, `Age`, `City_Category`, `Marital_Status`, `Product_Category`, and the target variable, `Purchase` amount.

### 3. Technical Stack
* **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---
## 4. Analytical Methodology

The project was executed in two main phases: a comprehensive Exploratory Data Analysis (EDA) followed by a deep dive using Inferential Statistics to generalize findings from the sample data to the entire customer population.

### Phase I: Exploratory Data Analysis (EDA)

The initial phase involved a thorough investigation of the dataset's characteristics and visible trends.

* **Data Profiling:** The dataset was loaded and characterized, confirming its structure and data types. A key finding was the absence of null values, indicating a high-quality source dataset.
* **Univariate Analysis:** The distribution of key variables was analyzed. It was observed that customers in the **26-35 age group** represent the largest segment of shoppers, and there are more male shoppers than female shoppers in the dataset.
* **Bivariate Analysis:** The relationship between demographic features and purchase amount was visualized using boxplots and countplots. This visual analysis consistently showed that **men tend to have a higher purchase amount per transaction than women**.

### Phase II: Inferential Statistics & Hypothesis Testing

To draw robust conclusions about the entire customer population (e.g., 50 million males and 50 million females), the **Central Limit Theorem (CLT)** was applied. This approach allows us to make statistically significant claims rather than relying on visual inspection alone.

* **Confidence Interval Framework:** 95% confidence intervals were constructed for the average purchase amount for different customer segments. The key question was whether the confidence intervals for different groups (e.g., male vs. female) would overlap.
* **Demographic Segmentation Analysis:** This statistical framework was systematically applied to three key demographic comparisons:
    1.  **Gender:** The analysis confirmed that the 95% confidence intervals for the average male and female purchase amounts **do not overlap**. This provides statistical evidence that men, on average, spend more than women during Black Friday.
    2.  **Marital Status:** The spending habits of married vs. unmarried customers were similarly compared to identify any significant differences.
    3.  **Age:** Customers were grouped into life-stage bins, and the analysis identified the age groups with the highest average spending, with the **26-35 segment** being a key high-value group.

---
## 5. Actionable Recommendations for Walmart

Based on the statistical findings, the following non-technical, data-driven recommendations were proposed:

* **Target High-Value Demographics:** Launch targeted marketing campaigns and product promotions specifically aimed at **male customers aged 26-35**, as this segment is statistically proven to have the highest purchasing power during the Black Friday event.
* **Customize Marketing Communications:** Tailor marketing messages based on marital status and age. For example, promote high-value individual items like electronics to unmarried customers, while showcasing family-oriented or household bundle deals to married customers.
* **Optimize Product Inventory:** Use the insights on which product categories are most popular within the highest-spending demographics to optimize inventory levels, ensuring stock availability of high-demand items and maximizing sales potential.
