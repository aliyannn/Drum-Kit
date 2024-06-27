# Drum Kit Website
This project is a simple drum kit webpage where users can play different drum sounds by clicking on buttons or pressing specific keys on their keyboard. The project uses HTML, CSS, and JavaScript to create an interactive and visually appealing drum kit

# HTML
The HTML file (index.html) sets up the basic structure of the webpage.
* The head section includes metadata, the page title, links to the CSS stylesheet, and a Google Font.
* The body section contains the main content: the main title of the website and a set of buttons.
* Each button is assigned a class corresponding to a drum sound (e.g., w, a, s, etc.).
* The script tag includes the JavaScript file (index.js).
  
# CSS
* The CSS file (styles.css) styles the webpage.
* The body selector centers text and sets the background color.
* The h1 selector styles the main title with a font, size, color, and text-shadow.
* Each button class (w, a, s, etc.) sets a background image for the button.
* The drum class styles the buttons with border, font, color, size, and other properties.
* Additional classes (game-over, pressed, red) provide specific styles for different states.
* Custom scrollbar styling is also included.

# JavaScript
* The JavaScript file (index.js) adds interactivity to the webpage.
* The script detects button clicks and keyboard presses to play corresponding drum sounds.
* document.querySelectorAll(".drum").forEach adds event listeners to all buttons with the class drum.
* The addEventListener("click", function () {...}) callback function calls makeSound and buttonAnimation functions when a button is clicked.
* document.addEventListener("keydown", function (event) {...}) adds an event listener to detect key presses and calls makeSound and buttonAnimation.
* The makeSound function plays a specific sound based on the key pressed or button clicked.
* The buttonAnimation function adds a visual effect to the button when pressed, removing it after a short delay.

# How to Run
* Clone the repository.
* Open index.html in a web browser.
* Click the buttons or press the corresponding keys (w, a, s, d, j, k, l) to play the drum sounds.

Feel free to modify and enhance this project. Enjoy making music with your Drum Kit!
