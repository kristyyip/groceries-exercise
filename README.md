# groceries-exercise (python)

An exercise in building a Python application, completed for class.

## Prerequisites
    + Anaconda 3.7
    + Python 3.7

# Installation

An introductory Python application (a starter game of rock-paper-scissors), for instructional purposes.

## Prerequisites

  + Anaconda 3.7
  + Python 3.7
  + Pip

## Repo Setup

Using GitHub.com, access your "Repositories" tab to create a new private repositiory. Name this repository "groceries-exercise". Make sure to check off "Initialize this repository with a README" and select "Add .gitignore: Python" before completing the process. Once finished, you should be able to access your repository on Github at https://github.com/YOUR_USERNAME/groceries-exercise.

In your repository on GitHub.com, press "Clone or download" to open the repository in GitHub Desktop. After, press "Open in Visual Studio Code" or in another such external editor. Create a file called "groceries.py" and place the following inside.

    # groceries.py

    #from pprint import pprint

    products = [
        {"id":1, "name": "Chocolate Sandwich Cookies", "department": "snacks", "aisle": "cookies cakes", "price": 3.50},
        {"id":2, "name": "All-Seasons Salt", "department": "pantry", "aisle": "spices seasonings", "price": 4.99},
        {"id":3, "name": "Robust Golden Unsweetened Oolong Tea", "department": "beverages", "aisle": "tea", "price": 2.49},
        {"id":4, "name": "Smart Ones Classic Favorites Mini Rigatoni With Vodka Cream Sauce", "department": "frozen", "aisle": "frozen meals", "price": 6.99},
        {"id":5, "name": "Green Chile Anytime Sauce", "department": "pantry", "aisle": "marinades meat preparation", "price": 7.99},
        {"id":6, "name": "Dry Nose Oil", "department": "personal care", "aisle": "cold flu allergy", "price": 21.99},
        {"id":7, "name": "Pure Coconut Water With Orange", "department": "beverages", "aisle": "juice nectars", "price": 3.50},
        {"id":8, "name": "Cut Russet Potatoes Steam N' Mash", "department": "frozen", "aisle": "frozen produce", "price": 4.25},
        {"id":9, "name": "Light Strawberry Blueberry Yogurt", "department": "dairy eggs", "aisle": "yogurt", "price": 6.50},
        {"id":10, "name": "Sparkling Orange Juice & Prickly Pear Beverage", "department": "beverages", "aisle": "water seltzer sparkling water", "price": 2.99},
        {"id":11, "name": "Peach Mango Juice", "department": "beverages", "aisle": "refrigerated", "price": 1.99},
        {"id":12, "name": "Chocolate Fudge Layer Cake", "department": "frozen", "aisle": "frozen dessert", "price": 18.50},
        {"id":13, "name": "Saline Nasal Mist", "department": "personal care", "aisle": "cold flu allergy", "price": 16.00},
        {"id":14, "name": "Fresh Scent Dishwasher Cleaner", "department": "household", "aisle": "dish detergents", "price": 4.99},
        {"id":15, "name": "Overnight Diapers Size 6", "department": "babies", "aisle": "diapers wipes", "price": 25.50},
        {"id":16, "name": "Mint Chocolate Flavored Syrup", "department": "snacks", "aisle": "ice cream toppings", "price": 4.50},
        {"id":17, "name": "Rendered Duck Fat", "department": "meat seafood", "aisle": "poultry counter", "price": 9.99},
        {"id":18, "name": "Pizza for One Suprema Frozen Pizza", "department": "frozen", "aisle": "frozen pizza", "price": 12.50},
        {"id":19, "name": "Gluten Free Quinoa Three Cheese & Mushroom Blend", "department": "dry goods pasta", "aisle": "grains rice dried goods", "price": 3.99},
        {"id":20, "name": "Pomegranate Cranberry & Aloe Vera Enrich Drink", "department": "beverages", "aisle": "juice nectars", "price": 4.25}
    ] # based on data from Instacart: https://www.instacart.com/datasets/grocery-shopping-2017

    print(products)
    # pprint(products)

    # TODO: write some Python code here to produce the desired output

After editing, save the Python file so that we can proceed to our virtual environment setup.

## Environment Setup

In your command-line, create and activate a new Anaconda virtual environment by entering the following:
   
    conda create -n groceries-env python=3.7 # (first time only)
    conda activate groceries-env

This will activate your virtual environment. Then, you can run the Python script by entering:

    python groceries.py

If you see the contents that we placed in groceries.py during the Repo Setup, then you're ready to proceed. Make your first commit to master in GitHub Desktop, naming it "Setup the repo".