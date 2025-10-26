# 🛋️ Lovely Loveseats Receipt Generator

This project was completed as part of a Codecademy Python course for a fictional furniture company called **Lovely Loveseats**. The goal was to build a simple receipt system to speed up the checkout process for customers.

## 📚 Project Summary

Using foundational Python programming skills, I created a system that:

- Stores a catalog of furniture items with descriptions and prices
- Tracks customer purchases and calculates totals
- Applies sales tax to the final bill
- Prints a formatted receipt with item details and total cost

## 🧠 How It Works

1. **Catalog Setup**  
   I created variables to store information about the furniture catalog, including item descriptions and prices.

2. **Customer Purchase Tracking**  
   - `customer_one_total`: Initialized at `0`, this variable increases with each purchase using the `+=` operator.
   - `customer_one_itemization`: Starts as an empty string and accumulates item descriptions as purchases are made.

3. **Tax Calculation**  
   - A `sales_tax` variable is set to `0.088`.
   - Tax is calculated using basic arithmetic and added to the total cost.

4. **Receipt Printing**  
   - The `print()` function displays the item descriptions and total cost.
   - The total is formatted to two decimal places using `"{:.2f}".format()` for currency display.

## 🧾 Sample Output
