# Rotating Navigation
This is a rotating navigation menu example that demonstrates a circular navigation interface. When the user clicks on the circular menu, it rotates and reveals a hidden navigation menu with options. The menu can be opened or closed by clicking the buttons inside the circle.

## Live site:
https://silviasaverino.github.io/Rotating-Navigation/

### Animation Logic
The animation is implemented using CSS transforms and JavaScript. When the user clicks the circular menu, it adds the "show-nav" class to the container, which triggers the rotation animation defined in the CSS. The buttons inside the circle have event listeners attached to them, so when they are clicked, the "show-nav" class is added or removed from the container, resulting in the opening or closing of the navigation menu.

### HTML Structure: 
The HTML structure consists of a container with a circle container and content section. The circle container contains buttons for opening and closing the navigation. The content section includes headings, paragraphs, and an image.

### CSS Styling: 
The CSS styling defines the visual appearance of the web page. It sets the background color, font family, and colors for various elements. The container is styled to have a rotating effect when the navigation is opened, achieved through the transform and transition properties. The navigation menu is fixed at the bottom of the page.

### Navigation Menu: 
The navigation menu is represented by an unordered list with three list items . Each list item contains an icon from Font Awesome and a corresponding text link. The navigation menu has a sliding-in animation when the container is in the "show-nav" state.

### JavaScript Functionality: 
The JavaScript code at the end of the HTML file handles the interaction with the navigation buttons. When the "open" button is clicked, the container element is given the "show-nav" class, triggering the rotating effect and sliding-in animation. Clicking the "close" button removes the "show-nav" class, reversing the effects and closing the navigation.

