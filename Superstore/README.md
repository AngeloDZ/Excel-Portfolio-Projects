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

Let's start our analysis with looking at the best and worst performing products that Superstore produces.

The graph above shows the top ten products with the highest profit. We can clearly see that the 'Canon imageCLASS 2200 Advanced Copier' is the most profitable product by a large margin, with a total profit of $25,199.93.

Conversely, the graph above shows the 10 least profitable products. The 'Cubify CubeX 3D Printer Double Head Print' is by far the least profitable product, with a net profit of -$8,879.97.

### Profit by Sub-Category

Now, let's have a look at the profits by a sub-category basis. The following graph shows each sub-category and their respective profits.

We can see thet Tables are by far the worst sub-category, with a total net loss of $17,725.48. Bookcases and Supplies are the other two sub-categories producing a net loss, with a total loss of $3,472.56 and $1,189.10 respectively.

Let's also check the profit margins for each sub-category. The following pivot table shows the sub-categories that have less than 5% of profit, assuming 5% is the minimum target.

As we can see, Tables, Bookcases and Supplies each have a negative profit margin of -8.56%, -3.02% and -2.55% respectively, which follows relatively in line with the profits graph.

Interestingly, Machines have only produced a profit margin of 1.79%. This is likely due to the cost of goods for Machines in particular being the most expensive out of all other sub-categories, as well as having the second highest average discount.


## Regional analysis

## Segment analysis

## Other insights

## Recommendations

## Dashboard
