# Data-Analysis-SuperStore-Python
# Superstore Sales and Profit Analysis

## Objective

This project analyzes a Superstore dataset to uncover trends and insights related to sales, profit, and other performance metrics. The analysis aims to provide actionable recommendations to improve business strategies and performance.

---

## Dataset Summary

The dataset contains 21 columns and 9995 rows, providing information about transactions, categorized by product categories, sub-categories, regions, customer segments, and discounts. Key columns include:

| **Column Name**            | **Description**                         |
|----------------------------|-----------------------------------------|
| `Order Date`               | Date of the order placed               |
| `Sales`                    | Revenue generated from sales            |
| `Profit`                   | Profit earned from sales                |
| `Category`                 | Main product category                   |
| `Sub-Category`             | Sub-category under main category        |
| `Customer Segment`         | Segment of the customer                 |
| `Region`                   | Regional classification of the sales    |
| `Discount`                 | Discount applied                       |

---

## Questions Explored

1. **Monthly Sales Analysis**:
   - Calculate monthly sales and identify the months with the highest and lowest sales.
2. **Category-Wise Sales**:
   - Analyze sales based on product categories to find the highest and lowest-performing categories.
3. **Sub-Category Sales**:
   - Determine sales performance at the sub-category level.
4. **Monthly Profit Analysis**:
   - Calculate monthly profits and identify the most and least profitable months.
5. **Category-Wise Profit**:
   - Assess profitability across product categories.
6. **Sub-Category Profit Analysis**:
   - Evaluate profits generated at the sub-category level.
7. **Customer Segment Analysis**:
   - Analyze sales and profits across different customer segments.
8. **Sales-to-Profit Ratio**:
   - Assess the efficiency of converting sales into profit.
9. **Regional Sales Analysis**:
   - Evaluate sales performance across different regions.
10. **Discount Impact**:
    - Group sales and profit by discount ranges.

---

## Key Insights

1. **Monthly Sales**:
   - **Highest Sales Month**: November 2017 with **$118,447.83**.
   - **Lowest Sales Month**: February 2014 with **$4,519.89**.

2. **Category Sales**:
   - **Highest Sales Category**: Technology with **$836,154.03**.
   - **Lowest Sales Category**: Office Supplies with **$719,047.03**.

3. **Sub-Category Sales**:
   - **Highest Sales Sub-Category**: Phones with **$330,007.05**.
   - **Lowest Sales Sub-Category**: Fasteners with **$3,024.28**.

4. **Monthly Profit**:
   - **Most Profitable Month**: December 2016 with a profit of **$17,885.31**.
   - **Least Profitable Month**: January 2015 with a loss of **$3,281.01**.

5. **Profit by Category**:
   - **Highest Profit Category**: Technology with **$145,454.95**.
   - **Lowest Profit Category**: Furniture with **$18,451.27**.

6. **Profit by Sub-Category**:
   - **Highest Profit Sub-Category**: Copiers with **$55,617.82**.
   - **Lowest Profit Sub-Category**: Tables with a loss of **$17,725.48**.

7. **Sales and Profit by Segment**:
   - **Highest Sales and Profit Segment**: Consumer with sales of **$1,161,401.00** and a profit of **$134,119.21**.
   - **Lowest Sales and Profit Segment**: Home Office with sales of **$429,653.10** and a profit of **$60,298.68**.

8. **Sales-to-Profit Ratio**:
   - The average sales-to-profit ratio was calculated to be approximately **6.41**.

9. **Sales by Region**:
   - **Highest Sales Region**: West with total sales of **$725,457.82**.
   - **Lowest Sales Region**: South with total sales of **$391,721.91**.

10. **Discount Impact**:
    - **0-20% Discount**: Total sales of **$846,522.24** with a profit of **$100,785.47**.
    - **20-40% Discount**: Total sales of **$234,137.90** with a loss of **$35,817.47**.
    - **40-60% Discount**: Total sales of **$71,048.21** with a loss of **$28,944.19**.
    - **60-80% Discount**: Total sales of **$57,584.04** with a loss of **$70,614.40**.
    - **80-100% Discount**: No sales recorded.

---

## Tools & Libraries

- **Python**: Used for analysis and visualization.
- **Pandas, NumPy**: For data manipulation and aggregation.
- **Matplotlib, Plotly**: For data visualization.
- **Jupyter Notebook**: For interactive analysis and reporting.

---

## Recommendations

1. **Boost Profits in Key Categories**:
   - Focus on Technology and Copiers to leverage their strong profitability.
   - Reassess pricing and operational efficiency in Furniture, especially Tables.

2. **Optimize Discount Strategy**:
   - Maintain discounts in the 0-20% range for maximum profitability.
   - Avoid discounts above 40%, as they result in significant losses.

3. **Regional Improvements**:
   - Allocate resources to the West region to sustain its high sales.
   - Develop targeted strategies to uplift sales in the South region.

4. **Segment-Specific Strategies**:
   - Strengthen campaigns for the Consumer segment to maintain its dominance.
   - Innovate offerings to attract and retain Home Office customers.

---

## Conclusion

The analysis reveals:

1. **Technology and Copiers** drive the highest profits, warranting strategic investments.
2. **Tables and high discount ranges** are significant loss areas, needing operational and pricing corrections.
3. **Regional and segment-specific strategies** can further optimize performance.
4. Focusing on efficient discounting and resource allocation will enhance overall profitability and market presence.
