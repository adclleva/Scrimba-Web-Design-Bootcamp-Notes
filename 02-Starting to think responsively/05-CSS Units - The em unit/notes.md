Relative units are always relative either to a font-size, or the size of the viewport.

For those which are relative to a font-size, which font-size they are relative to depends on a few things, which complicates matters

The em and rem are considered relative, because they are relative to the font-size of other elements

- em are relative to their parent's font-size
- Font-size is an inherited property, so if you don't declare it anywhere, it's getting it from the body (or the default, which is normally 16px)

Em and rem is something that is commonly used