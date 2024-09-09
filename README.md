# FinalSprint-Sem1-SC

## Overview
This project is a simple web application that reads and displays a game inventory from a JSON file using basic JavaScript functionalities. It showcases how to fetch data from a JSON file, process it, and dynamically display the inventory of games on a webpage. Additionally, it calculates the total profit based on the difference between the market value and the price paid for each item.

## Features
- Fetch and display game inventory items from `gameinventory.json`.
- Dynamically create HTML elements to display each game’s details (e.g., item name, category, console type, quantity, price, market value, condition).
- Calculate and display the profit for each game, as well as the total profit.
- Logs game data to the console for debugging and development purposes.

## Technologies Used
- **HTML**: For structuring the webpage.
- **JavaScript**: For fetching data from the JSON file, performing calculations, and manipulating the DOM to display the inventory.
- **JSON**: Used to store the game inventory data.

## How It Works
1. The `datareader.js` script fetches the `gameinventory.json` file, which contains the list of games and their details.
2. The script then processes each game, extracting and displaying details such as:
   - Item Name
   - Item Category
   - Console Type
   - Quantity
   - Price Paid
   - Market Value
   - Condition
   - Profit (calculated as `market value - price paid`)
3. The total profit from all games is also calculated and displayed at the bottom of the page.
4. The processed data is both displayed on the webpage and logged to the console for debugging.

## Repository Structure
- **index.html**: The main HTML file that serves as the entry point for the application.
- **datareader.js**: The JavaScript file responsible for fetching and processing the `gameinventory.json` file, calculating profits, and dynamically updating the DOM.
- **gameinventory.json**: The JSON file containing the game inventory details (not included in this README, but assumed to be present in the project directory).

## Running the Project
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FinalSprint-Sem1-SC.git
   ```
2. Open index.html in your preferred web browser.
3. Ensure that gameinventory.json is in the same directory as datareader.js.
4. The game inventory will be fetched and displayed automatically on the webpage, with profits calculated and shown at the bottom.

## Author
- **Stephen Crocker**
- Date: April 4, 2024

## License
This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. You are free to view and share this project for educational purposes but may not modify or use it for commercial purposes without permission.

### Usage Policy
This repository contains coursework completed as part of an academic program. Unauthorized use of this material, including copying or submitting it for academic credit, is strictly prohibited. The author is not responsible for any misuse of this content, and any legal repercussions that may arise from such actions are the sole responsibility of the individual using the material inappropriately.

For more information, please refer to the [Creative Commons CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

