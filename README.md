# Assignment_ShopifyTask_1
## Variable Declarations: -
You start by declaring variables to store references to HTML elements such as product prices, shipping charges, total cart amount, and a discount code input field.

## decreaseNumber Function:
This function is called when the user clicks to decrease the quantity of a product. It does the following:

It checks if the current quantity is not already at 0; otherwise, it shows an alert to prevent negative quantities.
If the quantity is greater than 0, it decreases the quantity by 1 and updates the item's price, the product total amount, and the total cart amount.

## increaseNumber Function:
This function is called when the user clicks to increase the quantity of a product. It does the following:

It checks if the current quantity is not already at the maximum value of 8; otherwise, it shows an alert to limit the quantity to a maximum of 8.
If the quantity is less than 8, it increases the quantity by 1 and updates the item's price, the product total amount, and the total cart amount.
discount_code Function: This function is called when the user attempts to apply a discount code. It does the following:

It checks if the entered discount code matches the code "ASHISH." If it does, it subtracts $20 from the total cart amount as a discount and displays
a success message. Otherwise, it displays an error message.
## Reasoning: 
Your code is written in JavaScript, which is commonly used for client-side interactions in web applications.
It's a suitable choice for handling user interactions like updating quantities and applying discounts.
You're also using plain HTML for the user interface elements.

# Shopping Cart JavaScript

## Introduction

This JavaScript code provides the functionality for a simple shopping cart on a web page. Users can adjust the quantity of items in the cart, apply a discount code, and see the updated total amount.

## Code Structure

- `product_total_amt`: Variable to display the product's total amount.
- `shipping_charge`: Variable to display the shipping charges.
- `total_cart_amt`: Variable to display the total cart amount.
- `discountCode`: Variable to store the discount code input element.

### `decreaseNumber(incdec, itemprice)`

This function is used to decrease the quantity of a product in the cart:

- Checks if the current quantity is not 0 (prevents negative quantities).
- Decreases the quantity by 1 and updates the item's price, product total amount, and the total cart amount.

### `increaseNumber(incdec, itemprice)`

This function is used to increase the quantity of a product in the cart:

- Checks if the current quantity is less than the maximum value of 8 (limits the quantity to 8).
- Increases the quantity by 1 and updates the item's price, product total amount, and the total cart amount.

### `discount_code()`

This function is used to apply a discount code:

- Checks if the entered discount code matches "ASHISH."
- If matched, subtracts $20 from the total cart amount and displays a success message.
- If not matched, displays an error message.

## Usage

You can integrate this JavaScript code into your e-commerce website to provide a shopping cart functionality. Make sure to have the necessary HTML elements with the specified IDs to connect with the code.

To adjust the behavior or styling, you can customize the JavaScript functions and associated HTML elements as needed.

## Contributing

Contributions to improve and enhance this code are welcome! Feel free to fork the repository, make changes, and submit pull requests.

For more information or support, visit([https://yourwebsite.com](https://kaleidoscopic-genie-204b91.netlify.app)).
# Shopping Cart JavaScript

## Introduction

This JavaScript code provides the functionality for a simple shopping cart on a web page. Users can adjust the quantity of items in the cart, apply a discount code, and see the updated total amount.

## Code Structure

- `product_total_amt`: Variable to display the product's total amount.
- `shipping_charge`: Variable to display the shipping charges.
- `total_cart_amt`: Variable to display the total cart amount.
- `discountCode`: Variable to store the discount code input element.

### `decreaseNumber(incdec, itemprice)`

This function is used to decrease the quantity of a product in the cart:

- Checks if the current quantity is not 0 (prevents negative quantities).
- Decreases the quantity by 1 and updates the item's price, product total amount, and the total cart amount.

### `increaseNumber(incdec, itemprice)`

This function is used to increase the quantity of a product in the cart:

- Checks if the current quantity is less than the maximum value of 8 (limits the quantity to 8).
- Increases the quantity by 1 and updates the item's price, product total amount, and the total cart amount.

### `discount_code()`

This function is used to apply a discount code:

- Checks if the entered discount code matches "ASHISH."
- If matched, subtracts $20 from the total cart amount and displays a success message.
- If not matched, displays an error message.

## Usage

You can integrate this JavaScript code into your e-commerce website to provide a shopping cart functionality. Make sure to have the necessary HTML elements with the specified IDs to connect with the code.

To adjust the behavior or styling, you can customize the JavaScript functions and associated HTML elements as needed.

## Contributing

Contributions to improve and enhance this code are welcome! Feel free to fork the repository, make changes, and submit pull requests.



---

For more information or support, visit [Your Website URL](https://kaleidoscopic-genie-204b91.netlify.app).
