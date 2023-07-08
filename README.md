# Meals_And_Dishes_REST_API

## API:
This project implenets a RESTful API for meals.
- It invokes a RESTful API.
- It provides a RESTful API.
- It uses Docker containers to package the application.

The RESTful API allows users to:
- Create and store dishes.
  A dish will be given by its name. Then, the program will invoke a the REST API http://api.apininjas.com/v1/nutrition to compute the following information for that dish:
  1. The number of calories.
  2. The serving size (in grams).
  3. The amount of sodium (in mg).
  4. The amount of sugar (in grams).
- Create and store meals by specifying the 3 dishes that comprise that meal (appetizer, main*, dessert).
- Retrieve, update, and delete dishes and meals.

## Docker:
- The application can run in a Docker container.


