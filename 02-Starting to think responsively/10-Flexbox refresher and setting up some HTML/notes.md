Elements normally have a display: block
or a display: inline
as a default from the browser

Block elements stack on one top of each other:

- div, header, footer , main, etc.
- h1 -> h6
- p

Inline elements stay within the flow of what's around them

- a
- strong
- em
- span

We can change this behavior by setting the display peropert to flex on the parent element

One of the most difficult part is organizing the layout

the case in this one, there's one single container
then have a div for a columns container
and each columns container would get col containers inside them

thus it would be
    .container
        .columns
            .col
            .col
        .columns
            .col
            .col
            .col
