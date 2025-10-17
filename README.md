# Sales Summary App

A simple single-page web application that reads sales data from a CSV file (`data.csv`) and displays the total sales amount.

## Features

*   Reads data from a `data.csv` file.
*   Calculates the sum of the 'sales' column.
*   Displays the total sales amount on the page.
*   Uses Bootstrap 5 for basic styling.

## Usage

1.  Ensure that the `index.html` and `data.csv` files are in the same directory.
2.  Open `index.html` in a web browser.
3.  The total sales amount will be displayed on the page.

## Data Format

The `data.csv` file should be formatted as follows:

```csv
product,sales
Laptop,899.99
Mouse,24.50
Keyboard,65.00
Monitor,199.99
```

The first row should be the header row, with columns named 'product' and 'sales'. Subsequent rows should contain the product name and its corresponding sales amount, separated by a comma.

## Dependencies

*   Bootstrap 5 (via CDN)

## Implementation Details

The application uses JavaScript to:

1.  Fetch the `data.csv` file.
2.  Parse the CSV data.
3.  Calculate the sum of the 'sales' column, skipping the header row and handling potential errors.
4.  Update the content of the `div` element with the ID `total-sales` to display the total sales amount.
