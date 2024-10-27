# ISM-3232-Coding-Challenge-11
Coding Challenge: Order Management System - Event Handling in JavaScript
Introduction:
In this challenge, you will create a simple Order Management System for a business that tracks and manages product orders. You will use JavaScript to handle events such as selecting products, updating order quantities, and calculating total prices in real-time. The challenge focuses on event handling and dynamic UI updates in a business context.

Business Case:
Scenario: A small business sells different products online. The business wants to create a system that allows customers to: - Select a product from a dropdown list. - Enter the quantity of the selected product. - Calculate the total price based on the product and quantity. - Display an order summary when the customer places the order.

Tasks:
1. Setup HTML Structure for Order Form Create an HTML page that includes the following elements:

A dropdown to select a product (e.g., “Product A - $10”, “Product B - $15”).
An input field to enter the quantity.
A paragraph to display the total price.
A button to place the order and display a summary.
Commit: Setup basic HTML structure for order form

2. Add Event Listener for Product Selection 

Create a JavaScript file that listens for changes in the product dropdown. When a product is selected, update the price display based on the selected product and quantity entered by the user.

Commit: Add event listener for product selection and quantity input

3. Calculate Total Price Dynamically 

Add functionality to dynamically calculate the total price when the user selects a product and enters a quantity. The total price should be updated in real-time.

Commit: Calculate and update total price dynamically based on product and quantity

4. Handle Order Submission Add an event listener to the order button. 

When the order is placed, display an order summary with the selected product, quantity, and total price.

Commit: Handle order submission and display order summary

Hints:

Event Handling: Use addEventListener() to handle changes in product selection and quantity input, and to manage the order submission.

Input Validation: Ensure the quantity entered is a valid number (greater than 0). If not, display an error message or prevent the order from being submitted.

Dynamic Updates: Ensure the total price updates automatically whenever the product or quantity is changed by the user.