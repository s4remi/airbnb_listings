# airbnb_listings
# AirBNB Listings Project

This project is a simple web application that displays AirBNB listings. It consists of HTML, CSS, and JavaScript files. Below, you'll find a brief overview of the project's structure and functionality.

## Project Structure

The project consists of the following files:

- `index.html`: This is the main HTML file that displays the web page content.
- `styles.css`: This CSS file contains styles for the web page, including formatting for listings.
- `main.js`: The JavaScript file that controls the dynamic rendering of AirBNB listings on the page.
- `airbnb_sf_listings_500.json`: A JSON file containing data for AirBNB listings.

## HTML (`index.html`)

- The HTML file sets up the basic structure of the web page and includes links to external resources.
- It uses the Bootstrap framework for styling and responsiveness.
- The page includes a navigation bar, a header section, and a section for displaying AirBNB listings.
- The listing section is initially empty and will be populated dynamically using JavaScript.

## CSS (`styles.css`)

- The CSS file defines styles for AirBNB listing cards.
- It includes styles for images, card bodies, prices, host information, and more.
- The CSS file also adds hover effects to the listing cards for a visually appealing user experience.

## JavaScript (`main.js`)

- The JavaScript file defines a `MainModule` function that controls the dynamic rendering of listings.
- It fetches data from the `airbnb_sf_listings_500.json` file, which contains information about AirBNB listings.
- The `getListingCode` function generates HTML code for each listing using the provided data.
- The `redraw` function updates the web page with the generated listing HTML.
- The `loadData` function fetches and loads the data, then triggers the rendering of the initial listings.

## Getting Started

To run this project locally, follow these steps:

1. Clone or download the project repository.
2. Open the `index.html` file in a web browser to view the AirBNB listings.

Feel free to customize the project, add more listings, or enhance the functionality to suit your needs. Enjoy exploring AirBNB listings with this simple web application!
