# Pizza Order Calculator 🍕

This project is a technical assignment for an internship.

## Overview

The web application calculates a pizza order's total cost and allows for the review of submitted orders.

## Features

- **Order Creation**: Users can select the pizza size and toppings.
- **Cost Calculation**: The application displays the total order cost, with specific pricing rules.
- **Order Review**: Users can save their orders and view them on a separate page.

## Pricing Rules

- **Base Costs**: 
  - **Small**: €8
  - **Medium**: €10
  - **Large**: €12
- **Toppings**: 
  - Each topping costs $1. 
  - A discount of 10% is applied if more than 3 toppings are selected.

## Technical Stack

- **Backend**: ASP.NET Core with EF Core in-memory database.
- **Frontend**: React with the option of using libraries like Bootstrap or Material UI.
- **Logic**: All calculation logic resides in the backend.

## Optional Enhancements

- Unit tests in the backend.
- Web app deployment with a public URL access.

## Evaluation Criteria

1. Functionality of the web app (even if not 100% complete).
2. Quality and clarity of code.
3. Architecture decisions for backend and frontend.
4. Tools and libraries chosen.
5. Usage of design patterns.