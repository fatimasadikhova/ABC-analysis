# ABC Analysis

ABC Analysis is a simple yet powerful method used to classify inventory or products based on their value. It is essential for companies and analysts to allocate resources effectively and make informed decisions.

## Categories in ABC Analysis

- **Category A**: Highly important products that require strict control.
- **Category B**: Moderately important products that require average control.
- **Category C**: Less important products that require only minimal control.

## How to Calculate

1. Calculate the **annual percentage contribution** and **cumulative percentage contribution** of each product.
2. Based on the Pareto Principle (80/20 rule):
   - If the cumulative percentage of a product is **less than 80%**, it is considered very important → **Category A**.
   - If the cumulative percentage is **between 80% and 95%**, it is of medium importance → **Category B**.
   - If the cumulative percentage is **above 95%**, it is less important → **Category C**.

**Excel formula example:**

=IFS(F2<0.8,"A", F2<0.95,"B", TRUE,"C")


## Why Calculate Cumulative Percentage?

 - The goal of ABC Analysis is to group products by their contribution to total sales. The annual sales percentage alone is not enough because you need to know:

 - Which products together account for the first 80% of total sales (A category)

 - Which products account for the next 15% (B category)

 - Which products account for the remaining 5% (C category)

 - This can only be observed using the cumulative percentage.

 - Insights from the Analysis

## Evaluate Products by Category

 - A Products: Highest revenue-generating, critical for the company.

 - B Products: Moderate revenue-generating products.

 - C Products: Low revenue-generating products, often remain in stock longer.

## Determine Stock and Inventory Strategy

 - A Products: High priority, should always be in stock, minimal stockout risk.

 - B Products: Medium priority, stock levels should be balanced.

 - C Products: Low priority, can be kept in minimal quantities or sold through discount campaigns.
