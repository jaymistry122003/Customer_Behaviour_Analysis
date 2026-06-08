Customer_Behaviour_Analysis
Analyzed 3,900 customer transactions to uncover spending patterns and guide business decisions. Built a data pipeline using Python for cleaning, PostgreSQL for customer segmentation and revenue analysis, and Power BI to design interactive dashboards visualizing key demographics and sales trends

 Customer Shopping Behavior Analysis 

 Project Overview
This repository contains an end-to-end data analysis project that explores customer shopping behavior using transactional data from 3,900 purchases[cite: 1]. The goal of this project is to uncover actionable insights into spending patterns, product preferences, and customer segments to drive strategic business decisions[cite: 1].

---

 🛠️ Tech Stack & Workflow
*   **Python:** Data cleaning, missing value imputation, and feature engineering[cite: 1].
*   **PostgreSQL:** Advanced querying for customer segmentation and financial metrics[cite: 1].
*   **Power BI:** Interactive dashboard design for visual storytelling[cite: 1].

---

 🧹 Phase 1: Data Preparation (Python)
The initial dataset contained 3,900 rows and 18 columns[cite: 1]. Key data preparation steps included:
*   **Imputation:** Handled 37 missing values in the `Review Rating` column by applying the median rating of each specific product category[cite: 1].
*   **Feature Engineering:** Created new analytical dimensions like `age_group` (by binning customer ages) and `purchase_frequency_days`[cite: 1].
*   **Data Optimization:** Standardized column names to snake_case for consistency and removed redundant data (dropped the `promo_code_used` column)[cite: 1].
*   **Database Integration:** Loaded the cleaned dataset directly into PostgreSQL for structured analysis[cite: 1].

---

 📊 Phase 2: Business Analysis (SQL)
Using PostgreSQL, I queried the database to translate raw transactions into answers for key business questions:
*   **Customer Segmentation:** Classified the customer base into Loyal (3,116), Returning (701), and New (83) segments based on their purchase history[cite: 1].
*   **Demographic Revenue:** Identified that Male customers generated significantly more revenue ($157,890) than Female customers ($75,191)[cite: 1]. Additionally, the "Young Adult" demographic contributed the highest total revenue ($62,143)[cite: 1].
*   **Product Performance:** Ranked the top 3 products per category and identified the top 5 highest-rated items overall: Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), and Skirt (3.78)[cite: 1].
*   **Discount Dependency:** Found the products with the highest percentage of discounted purchases, led by Hats (50.00%) and Sneakers (49.66%)[cite: 1].

---

📈 Phase 3: Dashboard & Visualization (Power BI)
Built an interactive Power BI dashboard to give stakeholders a high-level view of customer behaviors[cite: 1]. Key metrics displayed include:
*   An average purchase amount of $59.76 across the dataset[cite: 1].
*   An average overall review rating of 3.75[cite: 1].
*   Visual breakdowns highlighting that only 27% of customers are active subscribers, while 73% are non-subscribers[cite: 1].

---

💡 Strategic Business Recommendations
Based on the analytical findings, I provided the following recommendations to stakeholders:
*   **Targeted Marketing:** Focus marketing efforts on the high-revenue "Young Adult" demographic and users opting for express shipping[cite: 1].
*   **Boost Subscriptions:** Promote exclusive benefits to convert the massive pool of non-subscribers and increase the 27% subscriber base[cite: 1].
*   **Customer Retention:** Implement loyalty programs to reward repeat buyers and transition them into the highly profitable "Loyal" segment[cite: 1].
*   **Discount Strategy:** Review the discount policy on highly dependent items (like Hats and Sneakers) to balance sales volume with profit margin control[cite: 1].
*   **Product Positioning:** Highlight the top-rated and best-selling products prominently in upcoming campaigns[cite: 1].
