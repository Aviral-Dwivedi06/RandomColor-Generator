# RandomColor-Generator
# Random Color Generator

This project is a dynamic Random Color Generator built using HTML, CSS, and JavaScript. It generates a new random hexadecimal color code each time the user clicks a button, instantly updating the background color of the webpage and displaying the generated color code in real-time.

---

## Features

- Generates fully valid 6-digit hexadecimal color codes using JavaScript.
- Dynamically changes the background color of the entire page on button click.
- Displays the generated color code on screen using DOM manipulation.
- Utilizes Google Fonts to enhance the visual appearance and typography.
- Includes smooth CSS transitions for background color changes.
- Fully responsive layout using Flexbox, with clean and minimal design.

---

## Technologies Used

- HTML: Structure of the webpage, including containers and content elements.
- CSS: Styling, layout, spacing, colors, and smooth transitions.
- JavaScript: Logic for generating random color codes and interacting with the DOM.
- Google Fonts: Integrated custom fonts (Playwrite VN Guides) for improved typography.

---

## How It Works

1. A random number between 0 and 16777215 (maximum value for 24-bit color) is generated.
2. This number is converted into a hexadecimal string using `.toString(16)`.
3. The resulting string is prefixed with `#` to form a valid hex color (e.g., `#4f3b2a`).
4. The background color of the page is finally updated using DOM manipulation.
   

