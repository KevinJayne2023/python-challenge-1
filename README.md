# python-challenge-1
Kevin's Food Truck Ordering System

Overview
This Python program simulates an ordering system for Kevin's food truck. Customers can select items from various menus (snacks, meals, drinks, and desserts) and place orders with specific quantities. The program calculates the total cost of the order and presents it to the customer.

Menu Structure
The menu variable contains a nested dictionary representing the food truck's menu structure. Each menu category (e.g., Snacks, Meals, Drinks, Dessert) contains items with their respective prices. Some menu items have further subcategories, such as Pizza flavors or Drink sizes.

Order Management
Order List: The orders list stores dictionaries for each ordered item, including the item name, price, and quantity ordered.

Ordering Process: The program guides customers through selecting items by displaying menu categories and respective items. Customers input item numbers and quantities for ordering.

Validation: Input validation ensures that customer inputs are valid menu options and quantities.

Order Confirmation: Customers can continue ordering or finalize their order. The program calculates the total cost of the order.

Usage
Launching: Upon execution, the program greets customers and starts the ordering process.

Order Selection: Customers choose menu categories and specific items by entering corresponding numbers.

Quantity Input: Customers input quantities for each item ordered.

Order Finalization: Customers can continue ordering or complete their order. The program calculates the total cost.

Order Summary
After completing the order, the program displays the items ordered along with their prices and quantities. It calculates the total cost of the order and presents it to the customer.