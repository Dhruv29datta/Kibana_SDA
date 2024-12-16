# Kibana Visualization Analysis

## Introduction
This analysis explores key visualizations created in **Kibana** using a dataset that includes columns such as:

- `branch`
- `city`
- `customer_type`
- `gender`
- `product_line`
- `unitprice`
- `quantity`
- `tax5`
- `total`
- `payment`
- `cogs`
- `gross_margin_percentage`
- `gross_income`
- `rating`

The charts provide insights into customer behavior, product sales, payment methods, and regional trends. Below, we break down each chart and highlight the insights derived from them.

## Chart Analysis

### 1. Customer Types and Preferences 

![Customer Types and Preferences](https://drive.google.com/uc?id=19QGrWNF7Yfw_v7jirvLiFpIsd5E8r9mD)

- **Insight:**
  - This bar chart compares the unique count of `name.keyword` (customers) segmented by `customer_type`.
  - Members (3) dominate the customer base compared to Normal (3) and `customer_type` (1).
- **Implication:**
  - A significant number of returning customers may indicate the effectiveness of membership programs.
  - However, the low count for certain categories like `customer_type` suggests a need for deeper engagement.

### 2. Employees per Region

![Employees per Region](https://drive.google.com/uc?id=1uHW3lAU6YpCqNAeNE_Gb5ngVeI7wx7OI)

- **Insight:**
  - The bar chart shows the unique count of employees segmented by `numberOfEmployees.keyword`.
  - Regions such as "Other" have the largest number of employees, followed by specific employee counts like 189.0945, 217.8355, and 276.948.
- **Implication:**
  - The distribution suggests that the workforce may be concentrated in certain high-performing areas.
  - The dominance of the "Other" category may indicate a lack of granularity in some regions.

### 3. Country and Sales of Product 

![Country and Sales of Product](https://drive.google.com/uc?id=1g_-Cr-AIP_V0Gmm1x4dnmSDMO30WYeLf)

- **Insight:**
  - This grouped bar chart displays `product_line` sales across various cities, including Mandalay, Naypyitaw, Yangon, and Others.
  - Cities like Mandalay and Naypyitaw have consistent sales across product lines.
- **Implication:**
  - Strong performance in specific cities highlights areas of opportunity for further growth.
  - Product lines like Food and Beverages and Electronics Accessories perform well across cities.

### 4. Type of Sales 

![Type of Sales](https://drive.google.com/uc?id=1wj1LG9jgUi_V-5daX-S0wbTb4NjAHHgs)

- **Insight:**
  - A pie chart displays the share of sales by `product_line`.
  - Major contributors include:
    - Electronics Accessories (15.38%)
    - Fashion Accessories (15.38%)
    - Health/Beauty (13.38%)
    - Other (23.08%)
- **Implication:**
  - Electronics and Fashion products are key drivers of revenue.
  - The significant "Other" category may include unclassified or niche products, requiring further breakdown.

### 5. Mode of Payment 

![Mode of Payment](https://drive.google.com/uc?id=1xuDTalxoEacVDQAZbVt9SdzQCkMBSn80)

- **Insight:**
  - This bar chart showcases the preferred modes of payment, including Cash, Credit Card, and Ewallet.
  - Cash and Credit Card are the top modes of payment, while Ewallet usage lags.
- **Implication:**
  - Ewallet adoption remains low, suggesting a potential opportunity to promote digital payment solutions.
  - Focused campaigns or incentives could improve the adoption of alternative payment methods.

### 6. Country and Average Sales

![Country and Average Sales](https://drive.google.com/uc?id=1HCJhzkSCmW2SpsmunOL9Ia80IIqCEam5)

- **Insight:**
  - This matrix visualization highlights city-specific average sales.
  - Naypyitaw (191), Yangon (186), and Mandalay (180) report the highest average sales.
- **Implication:**
  - Naypyitaw is a leading performer in average sales.
  - Understanding factors contributing to higher sales in Naypyitaw can help replicate success in other regions.

### 7. Sales by Country 

![Sales by Country](https://drive.google.com/uc?id=1B8fOnyofg-AjOF4nV1xssNJ5iYr3fse8)

- **Insight:**
  - This donut chart highlights the percentage of sales by country:
    - Mandalay, Naypyitaw, and Yangon each contribute 31.58% of sales.
    - A small share (5.26%) comes from "City".
- **Implication:**
  - Sales are distributed evenly across major cities, indicating a balanced market presence.
  - However, the low contribution from "City" suggests untapped potential.

### 8. Sale by Gender

![Sale by Gender](https://drive.google.com/uc?id=11BPW9F5a3TLAjhFl80lSuPlarTP2ec9E)

- **Insight:**
  - This bar chart shows gender-based sales distribution.
  - Female and Male customers are the primary contributors, with a small segment categorized as `gender`.
- **Implication:**
  - Balanced sales across genders indicate no specific gender bias in the customer base.
  - However, analyzing preferences by gender could help tailor marketing strategies.

### 9. Average Price Sales

![Average Price Sales](https://drive.google.com/uc?id=1jMAkCqwITCI-PmVOI3qT_1Ja_3t7_P6V)

- **Insight:**
  - A pie chart divides average price sales into several segments:
    - Highest contributors: Other (28.57%), followed by price segments like 37.15, 34.56, and 23.75.
    - All other price segments contribute equally (~14.29%).
- **Implication:**
  - The "Other" category dominates, which may require a clearer classification.
  - Equal distribution across price segments indicates product diversity and varied pricing strategies.

## Conclusion
The Kibana charts provide valuable insights into customer behavior, product preferences, sales distribution, and payment trends:

- Cities like Naypyitaw and Mandalay emerge as high performers, with significant contributions to sales.
- Product lines such as Electronics Accessories and Fashion Accessories drive revenue, while "Other" categories may need further breakdown for clarity.
- Modes of payment highlight an opportunity to increase Ewallet adoption.
- Gender and average price sales indicate balanced performance across segments but suggest room for targeted marketing strategies.

These insights can guide decision-making processes, helping businesses optimize sales, improve customer engagement, and enhance market penetration.


---

The video file containing the dashboard overview is provided below:

[Click here to watch the video](https://drive.google.com/file/d/1zFV55OMmNb90-W9q3wholOg-g4hlU3t6/view?usp=sharing)



