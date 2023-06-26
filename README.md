# To-Do List Application

This is a simple web-based to-do list application that allows users to add tasks, mark them as completed, and delete them. It provides a user-friendly interface for managing and organizing tasks effectively.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To use the to-do list application, follow these steps:

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. You will see the to-do list application interface.
4. Enter a task in the input box and click the "Add" button to add it to the list.
5. Click on a task to mark it as completed.
6. Click on the "X" button next to a task to delete it from the list.
7. The application automatically saves your tasks using local storage, so your data will persist even if you refresh the page.

## Files

- `index.html`: This file contains the structure and layout of the to-do list application interface. It includes the necessary HTML elements and references to the CSS and JavaScript files.
- `script.js`: This file contains the JavaScript code for adding, marking, and deleting tasks. It also includes functions for saving and retrieving data using local storage.
- `styles.css`: This file contains the CSS styles for the to-do list application, including the layout, colors, and visual elements.

## Customization

You can customize the application by modifying the CSS styles in the `styles.css` file. Feel free to update the colors, fonts, dimensions, and other design elements to match your preferences.

For example, to apply bold and a smaller font size to the to-do list title, you can modify the following CSS rule:

```css
.todo-app h2 {
  font-size: 20px;
  font-weight: bold;
}
