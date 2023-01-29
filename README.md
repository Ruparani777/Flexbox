# Flexbox

Flexbox is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.

To use it, give an element a display property of flex. This will make the element a flex container. Any direct children of a flex container are called flex items.

eg: 
gallery{
  display: flex;
}
lexbox has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:

row (default): horizontal axis with flex items from left to right
row-reverse: horizontal axis with flex items from right to left
column: vertical axis with flex items from top to bottom
column-reverse: vertical axis with flex items from bottom to top
Note: The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.

he flex-wrap property determines how your flex items behave when the flex container is too small. Setting it to wrap will allow the items to wrap to the next row or column. nowrap (default) will prevent your items from wrapping and shrink them if needed.

Make it so your flex items wrap to the next row when they run out of space.

gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap; ///shrink 
}

The justify-content property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.eg: center ,left etc.
gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}

The gap CSS shorthand property sets the gaps, also knowns as gutters, between rows and columns. The gap property and its row-gap and column-gap sub-properties provide this functionality for flex, grid, and multi-column layout. You apply the property to the container element.


object-fit: cover
he ::after pseudo-element creates an element that is the last child of the selected element. 
