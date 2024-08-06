# Calculator
HTML Structure
<html> and <head>:

Declares the document as HTML5 and sets meta information including charset and viewport settings.
Includes a <title> tag for the page title.
Contains a <style> block to define CSS styles.
<body>:

Central element of the document where the calculator interface is defined.
Calculator Container
<div class="calculator">:
The main container for the calculator.
Styled with a border, rounded corners, shadow effect, fixed width, and background color.
Display
<div class="display" id="display">:
Displays the input and output of the calculator.
Styled with a height, dark background, white text color, right-aligned text, and padding.
The font size is set to be large for clear visibility.
Buttons
<div class="buttons">:

Container for all the calculator buttons arranged in a grid layout with four columns.
<button class="button">:

Defines individual calculator buttons.
Buttons are styled with padding, font size, background color, and hover effects.
Transition effects are added for smooth color changes on hover and active states.
Special Buttons:

Operator Buttons: Styled with a distinct color for easy identification.
Equal Button: Styled to span two columns and with a green background.
Clear Button: Styled with a red background to indicate its function.
JavaScript Functionality
appendToDisplay(value):

Appends the clicked button value to the calculator display.
clearDisplay():

Clears the display.
deleteLast():

Deletes the last character in the display.
calculateResult():

Evaluates the expression in the display and shows the result.
Uses eval function to compute the result and includes error handling to display "Error" if the input is invalid.
CSS Styling
General Styles:

Centers the content on the page both horizontally and vertically.
Sets a light gray background for a clean look.
Uses the 'Roboto' font for modern and clean typography.
Calculator Container:

Uses a border, rounded corners, and shadow effects for a polished appearance.
Display:

Dark background with white text for contrast.
Right-aligned text with large font size for readability.
Buttons:

Arranged in a grid for a clean layout.
Different background colors and hover effects for normal, operator, equal, and clear buttons.
Transition effects for smooth background color changes.
This document provides a user-friendly and visually appealing calculator interface that includes basic arithmetic functionalities and responsive design elements.
