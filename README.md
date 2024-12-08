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

---

# Reflection

### 🎯What requirements did you achieve?

I think I have achieved all the requirements, even the stretch goals

🎯 Were there any requirements or goals that you were unable to achieve? no
It's not that I did not do anything, I found the CSS particulary tricky, especially positioning with absolute and relative, at first I had them the wrong way round and when my page was small screen the p tag over the image stayed where it was but it needed to move with image. However after a little bit of wrestling I found I had them on the wrong tags

🎯 If so, what was it that you found difficult about these tasks?
The CSS was hard, coming up with a theme of styles from my imagination was tricky as I am not a designer in any way shape or form

# Extra

Here are some links and sources that I used for the css
[https://css-tricks.com/almanac/properties/f/flex/](https://css-tricks.com/almanac/properties/f/flex/) This was to figure out the flex shortahnd property, this removes having to type flex-grow and flex-shrink.

I used this
[Link](https://dobrian.github.io/cmp/topics/sample-recording-and-playback-with-web-audio-api/1.loading-and-playing-sound-files.html#:~:text=Method%202%3A%20JavaScript,back%20the%20sound%20with%20the%20.) to help with sound of the buzzing when user clicks on the page. I couldn't add a sound as user went to my page as modern browsers do not allow it, as it can be annoying for the user. Luckily I know a little Javascript so adding the sound was pretty straight forward, I changed it to an audio constructor instead.

### What went really well and what could have gone better?

I feel overall I accomplished everything, I wish my page was more appealing, I feel if I was given a design in a later time in the course I could achieve it, but coming up with idea from scratch is hard. Hopefully knowing more about css in the future will make things better, I felt that I wads fighting a lot to mak it work. Maybe a thing called Tailwind CSS will help in the future.

I am happy to explain all my code if needed to prove I know what my code does. I would like feedback if possible
