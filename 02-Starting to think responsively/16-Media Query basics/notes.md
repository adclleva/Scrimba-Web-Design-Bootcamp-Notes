The media type let's us target different types of media
- Screen @media screen {...}
- Print @media print {...}
- Speech @media speech {...}

The media condition let's us target specific cnoditions within that medai type
- Widths @media (min-witdh: 600px) {...}
- Orientation @media (orientation: landscape) {...}
- Specific features @media (hover) {...}

Having both media types and conditions are optional.

We do need to either have a type or a condition though.

For example, we can target only screens.
@media screen {...}

Or we can choose only a condition, such as the width of the viewport.
@media (min-width: 960px) {...}

You can combine a type with a condition by using and.
@media screen and (min-with: 960px) {...}
@media screen and (orientation: portrait) {...}

For now, we're focused on min-width and max-width

"all and" is sometimes you see in old browsers but now we don't really need it

also keep in mind that css code reads from top down and the latest code with take
effect, thus order matters, depending on case

landscape means that it is wider than it is tall
while portrait means that it is taller than it is wide

https://css-tricks.com/logic-in-media-queries/

media queries should also be after the selected 

there's also different approaches with media queries as you can have them all at 
the bottom of the css file or have the media querie be right below from their 
respepctive selector