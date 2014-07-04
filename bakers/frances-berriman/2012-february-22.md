

Various debates this last fortnight, particularly around vendor prefixing and using other work in progress
features, reminded me of the importance of testing in my workflow. Working to make your users get the best
experience possible is still paramount. The only way to succeed in doing this is to understand what they see,
and then fix and enhance accordingly. I've seen mentions of cross-browser testing missing from many of the
arguments, and blindly using prefixes more or less encouraged.

If you're not noticing the lack of a prefixed property, where one is available in a browser your site has
visitor stats for and a commitment to support, I'm guessing you're not looking very hard at all in those
browsers. They probably have more fundamental problems than a few missing rounded corners. Worse still, if
you're not testing thoroughly, using a vendor's work in progress, unfinished, unstandardised feature could
make your site behave poorly in ways you can't foresee. Using a prefix for a certain vendor should be an
automatic commitment on your part to check what that prefixed effect actually looks like in those browsers
that understand it.