# Case Study: Superstore Dataset - Profitablity Analysis

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

## Segment analysis

## Other insights

## Recommendations

## Dashboard
