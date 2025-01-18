# Adidas-Sales-Analysis
## 🗂️ Project Overview
The Adidas Sales Analysis project leverages robust data visualization and collaborative analysis tools to optimize sales strategies and enhance overall performance. This project identifies key sales drivers, geographic performance trends, and product-specific insights, enabling the Adidas team to make informed decisions about pricing, inventory, and marketing.

## 🎯 Objectives
1. **Enhanced Understanding of Sales Dynamics**: Analyze sales trends and identify key performance drivers across various regions, products, and sales methods.
2. **Geographic Sales Potential:** Detect regions with high and low sales potential to enable strategic regional focus and resource allocation.
3. **Product Performance Insights:** Evaluate product-specific performance metrics to inform inventory management and marketing strategies.
4. **Informed Pricing and Margin Strategies:** Develop data-backed pricing strategies and optimize operating margins for improved profitability.
5. **Actionable Recommendations:** Provide clear, data-driven recommendations to optimize sales and profitability across multiple business dimensions.
   
## 📋 Data Description
### Metrics
- Total Sales: Total revenue generated from product sales.
- Operating Profit: Profit calculated as the difference between Total Sales and operating expenses.
- Units Sold: Total number of product units sold.
- Price per Unit: Selling price of each product unit.
- Operating Margin: The ratio of Operating Profit to Total Sales, indicating profitability.

### Dimensions
- Retailer: Name of the retailer responsible for the transaction.
- Product: Name and category of the product sold (e.g., Men's Footwear, Women's Apparel).
- Region: Geographic region of the transaction (e.g., Northeast, Midwest).
- State: U.S. state where the transaction occurred.
- City: City where the transaction took place.
- Invoice Date: Date of the sales transaction.
- Sales Method: Sales channel used (e.g., In-store, Online).
This breakdown of metrics and dimensions provides a structured approach for analyzing sales trends and profitability while supporting strategic business decisions.

<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/dashboard.png", width="" height="">
</p>

# Business Insights Overview
## Sales Trend by Regions
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Region.png", width="" height="">
</p>

- **Sales in the West region lead the pack with an impressive $269.94 million,** significantly outpacing other regions. Following closely is the Northeast region, with $186.32 million, reflecting strong urban consumer activity. Meanwhile, the Southeast and South regions also contribute robust figures of $163.17 million and $144.66 million, respectively, highlighting steady sales performance in these areas. However, **the Midwest region lags behind, generating $135.80 million,** signaling opportunities for targeted growth strategies.
- 
## Sales Trend by Products
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Product.png", width="" height="">
</p>

- The sales data reveals **Men's Street Footwear as the undisputed leader, with a commanding total of $208.83 million.** This category demonstrates the strong appeal of versatile and stylish options among male consumers, making it a cornerstone of Adidas' revenue.
- Trailing closely behind, Women's Apparel secures the second spot with $179.04 million in sales. This indicates the growing popularity of Adidas' clothing line among women, likely driven by a blend of comfort, style, and activewear trends.
- Men's Athletic Footwear takes the third position with $153.67 million, underscoring the enduring demand for performance-oriented footwear among male athletes and fitness enthusiasts. Meanwhile, Women's Street Footwear follows at $128.00 million, showcasing its significant role in the casual and lifestyle segment.
- **Further down the list,** Men's Apparel brings in $123.73 million, reflecting steady engagement with Adidas' clothing offerings for men. At the same time, **Women's Athletic Footwear rounds out the rankings with $106.63 million,** emphasizing the potential for further growth in this segment through targeted marketing and innovative designs.

## Sales Trend by Retailers
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Retailer.png", width="" height="">
</p>

- **West Gear takes the lead as Adidas’ most significant retail partner,** generating a remarkable **$243M in sales**. This highlights the retailer's robust market presence and successful strategies, including well-targeted customer engagement and effective promotions.
- Foot Locker follows with impressive sales of $220M, leveraging its specialization in athletic footwear and benefiting from Adidas’ popular sneaker lines. Sports Direct, with $182M in sales, demonstrates strong performance across diverse product categories, further cementing its position as a crucial contributor.
- Kohl’s, while notable at $102M in sales, lags significantly behind the top three, likely focusing on casual or discounted product lines. Meanwhile, Amazon ($78M) and Walmart ($75M) show underperformance in online and mass retail channels, suggesting limited product availability or less aggressive marketing efforts in these segments.

## Sales Trend by Channel
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Channels.png", width="" height="">
</p>

- **The in-store** method leads as the most significant sales channel **($356.64M)**, accounting for the highest share of revenue. This reflects the continued strength of physical retail in driving sales, likely supported by direct customer engagement, personalized shopping experiences, and product trial opportunities.
- Outlets contribute substantially to revenue ($295.59M), serving as an effective channel for moving inventory and catering to price-sensitive customers. Their proximity to in-store sales highlights their strategic importance in Adidas’ overall sales ecosystem.
- While online sales rank third ($247.67M), they represent a significant opportunity for growth. As digital transformation continues, this channel can be further optimized to capture market share through enhanced user experiences, targeted advertising, and streamlined logistics.

 ## Average Operating Margin
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Operating%20Margin.png", width="" height="">
</p>

- The average operating margin for Adidas stands at 42.30%, showcasing a solid profitability level across its operations. However, a closer look at regional performance reveals notable disparities.

## Average Operating Margin by Region
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/OM%20w%20Region.png", width="" height="">
</p>

- **The South region leads the charge with the highest operating margin of 46.69%,** demonstrating exceptional cost efficiency and profitability. This success could stem from optimized supply chains or strong sales of high-margin products in the region.
- The Midwest region follows with a robust margin of 43.53%, reflecting a steady balance between revenue generation and operational efficiency. Meanwhile, the Southeast region achieves an operating margin of 41.92%, slightly above the company average, indicating its strong contribution to overall profitability.
- In contrast, the Northeast region, with a margin of 41.05%, and **the West region, at 39.67%, lag behind.** The West region’s performance, in particular, suggests opportunities to revisit pricing strategies or cost management practices to boost profitability.

## Key Observations from the Correlation Analysis
<p align="center">
  <img src="https://github.com/Sopyaan/Adidas-Sales-Analysis/blob/main/images/Corelation.png", width="" height="">
</p>

### Total Sales and Operating Profit
- A strong positive correlation (0.96) indicates that higher total sales strongly drive operating profit. This suggests that scaling sales effectively boosts profitability.
Total Sales and Units Sold:
- A high positive correlation (0.91) highlights that sales volume is a major contributor to total sales. Maintaining competitive pricing and optimizing product distribution can amplify this trend.
### Price per Unit and Operating Margin
- A negative correlation (-0.14) suggests that higher prices per unit do not necessarily improve operating margins, possibly due to increased costs or reduced demand for premium-priced products.
Operating Margin and Total Sales:
- A negative correlation (-0.36) implies that regions or products with higher sales volumes might sacrifice margin, potentially due to discounts or operational inefficiencies.
Operating Profit and Units Sold:
- A positive correlation (0.89) indicates that higher unit sales positively impact operating profit, reaffirming the importance of driving volume sales to enhance profitability.

