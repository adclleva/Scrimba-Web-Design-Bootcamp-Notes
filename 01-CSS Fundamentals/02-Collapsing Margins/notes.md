By default, margins collapse into one another.

So if one element has a margin-bottom of 50px, and the next one has a margin-top of 50px, the space between them will be 50px and not 100px.

Margins will colla[se any time they touch each other. So, if the first child in an elemment has a margin-top, that can merge with the parents's margin-top

**This is where padding comes into play.**

In general, the background-color will always be on the parents. **We can add padding on the parent** to prevent the parent's margin from merging with the childs

Margin = empty space
Padding = more background