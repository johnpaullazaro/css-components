# NightDev's Card Contribution to STUDEV

## HTML Figure Component Overview

This card is using figure so it can easily edited by anyone 

The figure has 2 components which is the image and the figcaption

- img : where the image locate
- figcaption : where the info of the card


## CSS Figure Component Overview

The following CSS code defines styles for a versatile figure component commonly used for displaying images with optional captions. Here's a concise breakdown of the key styles:

### Figure Styles:
- display: grid; : Utilizes CSS Grid for layout.
- overflow: hidden; : Conceals content exceeding the figure's boundaries.
- cursor: pointer; : Changes cursor to a pointer on hover.

### Image Styles:
- width: 350px; height: 500px; : Sets fixed dimensions.

### Figcaption Styles:
- display: grid; align-items: end; : Aligns figcaption content to the bottom.
- font: bold 1.3rem sans-serif; : Sets caption font style.
- color: #ffffff; : Defines text color.
- padding: 0.75rem; : Adds padding to figcaption.
- background: var(--c, rgba(19, 18, 18, 0.808)); : Sets background color with fallback.
- clip-path: inset(0 var(--_i, 100%) 0 0); : Creates a diagonal clipping path.
- Various -webkit-mask properties for additional styling.
- margin: -1px; : Removes default margins.

### Hover Effects:
- figure:hover figcaption: Adjusts figcaption on hover.
- figure:hover img: Scales the image on hover.

### Body Styles:
- margin: 0; : Removes default body margins.
- min-height: 100vh; : Ensures a minimum viewport height.
- display: grid; grid-auto-flow: column; place-content: center; : Uses grid layout for centering.
- background: #425a52; : Sets the background color.