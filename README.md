# Currency-Converter

This is a web-based currency converter application built using HTML, CSS, and JavaScript. It allows users to convert between different currencies using live exchange rates fetched from a public API.

🔧 Features
Convert any amount from one currency to another

Automatically fetches real-time exchange rates

Country flags update dynamically based on selected currency

Stylish, responsive UI using plain CSS

Default selection: USD to INR (can be changed)

📁 Project Structure
JS-Project.html – The main HTML file containing the layout and UI structure.

JS-Project.css – Stylesheet that beautifies the UI and ensures responsiveness.

JS-Project.js – Contains logic for:

Populating currency dropdowns

Fetching exchange rates

Updating country flags

Currency-Codes.js – A static JS object mapping currency codes (like INR, USD) to their respective country codes (like IN, US), used for displaying correct flags.

README.md – This documentation file.

🌐 API Used
Exchange rate data is fetched from:
📡 https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api

🧠 How It Works
When the page loads, the dropdowns are filled with all available currency codes.

The default conversion is set from USD to INR.

When the user changes currency or amount and clicks "Get Exchange Rate", the app:

Sends a request to the API for the current rate.

Calculates the converted amount.

Displays the result in a user-friendly format.

Corresponding national flags are shown beside the currency dropdowns using flagsapi.com.

🖼️ Demo Screenshot
(You can include a screenshot here of your app in action)

🚀 How to Run
Download or clone the repository.

Open JS-Project.html in a web browser.

Start converting currencies!

