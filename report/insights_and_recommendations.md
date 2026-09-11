# Insights & Recommendations

## Key Insights

### 1. Overall Sales Performance
- Total revenue generated from the cleaned dataset is approximately 10.64 million.
- A total of approximately 5.57 million units were sold.
- The dataset contains approximately 19,960 distinct orders.
- There are approximately 4,338 identifiable customers.

### 2. Country-wise Sales
- The United Kingdom is the dominant market and contributes the majority of total revenue.
- The Netherlands, EIRE, Germany, and France are among the other important markets.
- This indicates a strong concentration of sales in the UK, while selected European markets provide additional revenue opportunities.

### 3. Product Performance
- Revenue is concentrated among a relatively small group of high-performing products.
- Identifying and maintaining sufficient inventory for these products can help reduce the risk of stock-outs.
- Lower-performing products can be reviewed for pricing, promotion, or discontinuation decisions.

### 4. Customer Performance
- Revenue is concentrated among a group of high-value customers.
- These customers represent an important opportunity for retention and loyalty initiatives.
- Customer-level analysis should focus on customers with valid CustomerID values because some transactions do not contain customer identifiers.

### 5. Quantity and Revenue Relationship
- Quantity and revenue show a strong positive correlation of approximately 0.91.
- This suggests that transaction quantity is strongly associated with revenue in this dataset.
- Correlation indicates association and should not be interpreted as proof of causation.

### 6. Data Quality
- The original dataset contained duplicate records, missing descriptions, missing customer IDs, cancellations, negative quantities, and non-positive unit prices.
- Duplicate records were removed.
- Rows with missing descriptions were removed.
- Cancellation transactions, negative quantities, and non-positive prices were excluded from the final sales analysis.
- Missing CustomerIDs were retained for overall sales analysis but excluded from customer-specific analysis.

## Recommendations

1. **Focus on the UK market:** Since the UK generates the majority of revenue, maintain strong inventory availability and customer service in this market.

2. **Expand promising international markets:** Analyze markets such as the Netherlands, EIRE, Germany, and France to identify opportunities for targeted promotions and expansion.

3. **Prioritize high-performing products:** Maintain adequate stock of products generating the most revenue and monitor their demand regularly.

4. **Strengthen customer retention:** Develop loyalty programs, personalized offers, and targeted campaigns for high-value customers.

5. **Use sales trends for inventory planning:** Monthly revenue patterns can be used to improve demand forecasting and inventory decisions.

6. **Improve customer data collection:** Reducing transactions with missing CustomerID values would enable more complete customer segmentation and lifetime-value analysis.

7. **Monitor cancellations and returns:** Although excluded from the final sales analysis, cancellation activity should be tracked separately because it can reveal product, fulfillment, or customer-service issues.