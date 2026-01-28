# Price Analysis Project

## Problem Statement
The goal of this project is to figure out which products can have their prices increased without losing a lot of customers. Many stores guess when they change prices, but this project uses data to make better decisions.

## How we are solving the problem
We looked at sales data from a big supermarket chain (Big Mart). We grouped products into 16 categories like "Seafood," "Breads," and "Soft Drinks." 

For each group, we calculated something called "price elasticity." This is just a way to measure how much people change their buying habits when prices go up or down.
- If a product is "inelastic," it means people will likely keep buying it even if the price goes up a bit.
- If a product is "elastic," it means people are very sensitive to the price and might stop buying if it gets too expensive.

## Results
- We analyzed 16 different types of products.
- We found that 4 categories (25%) are good candidates for price increases.
- The best opportunities for price increases are in **Seafood**, **Breads**, and **Soft Drinks**.
- By increasing prices by just 5% in these top categories, the store could potentially earn an extra **Rs 156,744.80**.

## Limitations
- **Other Factors**: Our model only looks at prices. In real life, things like advertising, the time of year (holidays), and what competitors are doing also affect sales.
- **Data Quality**: The results depend on the data we have. If the data has errors, the results might not be 100% accurate.
- **Customer Behavior**: Some customers might react differently in different locations or at different times than what our data shows.

## Files In This Project
- `Price Analysis.ipynb`: The main file where we did all the calculations and data work.
- `app.py`: A simple web application to show the results.
- `Train (2).csv`: The raw sales data we used.
- `requirements.txt`: A list of tools needed to run the code.
