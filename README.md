# Point of Sale Terminal using Java Swing

 
This is a simple Point of Sale Terminal application developed using Java Swing. The application allows users to add products, calculate the total amount, and generate a receipt as pdf.

All the receipts are generated are unique and no database is used , receipts can be stored in the local memory.

As the project is developed using NetBeans IDE it generates a JAR file which has all the required libraries and images of the JFrame Form, So only the POS.jar is executable and the POS.java file requires some NetBeans libraries, In order to use the application run the JAR file using the command given below.

# Features
 - Add products to the cart
 - Calculate cost based on purchase quantity
 - Calculate GST during the checkout
 - Generation of bill receipt & payment
 - The final bill has shop name with address in the header and customer details with points earned in the footer

# Prerequisites
Java Development Kit (JDK) version 8 or later

# Installation
Clone the repository:

```
git clone https://github.com/Suresh-23723/Point-of-Sale-Terminal.git
```
Navigate to the dist folder in the repository in the terminal

Run the application:

```
java -jar "POS.jar"
```
# Usage
 Usage is completely on the cashier side.

- Add products to the cart by selecting them from the list of available products and clicking the item.

- View the list of added products in the cart.

- To Remove any Item from the cart. Click Remove button and select the item you want to remove.

- Select payment mode in the payment section.

- If Cash is selected enter the amount received from the customer.

- If Credit Card is selected enter the amount displayed in the total.

- Click the pay button.

- Enter the Customer Name and contact number in order generate the receipt.

- Click the print button.

- Select the printer or pdf generator.

- For the next usage click the reset button.

- To exit, Click the Exit button.
