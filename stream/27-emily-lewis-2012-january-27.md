

There's this home improvement show called Holmes on Homes, where a contractor visits a home that has
been plagued with problems like electrical issues or roof leaks. The contractor, Mike Holmes, inspects the
house from its foundation to its insulation and identifies the culprits of the issues.

99% of the time, the reasons for the problems with the home is that the original contractor simply did a
shitty job. Sometimes, the shitty job can be blamed on money: the home owners didn't want to spend the money,
so they hired an unlicensed contractor. In those cases, you get what you pay for.

But most of the time, the shitty job comes down to a lack of fundamentals. Over and over, Holmes points out
areas where the original contractor did the job without following best practices or even relying on
fundamental techniques and materials.

And 100% of the time, these homes *look* great. They appear grand and fancy, with all the modern
amenities.

From the first episode I watched, I immediately drew parallels with the web industry because I don't think the
majority of practitioners in our field focus on fundamentals. In fact, I'm not even sure the majority of
practitioners even know the fundamentals. __And this lack of knowledge and/or execution is damaging our
industry__.

Consider the scenario I currently find myself in: I have a client with a custom, in-house-built CMS who needed
a design and front-end development for their CMS templates. Straightforward enough. That is, until I got into
the templates.

The HTML was a sea of nested (and nested and nested) `<div>`s, inline CSS and `<span>`s for
headings, just to name a few offenses. The linked CSS was even worse, bloated with unused selectors,
overly-specific selectors and redundant styles.

These templates weren't developed years ago … not even a month ago. December 2011. By a developer who says
he has “many years of experience”.

While I will hold my tongue regarding the aforementioned developer's actual "experience," this situation is
far more common than I think people realize. *Especially* if you find yourself insulated by the web
standards bubble, where we all talk to each other and buy each other's books and read each other's blogs
and work on projects where standards are a given.

Amongst "our own" we think everyone is passionate about semantic markup or that everyone cares about progressive enhancement or even that everyone already knows how to build with standards. But
this, sadly, isn't the case … especially in an industry where skills are overwhelmingly self-taught.

Outside the web standards bubble I like to reside in, the web seems like the Wild West. Standards? What
standards?

If a `<span>` gets the job done, who cares about semantic markup? If you can't get your specificity
right, use `!important` and use it everywhere! If text won't indent, throw five `<div>`s around it and
give each padding! If a column won't align, put it all in a `<table>`. Who cares if it doesn't work if
JavaScript is disabled? Who cares if a blind user can't turn off the audio that started playing on page
load?

Pedantic? Perhaps. But though these things may *seem* small, they are actually a big deal. For me, as the
front-end developer who has to work with that kind of crap, I get frustrated and I tend to hate my job in
those moments. But that hassle isn't my main concern. It's the cascade effect this kind of development leads
to.

It's now a big deal to my client, who has to pay me more because working in such convoluted markup and CSS
takes more time than the alternative. It's now a big deal to that developer, who is has a very unhappy
employer.

But even worse, it's now a big deal when my client talks to other prospects or considers future work. Because,
from my client's perspective, he's paid two developers and *still* doesn't have a solid system that meets his
needs and is easy to maintain.

No, it isn't a bomb that goes off to destroy our industry. It's a trickle of water that slowly (but surely)
erodes opportunities, trust and perceptions of value.

And let's not forget, it just isn't possible to build something awesome on a shitty foundation. Whether it is
a house or a web site, the latest techniques and trends require a solid understanding (and execution) of
fundamentals.

Take responsive web design. If you don't understand the basics of the box model and how an element's
true width is determined, good luck getting a fluid design working *before* you bang your head so hard against
your desk you pass out.

Fundamentals are important. Not just to sate the pedants and standardistas, but to ensure that we all have
great opportunities for work. To ensure our clients feel satisfied with their investment and remain positive
about future development with people they can trust. To ensure that our field is respected so that we can all
earn pay commensurate with our value.

I'm hopeful efforts like Move the Web Forward will help slow the steady stream of crap that plagues
our industry. The project offers a variety of fundamental ways designers and developers can get involved to
make our industry (and the web) better. Please go check it out, and then spread the word far and wide.

Pretty please? Because I want to dream of a day where I never again encounter 20 nested `<div>`s inside
a `<form>` that encompasses everything between the opening and closing `<body>` tags, all of which
styled with inline CSS.