 Chocolate-House-management-system

Welcome to the Chocolate House Management Application! This is a simple Python application designed to help manage a fictional chocolate house’s seasonal flavor offerings, ingredient inventory, and customer flavor suggestions, including allergy concerns. The application uses SQLite for.

Features

- Manage seasonal flavor offerings:
  - Add new seasonal flavors with availability.
  - View current seasonal flavors.

- Manage ingredient inventory:
  - Add new ingredients with their quantities.
  - View current ingredients in stock.

- Manage customer flavor suggestions:
  - Add customer suggestions for new flavors, including allergy concerns.
  - View all customer suggestions.
 
  Requirements

- Python 3.x
- SQLite (included with Python)

How to Use

1. After running the application, you will see a menu with options to manage seasonal flavors, ingredients, and customer suggestions.

2. Follow the prompts to:
   - Add seasonal flavors by entering the flavor name and availability period.
   - View all seasonal flavors saved in the database.
   - Add ingredients by entering the ingredient name and its quantity.
   - View the current inventory of ingredients.
   - Submit customer flavor suggestions with any allergy concerns.
   - View all customer suggestions recorded in the database.

3. Select the option to exit the application when done.

SQLite Database

The application uses an SQLite database (`chocolate_house.db`) to store the following tables:

- **SeasonalFlavors**: Stores the id, name, and availability rating of seasonal chocolate flavors.
- **Ingredients**: Stores the id, name, and quantity of ingredients available.
- **CustomerSuggestions**: Stores the id, flavor suggestion, and any allergy concerns shared by customers.
