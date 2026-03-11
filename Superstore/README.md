# Superstore Dataset - Profitablity Analysis

## Objective

To analyse key drivers of profits for the company, identify financially weak areas and provide insights.

Data taken from Kaggle: www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Data Cleaning
- Spelling checks (None found) - Not correcting customer or product names.
- Check for duplicates. (None found)
- Check for missing values (TO DO)
- Converting dates from American (MDY) to UK (DMY). (Text to Columns)

## Introductory Questions

Let's answer some standard questions to provide some context to the dataset.

### What is the all time profit margin achieved by the company?

From the data we can work out the the total profit is $286,397.02, and the total sales is $2,297,200.86 for the 2014 to 2017 period.

This gives us a 12.47% (2 d.p.) profit margin.

### Which products have the highest quantity of sales?

### What are the most profitable products?

## Product analysis

### Most and least profitable products

This analysis will begin with looking at the best and worst performing products that Superstore produces.

<p align="center">
<img width="3742" height="2066" alt="Best products" src="https://github.com/user-attachments/assets/a8da29f9-7c7e-4b60-af57-cfce71c78ba6" />
</p>
  
The graph above shows the top ten products with the highest profit. It shows us that the 'Canon imageCLASS 2200 Advanced Copier' is the most profitable product by a large margin, with a total profit of $25,199.93, indicating a mix of high demand and optimal pricing.

<p align="center">
<img width="3743" height="1928" alt="Worst Products" src="https://github.com/user-attachments/assets/106c3d34-6ae1-4656-b012-1863c7649cb5" />
</p>

Conversely, the graph above shows the 10 least profitable products. The 'Cubify CubeX 3D Printer Double Head Print' is by far the least profitable product, with a net profit of -$8,879.97.

### Profits by Sub-Category

Now, let's have a look at the profits by a sub-category basis. The following graph shows each sub-category and their respective profits.

<p align="center">
<img width="3240" height="1581" alt="Profits by category" src="https://github.com/user-attachments/assets/3076b4ea-01c8-4ffa-9b25-9e50bf2d403d" />
</p>

This graph shows us that Tables are by far the worst sub-category, with a total net loss of $17,725.48. Bookcases and Supplies are the other two sub-categories producing a net loss, with a total loss of $3,472.56 and $1,189.10 respectively.

Let's also check the profit margins for each sub-category. The following pivot table shows the sub-categories that have less than 5% of profit, assuming 5% is the minimum target.

<p align="center">
<img width="794" height="223" alt="Worst Profit Margin" src="https://github.com/user-attachments/assets/825279d1-6c81-4a3f-9800-85674d0d97af" />
</p>

The data shows that Tables, Bookcases and Supplies each have a negative profit margin of -8.56%, -3.02% and -2.55% respectively, which follows relatively in line with the profits graph.

Interestingly, Machines have only produced a profit margin of 1.79%, and while it is still positive, it is still very low. This is likely due to the cost of goods for Machines in particular being the most expensive out of all other sub-categories combined with having the second highest average discount. Fasteners can be seen with a low profit margin, but this is understandable as they are cheaply made and are not designed for incredible profits like the other sub-categories.

### Trends for worst performing sub-categories



## Regional analysis

### Profits by Region

<p align="center">
<img width="853" height="541" alt="image" src="https://github.com/user-attachments/assets/fd4e7e6a-67c6-422a-a01e-5da85f6a6fa5" />
</p>

This bar graph shows the all time profit made across all products in each region. The West region is the most profitable area, having a total profit of $108,418.45. It is then followed closely by East, which has an impressive sum of $91,522.78. The South and Central regions have quite lower total profits than the first two regions, producing total profits of $46,749.43 and $39,706.36 respectively.

### Profit Margins by Region

<p align="center">
<img width="848" height="528" alt="image" src="https://github.com/user-attachments/assets/d2379e5c-cc4d-40d0-a5ef-75a5baf6280d" />
</p>

This graph shows the profit margins for each region. As we can see, it is almost identical to the total profits accumulated by each region. The West region is again at the top, with a profit margin of 14.94%, followed by East with 13.48%, South with 11.93%, and then Central with the lowest at just 7.92%.

### Implications

From these results, we can clearly see that West is the highest performing region in terms of both total profit and profit margin, while Central is the least profitable and least efficient region.

A strong reason for these results seem to come from the pricing strategies that have been implemented in each region. The below graph provides us with the average discount applied to a typical product in each region.

<p align="center">
<img width="982" height="581" alt="image" src="https://github.com/user-attachments/assets/24099263-dbd1-4b5d-b5fb-c5d09ef37bbf" />
</p>

Central has an average discount of roughly 24% for products sold in this region, the highest out of any region, while the rest have a much lower discount on average, and in partiuclar West has the least average discount at only 11%. These findings strongly correlate with the results seen when analysing the total profits and profit margins.

It is clear to see that Central could benefit well from lower rated discounts on products, similar to the pricing strategies amongst the other regions. Central already has a solid amount of sales, so reducing discounts amongst products could lead to a much healthier profit margin, as well as an increase in total profit.

East and West are healthy in many aspects including quantity of sales, total profit and profit margin. Focusing on sales in these regions would be recommended, as they seem to be much more efficient for profits than the other regions.

Despite the South region having fairly low total profit, the following graph puts into perspective the quanity of sales made in each region.

<img width="1054" height="591" alt="image" src="https://github.com/user-attachments/assets/6e3926c6-82ce-4e71-81d5-7fc11b061bef" />

South have the lowest total quantity of sales, in fact it has roughly half the sales in West, but have managed to generate more total profits than Central while maintaining a respectable profit margin. A good idea would be to experiment with pushing more sales in the South region if possible, as it could yield more profits without having to adjust pricing strategies.

## Segment analysis

### Total Profits by Segment

<p align="center">
<img width="2332" height="1206" alt="Profits by segment" src="https://github.com/user-attachments/assets/36bebfcd-b0dc-4d1b-877e-1687b3cd8ae2" />
</p>

The graph above provides the total profits earned by each Segment over the four year period.

The Consumer segment is the dominant contributor to profits, having produced $134,119.21 over the course of the 4 years. Corporate has the second most profit earned, having achieved a total of $91,979.13, while Home Office has only produced a total profit of $60,298.68.

### Profit Margins by Segment

What is interesting, though, is that despite the rankings in pure sum of profits, the profit margins show a different pattern.

<p align="center">
<img width="2441" height="1289" alt="Segment profit margin graph" src="https://github.com/user-attachments/assets/868fe649-6cf7-4601-9073-b64e50087a9b" />
</p>

As we can see in the above chart, the profit margins generated by each segment rank in reverse order. Home Office managed to achieve the highest profit margin of 14.03%, followed by Corporate with 13.03%, and leaving Consumer with the lowest, yet respectable, profit margin of 11.55%.

### Implications

These findings suggest that the Consumer segment should remain as the highest priority as it generates the large majority of total profits. It would be advisable to review and reduce discounts for products in this segment, as the low profit margin indicates an inefficient profit per sale, at least in comparison to the other segments.

The Home Office segment, which has achieved the highest profit margin, shows a very promising opportunity for growth. Pushing for higher sales volume could very well lead to high total profits while maintaining a healthy profit margin.

## Recommendations

## Dashboard
