# README.md

## Project Overview

This project is a simple HTML table styled with CSS to display product orders, including details like date, order ID, product name, price, quantity, and total. The table is designed to be responsive and visually appealing, with a gradient background, alternating row colors, and hover effects.

## Files Included

- **index.html**: The HTML file that contains the structure of the table.
- **style.css**: The CSS file that provides styling for the table and overall page layout.

## Features

1. **Responsive Layout**: The page uses a flexbox layout to ensure the table is centered horizontally on the screen and adjusts for various screen sizes.
2. **Gradient Background**: The background of the page is a gradient transitioning from purple to pink, creating a visually attractive look.
3. **Styled Table**:
   - Table rows have alternating background colors for better readability.
   - Hover effects highlight each row for improved user interaction.
   - Padding is applied to each table cell for better spacing.
   - Rounded corners and box shadow for the table container to enhance aesthetics.
4. **Scrollable Container**: The table container has a fixed maximum height, allowing a scroll bar for better viewing of large data sets without expanding the page vertically.

## CSS Breakdown

- **Body Styling**: The body has a gradient background, flexbox layout, and padding for visual alignment.
- **Table Container**: The `.table-container` class is used to create a container for the table with a maximum height and box shadow to add emphasis.
- **Table Styling**:
  - The `table` element uses `border-collapse` for a clean appearance.
  - The `thead` has a dark background color and white text for contrast.
  - Alternating row colors (`nth-of-type(even)` and `nth-of-type(odd)`) are used to improve readability.
  - The column for "Quantity" is aligned to the left for consistency.
  - Hover effects for rows enhance user experience.

## How to Run

1. **Clone the repository** or download the HTML and CSS files.
2. Open `index.html` in your preferred web browser.

## Customization

- **Background Colors**: You can modify the background gradient in the `body` style within `style.css` to suit your preferences.
- **Table Row Colors**: The alternating row colors can be adjusted by modifying the `nth-of-type` CSS selectors for rows.
- **Container Height**: To increase or decrease the height of the table container, adjust the `max-height` property of the `.table-container` class.

## Future Enhancements

- **JavaScript Interactivity**: Adding JavaScript functionality to sort the table columns or perform searches would make this project more dynamic.
- **Responsive Design Improvements**: Use media queries for further responsive optimizations on smaller devices.

## Author
This project was created by Thien Ha. Feel free to contribute or suggest improvements!