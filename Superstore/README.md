# Superstore Dataset - Profitablity Analysis

## Objective

To analyse key drivers of profits for the company, identify financially weak areas and provide insights.

Data taken from Kaggle: www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Data Cleaning
- Spelling checks (None found) - Not correcting customer or product names.
- Check for duplicates. (None found)
- Check for missing values (TO DO)
- Converting dates from American (MDY) to UK (DMY). (Text to Columns)

## Product analysis

### Most and least profitable products

This analysis will begin with looking at the best and worst performing products that Superstore produces.

<p align="center">
<img width="1000" alt="Best products" src="https://github.com/user-attachments/assets/a8da29f9-7c7e-4b60-af57-cfce71c78ba6" />
</p>
  
The graph above shows the top ten products with the highest profit. It shows us that the 'Canon imageCLASS 2200 Advanced Copier' is the most profitable product by a large margin, with a total profit of $25,199.93, indicating a mix of high demand and optimal pricing.

<p align="center">
<img width="1000" height="1928" alt="Worst Products" src="https://github.com/user-attachments/assets/106c3d34-6ae1-4656-b012-1863c7649cb5" />
</p>

Conversely, the graph above shows the 10 least profitable products. The 'Cubify CubeX 3D Printer Double Head Print' is by far the least profitable product, with a net profit of -$8,879.97.

### Profits by Sub-Category

Now, let's have a look at the profits by a sub-category basis. The following graph shows each sub-category and their respective profits.

<p align="center">
<img width="1000" alt="Profits by category" src="https://github.com/user-attachments/assets/3076b4ea-01c8-4ffa-9b25-9e50bf2d403d" />
</p>

This graph shows us that Tables are by far the worst sub-category, with a total net loss of $17,725.48. Bookcases and Supplies are the other two sub-categories producing a net loss, with a total loss of $3,472.56 and $1,189.10 respectively.

Fasteners can be seen with having a low profit margin, but the reason for this is that they are by far the cheapest type of product, thus the total sales and profits are expected to be low.

### Worst Profit Margins by Sub-Category

Let's also check the profit margins for the worst sub-categories. The following chart represents the profit margins of sub-categories that have earned less than 5% of profit.

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/f1e5d5e6-bba4-494f-a84e-e200e737bcb3" />
</p>

The data shows that Tables, Bookcases and Supplies each have a negative profit margin of -8.56%, -3.02% and -2.55% respectively, which follows relatively in line with the graph of the total profits.

Interestingly, Machines have only produced a profit margin of 1.79%, and while it is still positive, it is still very low. This is likely due to the cost of goods for Machines in particular being the most expensive out of all other sub-categories combined with having the second highest average discount.

### Trends for worst performing sub-categories

<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/5e4e3340-c0a9-4927-8327-7f71b922bc78" />
</p>

### Implications

## Regional analysis

### Profits by Region

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/fd4e7e6a-67c6-422a-a01e-5da85f6a6fa5" />
</p>

This bar graph shows the all time profit made across all products in each region. The West region is the most profitable area, having a total profit of $108,418.45. It is then followed closely by East, which has an impressive sum of $91,522.78. The South and Central regions have quite lower total profits than the first two regions, producing total profits of $46,749.43 and $39,706.36 respectively.

### Profit Margins by Region

<p align="center">
<img width="700" alt="image" src="https://github.com/user-attachments/assets/2ff02f79-98a7-4542-b0c2-a74615ce21b7" />
</p>

This graph shows the profit margins for each region. As we can see, it is almost identical to the total profits accumulated by each region. The West region is again at the top, with a profit margin of 14.94%, followed by East with 13.48%, South with 11.93%, and then Central with the lowest at just 7.92%.

From these results, we can clearly see that West is the highest performing region in terms of both total profit and profit margin, while Central is the least profitable and least efficient region.

A strong reason for these results seem to come from the pricing strategies that have been implemented in each region.

### Discount of products by Region

The below graph provides us with the percentage of revenue that has been discounted from products in each region.

<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/380492bd-7502-4724-9e92-f2c2dab34057" />
</p>

Central has a revenue-weighted discount of roughly 24.56% for products sold in this region, the highest out of any region, while the rest have generally lower discounts, and in partiuclar West has the least at only 15.55%. These findings strongly correlate with the results seen when analysing the total profits and profit margins.

In fact, we can compare the profit margin with the revenue-weighted discount in a scatter graph.

<p align="center">
<img width="700" src="https://github.com/user-attachments/assets/30a3ac46-ebfc-4d3d-be2e-f32d3b9dcc00" />
</p>

The graph presents a clear trend, showing a directly inverse relationship between the revenue-weighted discount and the profit margin. We should aim to apply this to the pricing strategies for each region where necessary.

### Implications

It is clear to see that Central could benefit well from lowering discounts on products, similar to the pricing strategies amongst the other regions. Central already has a solid amount of sales, so reducing discounts amongst products could lead to a much healthier profit margin, as well as an increase in total profit.

East and West are healthy in many aspects including quantity of sales, total profit and profit margin. Focusing on sales in these regions would be highly recommended, as they seem to be much more efficient for profits than the other regions.

Despite the South region having fairly low total profit, the following graph puts into perspective the quanity of sales made in each region.

<p align="center">
<img width="800" height="591" alt="image" src="https://github.com/user-attachments/assets/6e3926c6-82ce-4e71-81d5-7fc11b061bef" />
</p>

South has the lowest total quantity of sales. In fact it has roughly half the sales in West, but have managed to generate more total profits than Central while maintaining a respectable profit margin. A good idea would be to experiment with pushing more sales in the South region if possible, as it could yield more profits. Additionally, seeing as it has the second highest revenue-weighted discount, we could aim to lower discounts in this region too. However, adjusting prices could affect the total sales and orders, so it would be best to experiment and test for optimal discount rates.

## Segment analysis

### Total Profits by Segment

<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/6cfe6d5a-427c-4811-ae41-6caf5394f192" />
</p>

The graph above provides the total profits earned by each Segment over the four year period.

The Consumer segment is the dominant contributor to profits, having produced $134,119.21 over the course of the 4 years. Corporate has the second most profit earned, having achieved a total of $91,979.13, while Home Office has only produced a total profit of $60,298.68.

### Profit Margins by Segment

What is interesting, though, is that despite the rankings in pure sum of profits, the profit margins show a different pattern.

<p align="center">
<img width="800" alt="Segment profit margin graph" src="https://github.com/user-attachments/assets/868fe649-6cf7-4601-9073-b64e50087a9b" />
</p>

As we can see in the above chart, the profit margins generated by each segment rank in reverse order. Home Office managed to achieve the highest profit margin of 14.03%, followed by Corporate with 13.03%, and leaving Consumer with the lowest, yet respectable, profit margin of 11.55%.

### Implications

These findings suggest that the Consumer segment should remain as the highest priority as it generates the large majority of total profits. It would be advisable to review and reduce discounts for products in this segment, as the low profit margin indicates an inefficient profit per sale, at least in comparison to the other segments.

The Home Office segment, which has achieved the highest profit margin, shows a very promising opportunity for growth. Pushing for higher sales volume could very well lead to high total profits while maintaining a healthy profit margin.

## Recommendations

### Products

### Region

### Segment

## Dashboard
