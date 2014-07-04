

# On standards and sausages

In any industry, standards are vital, and the Web industry is no different.

After the dark days of the browser Wars, in which Microsoft and Netscape competed on adding ever more
proprietary whizz-bangs to lock developers in – ahem, more deeply engage developers into their eco-systems,
I mean – we’re in an age when all browser and tool vendors compete to tell you how great their
standards support is. And this is A Good Thing™.

As [Bismarck never said](http://en.wikiquote.org/wiki/Otto_von_Bismarck#Misattributed) “Laws are like
sausages. You should never see them being made” and the same is true of standards. There are many ways
to make a standard – some more palatable than others.

Some things are defacto standards – GIF, JPG, webM, h264. Others, like JavaScript (more accurately,
ECMAscript) are made by a committee in a smoky room – in the case of ECMAscript, a group with the sinister
name of [TC39](http://www.ecma-international.org/memento/TC39.htm).

Others are retrospectively standardised at the end of their evolution from proprietary whizzbang to defacto
standard to real standard. Examples of this are some of Microsoft’s best gifts to the Web:
XMLHttpRequest (XHR) which powers almost all Ajax-driven sites, innerHTML and contentEditable.

Another example, this time from Apple, is <canvas> – invented for Apple’s dashboard widgets,
liked by everyone and so reverse-engineered and improved by Mozilla, reverse-engineered and implemented by
Opera, reverse-engineered and specified by Ian Hickson as part of the HTML5 effort. When Microsoft wanted to
implement it, they didn’t have to waste hundreds or thousands of man-hours reverse engineering, with its
stupid waste of time and potential to introduce interoperability-damaging bugs: they just picked up the spec
and implemented what it said.

But as the editor of HTML5, [Ian Hickson](http://ln.hixie.ch/?start=1089635050&count=1), said of
<canvas>, “The real solution is to bring these proposals to the table, get some consensus between
the relevant vendors and other interested parties, and then use that.”

The best kind of standards process involves as many competitor stakeholders as possible going completely
crazy:

 *  sharing ideas

 *  trying out ideas in their own labs and sharing results

 *  discussing openly

 *  compromising where necessary to achieve concensus

 *  implementing what has been specified.

This is how the HTML5 effort has worked. Anne van Kesteren [described
it](http://annevankesteren.nl/2012/07/passion):

> We developed HTML in the open, taking
> input from anyone, and pretty much from anywhere (mostly tracking blogs back in the day). Until that point
> HTML was by and large developed by a committee in private meetings.

But the collegiate, co-operative, *productive* working environment that bloomed so encouragingly seems to be
withering.

More and more, we see different companies seeking to solve similar problems secretly, and without discussion.
This is why we have many formats for [packaged/installable Web
applications](http://www.brucelawson.co.uk/2011/installable-web-apps-and-interoperability/). Of course, each
company promises that it will *eventually* standardise its solution to the problem, leading to [a
proliferation of “standards”](http://xkcd.com/927/).

Trying stuff out (perhaps with vendor prefixes) and reporting back is a vital part if standardisation. But
presenting whole new features as a fait accompli, and encouraging their use by developers on the open Web
loses discussion, the sharing of ideas and results from the process. The end-result loses ease for developers
and, ultimately, interoperability for consumers – you know, the great unwashed that we actually make
Websites for.

Tossing a specification that you’ve written in-house, in secret and already implemented onto a table at
W3C, saying “here, standardise this” as you saunter past isn’t a Get Out of Jail Free card
for proprietary misdemeanours. And it isn’t standardisation.