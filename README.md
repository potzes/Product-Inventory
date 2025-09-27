# Product-Inventory

A CLI program built using C language that allows user to add, search, and track products in their inventory.

## Main Features

**Add product** - This allows the user to add new product in their inventory which prompts the user to enter the product informations such as name, price, and stock.

**View inventory** - This function displays all of the products added in the inventory with complete information of each product.

**Search product** - This allows the user to search an existing product within their inventory through the product's name. If the product is found, it will display the product's information.

**Edit product** - This function can only be used after a successful product search. User will have an option to exit or edit the product information.

**Save and load inventory** - Integration of file handling for inventory saving purposes. All of the product in the inventory inputted by the user will be saved to the designated file of the current inventory automatically before exiting the program. This allows user to retrieve the saved inventory including its products when reopening the program.

**Error handling** - Displays an error if the memory failed in a certain operations for easier troubleshooting.

## How to use

  This program is currently pure CLI program which runs only on terminal after compiling. The main interface of this program includes the program's function with their corresponding number(1 - 4). Those number are used for user to navigate the program by inputing the corresponding number of the feature they want to use. However, number 4 is used for exiting or stopping the program.

## Future improvements

**Deletion of product** - Allowing user to remove a certain product from the inventory.

**PIN encryption** - Providing privacy and security of the inventory access.

**Flexible product search** - Allowing user to search products without minding the capitalizations of the product name.

**Sorting of inventory** - Allowing user to sort the inventory view base on product name, price, or stock for a better visualization.

**Transition to GUI** - Integration of GUI for a better navigation and UI/UX.
