<img width="113" height="21" alt="image" src="https://github.com/user-attachments/assets/adb74304-cafc-4837-9cc3-4abab8a0eca9" /># Case Study: Superstore Dataset - Profitablity Analysis

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

### Profit by Sub-Category

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

Interestingly, Machines have only produced a profit margin of 1.79%, and while it is still positive, it is still very low. This is likely due to the cost of goods for Machines in particular being the most expensive out of all other sub-categories combined with having the second highest average discount.

## Regional analysis

### Profits by Region

This bar graph shows the all time profit made across all products in each region. The West region is the most profitable area, having a total profit of $108,418.45. It is then followed closely by East, which has an impressive sum of $91,522.78. The South and Central regions have quite lower total profits than the first two regions, producing total profits of $46,749.43 and $39,706.36 respectively.

Above is a line graph consisting of the trends of profits for each region over the years.

With West being the most dominant region for profits, it is no surprise to see that it is consistently performs well each year. In fact it increases steadily up until 2017, with a massive jump in profits up to a total of $43,808.96.

East follows in a similar fashion. Despite a short dip in profits in 2016, it generates almost as much profits as West, including a similar jump in profits in 2017.

The South region seems to have the most unique trend out of all the regions. Between 2014 and 2016, the profits fluctuate quite a bit, but unlike West and East, there is a major drop in profits in 2017.

The least profitable region of all time, Central, started off very weak, with only a total profit of $539.55 for the whole of 2014. Interestingly, profits in that region grew practically linearly between the 2014 and 2016 region. In fact, for 2016, profits in Central came to $19,899.16, nearly matching East, which obtained  $20,141.60 for the same year. However, in 2017 it experienced the largest drop in profits seen ever for any region, dropping to $7,550.84, the lowest for any region that year.

(WHY RISE/DROP IN 2017?)
### Profits by Region and Category

The graph above shows the all time relationship of the total profits with respect to the Regions and Categories. The column graph clearly shows that that Furniture have by far the worst profits, being the only section that has resulted in a negative total profit. The total net loss in this section is $2,871.05. In fact, it seems that Furniture is all round less profitable than Office Supplies and Technology in all regions by quite a large margin.

## Segment analysis

### Profits by Segment

<p align="center">
<img width="2332" height="1206" alt="Profits by segment" src="https://github.com/user-attachments/assets/36bebfcd-b0dc-4d1b-877e-1687b3cd8ae2" />
</p>

The graph above provides the total profits earned by each Segment for all time sales.

Consumer is the dominant Segment, having produced  $134,119.21 over the course of the 4 years. Corporate has the second most profit earned, with a total of $91,979.13 earned, while Home Office has only produced a total profit of $60,298.68.

What is interesting, though, is that despite the rankings in pure sum of profits, the profit margins tell a slightly different story.


## Other insights

## Recommendations

## Dashboard
