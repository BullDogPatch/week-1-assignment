### I had to get this from ai

The flex: 1 1 45% shorthand property in Flexbox is a combination of three properties: flex-grow, flex-shrink, and flex-basis. Here's what each part means:

Breakdown:
1 (flex-grow): This is the growth factor. It determines how much the item will grow relative to the other items in the container. In this case, a value of 1 means the item will grow and take up any available space in the container (along with other items that have a grow factor of 1).

1 (flex-shrink): This is the shrink factor. It determines how much the item will shrink relative to the other items when there's not enough space in the container. A value of 1 means the item will shrink if necessary, but it will shrink proportionally with other items that have the same value.

45% (flex-basis): This is the initial size of the item before any growth or shrinking occurs. It defines the starting size of the element. In this case, it’s 45%, meaning each item (like your paragraph or image) will take up 45% of the available width within its container.

How It Works in Your Case:
When you use flex: 1 1 45%:

Each item (the paragraph and the image in your .info-section) will initially take up 45% of the container’s width (flex-basis of 45%).
If there’s extra space in the container, both items will grow equally (due to flex-grow: 1).
If there’s not enough space, both items will shrink proportionally (due to flex-shrink: 1).
The 45% is used so that both items (the paragraph and the image) can sit side-by-side, but they will be flexible if the screen size changes.

Example:
On a wide screen:

Both items will take 45% of the width initially, so there’s space for two items side-by-side.
If there’s extra space in the container (say the viewport is large), they will expand to fill that space evenly.
On a small screen:

The items will shrink to fit the available space, and they’ll wrap onto the next line because of flex-wrap: wrap;.
In summary, flex: 1 1 45% helps ensure the elements are flexible, and they adjust their size to fit the container while maintaining a good layout on both small and large screens.

#Todo
Create a back to the top button
un-comment the js to let the sound play
Finish reflection (put what resources)
