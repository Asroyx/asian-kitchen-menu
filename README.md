# Food Menu Application

This application creates a food menu that displays dishes from different countries along with their prices. Users can filter the menu by country category and view the details of the respective dishes.

## Technologies Used

- HTML
- CSS
- JavaScript

## How It Works

1. An array called `menu` contains objects that hold information about the dishes.
2. An array called `buttons` contains the country categories and filter buttons.
3. In the HTML file, a container and an output area are defined to display the filter buttons and the dishes.
4. The `showMenuItems` function filters the dishes based on the selected category and writes the results to the screen by calling the `displayMenuItems` function.
5. Click event listeners are added to the relevant filter buttons, and the `showMenuItems` function is called with the correct category.
6. On page load, all dishes are displayed using the `showMenuItems` function.

## Installation

1. Clone or download this project.
2. Navigate to the downloaded directory and open the `index.html` file in a browser.

## Screenshots

![Food Menu Application](screenshot.png)

This README.md file provides basic information on how to use and run the food menu application. If the project has additional documentation or dependencies, reference can be made to those documents as well.
