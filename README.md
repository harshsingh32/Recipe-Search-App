# Recipe Search App
This is a web application that allows users to search for healthy and nutritious food recipes using the Edamam's API. The app allows users to search for recipes based on specific ingredients, cuisine, meal type, and dietary restrictions. The app also provides information on the nutritional value of each recipe, including calorie count, macronutrient breakdown, and other key nutrients.


[🔗 Project](https://recipe-api-blush.vercel.app)

# Technologies Used
• React.js
• Bootstrap
• Edamam's APIReact
• npm
• vercel
• CSS module
• Git Workflow
• CSS
• Vercel



# Installation and Setup
To install and run this project on your local machine, follow the instructions for:

# Clone the GitHub repository:
git clone https://github.com/yourusername/recipe-search.git

Navigate to the project directory:
cd recipe-search

Install the required dependencies:
Create a .env file in the root directory of the project and add your Edamam API credentials as follows:
makefile
REACT_APP_EDAMAM_APP_ID=<your app id>
REACT_APP_EDAMAM_APP_KEY=<your app key>
Start the development server:
sql
npm start

# Features
The Recipe Search app includes the following features:

Search for recipes based on ingredients, cuisine, meal type, and dietary restrictions
View recipe details, including ingredients, instructions, and nutritional information
Save favorite recipes to a user's profile for easy access
Create a shopping list for ingredients needed for a recipe
View and edit user profile information

# API Usage
The Recipe Search app uses the Edamam API to retrieve recipe and nutrition data. The API requires an app id and app key, which are passed in as environment variables.

To search for recipes, the app makes a GET request to the Edamam recipe search endpoint with the user's search query and any optional parameters (cuisine, meal type, dietary restrictions). The response includes an array of recipes, each with its own unique identifier (URI).

When a user selects a recipe, the app makes a second GET request to the Edamam recipe endpoint with the recipe's URI to retrieve detailed recipe and nutrition data. The response includes the recipe's ingredients, instructions, and a detailed nutritional breakdown.

# Contributions

Contributions are welcome! Please create a pull request with any features or bug fixes.

# License
This project is licensed under the MIT License. See the LICENSE file for more information.
