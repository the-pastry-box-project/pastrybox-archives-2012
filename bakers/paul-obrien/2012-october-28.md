

When you’re designing your latest greatest website please don’t account for every pixel in the page as
though your life depended on it. Too often I see elements that stretch the full with of a page and have no
breathing space should the content be one character wider than the author imagined.

Browsers render text at various widths anyway and ultimately you have no control over what size the user may
have set so bear this in mind when creating menus and similar elements that you want to exactly fill the
horizontal space.

Use techniques that allow breathing space or indeed will allow text to wrap nicely should the text be resized
by the user (or should a certain browser decide that words will be wider than other browsers might make them).
The easiest solution is simply to allow extra room by default and not fill every pixel on the page. A more
robust solution is to build the element so that it can grow and wrap if necessary without breaking the
structure. Too often I see the last menu item on a menu missing because the browser couldn’t fit it all on
the same line and the last item has wrapped and been hidden because the overflow was hidden.

Some techniques you may want to try are using display:table and table-cell properties (IE8+) instead of floats
and allowing the menus to automatically spread without the need for horizontal padding. If you want to use
floats then often you can “not float” the last menu item and let it just fill the remaining available
space automatically.

Always plan ahead and expect that what you are seeing on your desktop may not be the same as what someone else
may see.