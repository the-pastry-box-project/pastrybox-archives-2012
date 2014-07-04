

There's a lot to think about when you're building something on the web. Is it accessible? How do I handle
translations of the text? Is the design OK on a 320px-wide screen? On a 2320px-wide screen? Does it work in
IE8? In Android 4.0? In Opera Mini? Have I minimized the number of HTTP requests my page requires? Is my
JavaScript minified? Are my images responsive? Is Google Analytics hooked up properly? AdSense? Am I handling
Unicode text properly? Avoiding CSRF? XSS? Have I encoded my videos correctly? Crushed my pngs? Made a print
stylesheet?

We've come a long way since:



	<HEADER><TITLE>The World Wide Web project</TITLE><NEXTID
	N="55"></HEADER><BODY><H1>World Wide Web</H1>The WorldWideWeb (W3) is a
	wide-area<ANAME=0 HREF="WhatIs.html">hypermedia</A> information retrievalinitiative
	aiming to give universalaccess to a large universe of documents.

Look at [http://html5boilerplate.com/](http://html5boilerplate.com/)—a base level page which helps you to
cover some (nowhere near all) of the above list of things to care about (and the rest of the things you need
to care about too, which are the other 90% of the list). A year in development, 900 sets of changes and
evolutions from the initial version, seven separate files. That's not over-engineering; that's what you need
to know to build things these days.

The important point is: one of the skills in our game is knowing what you don't need to do right now but still
leaving the door open for you to do it later. If you become the next Facebook then you will have to care about
all these things; initially you may not. You don't have to build them all on day one: that *is*
over-engineering. But you, designer, developer, translator, evangelist, web person, do have to understand what
they all mean. And you do have to be able to layer them on later without having to tear everything up and
start again. Feel guilty that you're not addressing all this stuff in the first release if necessary, but you
should feel a lot guiltier if you didn't think of some of it.