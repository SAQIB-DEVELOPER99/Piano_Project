# Piano Project

This project creates a piano keyboard using HTML and CSS. The page includes a piano with white and black keys, and a logo.

## Project Structure
- `index.html`: Contains the HTML structure of the piano.
- `styles.css`: Contains the CSS styles for the piano.

## HTML Structure
The HTML file includes the following elements:
- `div#piano`: The main container for the piano, which includes:
  - `img.logo`: The logo image.
  - `div.keys`: The container for the piano keys, which includes:
    - `div.key`: The white keys.
    - `div.key.black--key`: The black keys.

## CSS Styles
The CSS file includes styles for the following elements:
- `html`: Sets the box-sizing property.
- `*`, `*::before`, `*::after`: Resets box-sizing.
- `body`: Styles for centering the piano and setting the background.
- `#piano`: Styles for the piano container, including background color, size, margin, padding, position, and border-radius.
- `.keys`: Styles for the keys container, including background color, size, padding, and overflow.
- `.key`: Styles for the white keys, including background color, size, margin, position, and border-radius.
- `.key.black--key::after`: Styles for the black keys, including background color, size, position, and border-radius.
- `.logo`: Styles for the logo image, including size and position.
- `@media (max-width: 768px)`: Media query to adjust styles for smaller screens.

## How to Run
1. Clone the repository or download the project files.
2. Open `index.html` in your web browser to view the piano.


