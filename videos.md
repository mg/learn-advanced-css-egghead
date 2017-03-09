#### Target empty elements using the ``:empty`` pseudo-class
[Video](https://egghead.io/lessons/css-target-empty-elements-using-the-empty-pseudo-class)

Use pseudo class ``:empty`` to target any element that might not have any content. Use ``:not(:empty)`` to only target those elements that actually have content.

#### Target Positional Elements Using ``*-Of-Type`` CSS pseudo-classes
[Video](https://egghead.io/lessons/css-target-positional-elements-using-of-type-css-pseudo-classes)

- ``:first-of-type``: Target the first of its type
- ``:last-of-type``: Target the last of its type
- ``:only-of-type``: Target the only of its type
- ``:nth-of-type(odd)``: Target every other of its type
- ``:nth-of-type(3)``: Target the third of its type
- ``:nth-of-type(3n)``: Target every third of its type
- ``:nth-of-type(4n+3)``: Target every 4th of its type starting after 3rd of its type

#### Easily Reset Styles With a Single CSS value
[Video](https://egghead.io/lessons/css-easily-reset-styles-with-a-single-css-value)

Setting the value of a property (e.g. color, font-size) to ``unset`` resets the value to what it's parent (or any other ancestor) set it to.

#### Control Image/Video Aspect Ratio Using CSS
[Video](https://egghead.io/lessons/css-control-image-aspect-ratio-using-css)

- ``object-fit: fill;``: Stretch the image to fill it's parent.

- ``object-fit: contain;``: Best fit the image in the parent without stretching.

- ``object-fit: cover;``: Fill the height and width to the parent without stretching, crop if necessary.

- ``object-fit: none;``: Don't resize the image to fit the parent in any way.

- ``object-fit: scale-down;``: Use the smaller of **contain** and **none**.

- ``object-position: with height;``: Default is ``50% 50%%``.
