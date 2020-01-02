The font-family property is used to set the font you want to use for a given selector

font-family: Helvetica;

We can also use generic font styles, which will use our computers defaults

font-family: sans-serif;
font-family: serif;
font-family: cursive;

The problem with setting a font-family is, that font will only work if the visitor has the specfici font installed on their computer.

If we're using a generic font style, we dont' actually know what font is loading in.

To solve this, we can use font stacks, which allow us to declare backup fonts if the first one we wanted didn't work.

For example:
.class {
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
}

https://www. cssfonstack.com is a helpful source