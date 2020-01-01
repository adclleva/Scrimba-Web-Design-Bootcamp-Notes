For consistency, often we "turn off" the margin-top on typography related elements.

That way we can use padding on the parent. and know the exact spacing that we'll have, and can keep all slides constistent.

Also, when we get into layouts with flexbox and grid, margins no longer collapse, so this helps us stat more consistent.

That could be painful, but we can include all the elements in one selector!

h1, h2, h3, p {
    margin-top: 0
}

Always remember that the padding and margins add up for opposite sides