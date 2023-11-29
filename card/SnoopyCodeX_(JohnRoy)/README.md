# SnoopyCodeX's Card Contribution to STUDEV PH

## HTML Component Overview

This card is using divs as movie card in which anyone could edit the component to their liking

The card only has 3 components to edit

- img : The url of the cover photo
- h1 : The title of the card
- p : The description of the card

## CSS Overview

The following CSS code defines styles for the div

# root styles
- `padding: 0px;` removes the default padding in the root
- `margin: 0px;` removes the default margin in the root
- `font-family: sans-serif;` sets the default font family to `sans-serif`

# body styles
- `display: flex;` sets the body's display into `flex`
- `justify-content: center;` horizontally aligns the body's items to the center
- `align-items: center;` vertically aligns the body's items to the center
- `height: 100vh;` sets the height of the body to 100 viewport height
- `background: whitesmoke;` sets the body's background color to `whitesmoke` or `#f5f5f5f5`

# container styles
- `display: flex;` sets the container's display into `flex`

# Card styles
- Styles for the card container. The `overflow: hidden;` in the `.movie-card .movie-intro` ensures that it is hidden and not overflowing the main card body.

- Added `transition: .5s;` or a transition delay of `0.5 seconds` or `500 milliseconds` to the intro and image component of the card. This will make the sliding animation of the movie's description smooth and the scaling of the image smooth.