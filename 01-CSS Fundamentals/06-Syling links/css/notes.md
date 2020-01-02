Since we're talking about inline elements, it only makes sense to look a little more at how to style links.

We can change the style of a link like any other element, by using a simple element selector.

a {
    color: #f30;
}

Links have different "states" that we can style as well.
- Default "link" state
- Visisted
- Focus
- Hover
- Active

We can target these different states by using something called a pseudo-class
- a:link
- a:visisted
- a:focus
- a:hover
- a:active

The order of where the classes or css is in the style.css file matters

Makre sure when styling links, people know that you can interact with them! It should be very obvious
- Change the color on hover and focus
- Leave the text-decoration on, or, if you turn it off, make sure it's still obvious that it's a link!
- Remember to also include styles for :focus