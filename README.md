# Sales Summary Application

This is a single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display it prominently. The application is built with responsive design principles using Tailwind CSS and vanilla JavaScript.

## Features

*   **Data Fetching**: Automatically loads `data.csv` located in the same directory.
*   **Sales Calculation**: Parses the CSV to sum values from the 'sales' column.
*   **Dynamic Title**: Sets the page title to 'Sales Summary - Current Data' upon successful load.
*   **Responsive UI**: Utilizes Tailwind CSS for a clean and responsive user interface.
*   **Error Handling**: Displays an error message if the CSV data cannot be loaded or processed correctly.

## Setup and Usage

To run this application:

1.  **Save Files**: Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open `index.html`**: Simply open `index.html` in your web browser.

The application will automatically fetch `data.csv`, calculate the total sales, and update the display.

### `data.csv` Format

The `data.csv` file must include a header row with a column named `sales`. Example format:

```csv
item,sales,region
Product A,100.50,North
Product B,250.75,South
Product C,120.00,East
```

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For styling and responsiveness.
*   **Vanilla JavaScript**: For data fetching, parsing, and DOM manipulation.
