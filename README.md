# Food-Recipe-Book---Sritesh-Suranjan

Food Recipe Book Webpage

This HTML, CSS, and JavaScript code represents a Food Recipe Book webpage. Here's a breakdown of the key components:

HTML Structure:
- Head Section: Includes metadata like character set, viewport settings, and the title of the webpage. It also links an external stylesheet.
- Body Section: Contains the main content of the webpage.

Page Components:
1. Header:
   - Displays the title "Food Recipe Book - Sritesh Suranjan."

2. Container:
   - Contains an unordered list (`recipe-list`) of recipe items.

3. Recipe Items:
   - Each recipe item (`recipe-item`) includes an image, recipe title, list of ingredients, and a link to view the recipe.

CSS (style.css):
- Defines the styling for various elements.
- Utilizes a dark theme with a consistent color scheme.
- Implements responsive design using media queries for different screen sizes.

JavaScript (index.js):
- Fetches recipe data from the Spoonacular API using an API key.
- Dynamically creates HTML elements for each recipe and appends them to the `recipe-list`.
- The `displayRecipes` function is responsible for rendering recipes.
- The `getRecipes` function fetches recipes from the Spoonacular API.
- The `init` function initializes the webpage by fetching and displaying recipes.

This repository contains the code for a Food Recipe Book webpage. It dynamically fetches recipes from the Spoonacular API and displays them in a visually appealing format. Each recipe item includes an image, title, ingredients, and a link to view the full recipe. The dark theme and responsive design enhance the user experience. Explore the code to customize and integrate this recipe book into your web projects.
