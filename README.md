# Temperature Dashboard Web Application

## Description
A simple, professional single-page web application that displays the current temperature and allows users to refresh the data manually. The interface includes a heading, temperature display, and a refresh button styled with Bootstrap. The app simulates fetching real-time temperature data with a randomized value.

## Features
- Displays a static heading: "Temperature Dashboard"
- Shows current temperature (initially "25°C")
- Provides a "Refresh" button below the temperature
- Clicking the button updates the temperature with a simulated new value
- Uses modern ES6+ JavaScript syntax
- Fully responsive and styled with Bootstrap for a clean appearance
- Gracefully handles errors during data fetch simulation

## How to Use
1. Save the provided code in a file named `index.html`.
2. Open `index.html` in your web browser.
3. Click the "Refresh" button to generate a new random temperature.

## Code Structure Explanation
- **HTML**: Defines the structure with semantic tags, includes Bootstrap CSS for styling, and a custom style block.
- **CSS**: Adds basic custom styles for layout and appearance.
- **JavaScript**:
  - Contains an async function `fetchTemperature()` that simulates fetching temperature data.
  - Handles error scenarios gracefully.
  - Registers an event listener on the "Refresh" button to trigger data updates.
  - Initializes syntax highlighter (optional, since no code blocks are present but included for completeness).
  
## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap CDN for styling
- Highlight.js CDN for syntax highlighting (prepared for future code blocks)
```