# Stocktaking-program

## Description
Program to aid in managing a warehouse and stocktaking. Allows users to view all products in a store and add more as well as update the quantities. 
This program can be extended to manage the stock of any product as a simple way to keep track of inventory on a small scale.

## Table of Contents
1. Installation
1. Usage
1. Credits

## Installation
The code can be copied into any code editor.
Comments are available in the code to explain what each section does.

The user would also need the text file inventory.txt in the same directory as the code in order to access it as the program runs.

## Usage
As the program starts the user will be provided with the following menu from where they can choose to view different sections of the program.

![menu](https://user-images.githubusercontent.com/125367266/226479230-1dad860f-7a84-4121-b22c-99d2f8d49ad9.JPG)

This gives the user access to:
* Add new shoes.
    * The user is prompted to add the Country, Code, Type of product, Cost and Quantity of the shoes being added.
    * The shoe object will then be added to the class and the .txt file.
    
![add shoes](https://user-images.githubusercontent.com/125367266/226479296-7617c295-c667-4784-b1c0-813fabe108b8.JPG)

* View all shoes registered.
   * All shoes in the .txt file is printed out in the terminal in an easy-to-read table.

![view all](https://user-images.githubusercontent.com/125367266/226479411-ae1ebc53-6450-4684-8dd2-c87a4226095a.JPG)

* Mark a shoe as restocked with amounts.
   * The shoe object with the lowest quantity is found.
   * The user is asked if they want to restock this shoe, if not they are redirected to the main menu.
   * If the user chose to update the quantity, they are asked for the quantity that needs to be added to it.

![restock](https://user-images.githubusercontent.com/125367266/226479458-25eb8b6a-e837-41cb-a9a7-14923c23c3af.JPG)

* Search for a shoe.
    * The user is asked for the code from the shoe object they want to view.
    * If the code is found the shoe information is printed out.
    * If the code is not found the user is redirected to the main menu to try again.
    
![search](https://user-images.githubusercontent.com/125367266/226479505-fab39dac-4d9d-464c-b343-5a704d3d34a4.JPG)

* View the total monetary value of all the shoes in the system.
    * Calculation is done to multiply the cost with the quantity to obtain the total value for each shoe.
    * This information is then printed to the terminal for each shoe.

![value](https://user-images.githubusercontent.com/125367266/226479526-e888a747-f48e-47b9-a988-3649ee683a26.JPG)

* View the shoes with the highest quantity for sale purposes.
    * Shoes with the highest quantity is found.
    * User is asked if they want to place the shoes on sale.
    * If the user selects yes, a conformation message is printed out which can be further extended.
    
![high](https://user-images.githubusercontent.com/125367266/226479554-b73f17f1-7471-4fb2-bbce-7a6a3ed8501d.JPG)

## Credits
This project was created by Christopher Barnard (ChrisTheFish96).
