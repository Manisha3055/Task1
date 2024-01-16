# Task1
STEP 1: 
Product and Discount Rules:
 Create Product Dictionary of product name A, B, C with it's prices.

STEP 2:
Discount Rule Functions:
Define functions for calculating each discount amount: A dictionary that defines the discount rules, where the keys are the rule names, and the values are the corresponding discount percentages or amounts.

STEP 3:
User Input and Cart Calculations: This function takes two parameters (cart and discounts) and calculates the discount to be applied based on the discount rules. It returns an object containing the applied discount name and amount.
Prompt for quantity and gift wrap choice for each product: This function takes the cart as a parameter and calculates the shipping fee and gift wrap fee based on the total quantity of items in the cart. It returns an object containing the calculated shipping fee and gift wrap fee.
Then start writting main program:
1.Input Section
2.Cart Initialization
3.User Input Loop
4.Subtotal Calculation:  Calculated Sum of each product cost
5.Discount Calculation: Calculated potential discounts
6.Shipping and Gift Wrap Calculation: Calculated Shipping Fee based on the total number of units
and calculate Gift Wrap Fee based on the number of units selected for gift wrap
7.Total Calculation:Calculated total using below formula
Formula: const total = subtotal - bestDiscount + shippingFee + giftWrapFee;

