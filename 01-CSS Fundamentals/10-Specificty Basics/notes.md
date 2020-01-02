Specificty in CSS is all about how specific our selectors are. **The more specific they are, the higher priority they have!**

From the selectors we've seen so far, from lowest to highest specificity:
- Element Selector
- Class Selector
- ID Selector

This is one of the reasons many class naming conventions only use classes

If you understand specificity, you can get away with other ways of approaching things, but sometimes it complicates matters in the long run for nothing.

Here is how I gnerally approach styling things

General rules get put on elements selectors
e.g. body, headings, paragraphs, etc.

Everything else gets a class