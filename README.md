# Trip_cost_calculator_Python
This Python program helps users calculate the total estimated cost of a trip by breaking down expenses into key categories: hotel, flight, car rental, and additional spending money. The program utilizes a modular design, with separate functions for calculating each cost component. 

# Features
Modular Design: Separate functions are used for each calculation to improve readability and maintainability.
User Input: The program prompts the user for necessary details such as destination city, number of nights, flight cost, etc.
Total Cost Summary: A final function aggregates all costs and displays the grand total for the trip. 

# Functions
The program uses the following functions:

1.hotel_cost(nights): Calculates the total hotel cost based on the number of nights.
2.plane_cost(city): Calculates the flight cost based on the destination city.
3.car_rental_cost(days): Calculates the car rental cost based on the number of rental days.
4.spending_money(money): A simple function to incorporate additional spending money.
5.trip_cost(city, days, spending): The main function that calls the others, sums the total cost, and displays the results. 
