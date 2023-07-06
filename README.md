# Canteen System

The Canteen System is a command-line application built using Python that automates the canteen operations to make the life of canteen staff easier and services faster. It allows the canteen staff to manage the snack inventory and keep track of sales.

## Functionalities

The Canteen System provides the following functionalities:

1. **Display Snacks**: The application allows the canteen staff to view the snack inventory, including the snack ID, name, price, availability, and quantity.

2. **Add Snack**: Canteen staff can add new snacks to the inventory by providing the snack ID, name, price, availability (yes or no), and quantity.

3. **Remove Snack**: Canteen staff can remove snacks from the inventory by providing the snack ID.

4. **Update Snack Availability**: Canteen staff can update the availability of a snack by providing the snack ID and specifying whether it is available (yes) or not (no).

5. **Sell Snack**: Canteen staff can sell snacks by providing the snack ID and the quantity. The application checks the availability and quantity before updating the inventory and recording the sale.

6. **Exit**: The application allows the user to exit the system.

## Usage

## To use the Canteen System, follow these steps:

1. Clone the repository to your local machine.
Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 1

| ID | Snack Name | Price | Availability | Quantity |
|----|------------|-------|--------------|----------|
| 1  | Chocolate  | 1.5   | yes          | 10       |
| 2  | Chips      | 1.0   | yes          | 20       |

Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 2
Enter the snack ID: 3
Enter the snack name: Candy
Enter the price: 0.5
Is the snack available? (yes/no): yes
Enter the quantity: 15

--------------------------------------
Snack added to the inventory.
--------------------------------------

Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 1

| ID | Snack Name | Price | Availability | Quantity |
|----|------------|-------|--------------|----------|
| 1  | Chocolate  | 1.5   | yes          | 10       |
| 2  | Chips      | 1.0   | yes          | 20       |
| 3  | Candy      | 0.5   | yes          | 15       |

Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 5
Enter the snack ID to sell: 1

--------------------------------------
Snack sold.
--------------------------------------

Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 1

| ID | Snack Name | Price | Availability | Quantity |
|----|------------|-------|--------------|----------|
| 2  | Chips      | 1.0   | yes          | 20       |
| 3  | Candy      | 0.5   | yes          | 15       |

Welcome to the Canteen System!
1. Display Snacks
2. Add Snack
3. Remove Snack
4. Update Snack Availability
5. Sell Snack
6. Exit
Enter your choice (1-6): 6

--------------------------------------
Thank you for using the Canteen System.
--------------------------------------
