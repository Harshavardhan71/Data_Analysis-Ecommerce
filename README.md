# Amazon Sales Analysis

## Project Overview
This project analyzes Amazon sales data sourced from Kaggle to gain insights into revenue trends, customer behavior, product performance, and shipping efficiency. Using Python and Pandas, we explore various sales metrics, visualize trends, and extract meaningful insights.

## Dataset
- **Source**: Kaggle
- **File**: `Amazon Sale Report.csv`
- **Key Columns**:
  - `Date` (Order Date)
  - `SKU` (Product Identifier)
  - `Amount` (Revenue Generated)
  - `Qty` (Quantity Ordered)
  - `ship-city`, `ship-state`, `ship-country`
  - `Status` (Order Status: Completed, Cancelled, etc.)
  - `B2B` (Business vs Consumer)
  - `Fulfilment` (Amazon vs Merchant Fulfilled)
  - `Category`, `Style`, `promotion-ids`

## Analysis Performed
### Sales Analysis
1. **Total Revenue Over Time**
   - Calculate total revenue
   - Plot revenue trends
2. **Top 10 Products by Sales**
   - Identify best-selling products
   - Visualize top products
3. **Average Order Value**
   - Compute the average revenue per order
4. **Peak Sales Periods**
   - Analyze sales by day, week, month, year
   - Identify high-sales periods

### Customer Analysis
1. **Top Cities, States, and Countries by Sales**
   - Identify key sales regions
2. **Order Cancellation Trends**
   - Analyze cancellation trends over time
3. **B2B vs B2C Distribution**
   - Compare business and consumer sales trends

### Shipping Analysis
1. **Amazon vs Merchant Fulfillment**
   - Analyze the share of orders fulfilled by Amazon vs Merchants

### Product Analysis
1. **Popular Product Categories**
   - Identify best-selling categories
2. **Popular Styles**
   - Find top styles based on sales
3. **Average Quantity Ordered**
   - Compute the average number of items per order

### Promotional Analysis
1. **Most Common Promotions Used**
   - Identify frequently used promotions

### Geographical Analysis
1. **Key Markets for Sales**
   - Identify top-performing regions

### Monthly Analysis
1. **Seasonal Trends by Product Category**
   - Analyze how monthly trends affect product sales

## Technologies Used
- **Python** (Pandas, Matplotlib)
- **Jupyter Notebook**
- **Data Visualization** (Matplotlib, Pandas)

## Visualizations
- Revenue trends over time
- Top products by sales
- Peak sales periods
- Regional sales trends
- B2B vs B2C distribution
- Order cancellations over time

## Conclusion
This project provides insights into Amazon sales patterns, helping businesses optimize their product offerings, marketing strategies, and operational efficiency. Future work can include:
- Machine learning models for sales prediction
- Sentiment analysis on customer reviews
- Customer segmentation for personalized marketing
