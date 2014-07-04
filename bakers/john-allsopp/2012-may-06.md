

In the last 12 months or so, I've had a number of quite specific online conversations about the performance of
web technologies. Indeed, some of these conversations go back quite a bit before that. 

Most recently, I critiqued a spate of articles arguing that localStorage suffers from performance issues
(well, might in theory, [though evidence suggests
otherwise](http://www.webdirections.org/blog/localstorage-perhaps-not-so-harmful/)).

9 months or so ago, for reasons best known to myself, I posted a [point by point
critique](http://blog.theunpluggedweb.com/post/6536550719/the-native-is-better-thing-again-sigh) of one of
John Gruber's typically fact free pieces asserting that native apps are inherently better than apps developed
with web technologies. At the heart of these arguments is the issue of performance. 

Developers care a lot about performance. The mark of a quality application is responsiveness. Not in the sense
we've come to use it recently, but in the sense of the perceived lag between a user's action and the
outcome.

Typically, these conversations are about performance in the absolute—for example, it's frequently asserted
that any "native" app will always be faster than a web app, because native apps are compiled, and web apps use
interpreted JavaScript.

But this is essentially a meaningless observation, because performance is just one small, although of course
very important, piece of the puzzle. Lower level, more highly performant languages may well impact time to
market, cost of development, platform reach, and more.

Practical developers typically care not about overall performance, but the bottlenecks where performance
becomes an issue—often because it impacts the user experience. Developers optimize for those bottlenecks,
and it's only when after all optimisation, performance remains below a certain threshold that we have a real
issue.

In essence, at present most conversations about performance take place at an ideological level. Where we need
them to take place is the practical level.

When someone observes something lacks performance, is "slow", or however this is characterised, hand waving
like "compiled is always faster than interpreted" or "synchronous is always slower than asynchronous" miss the
point. What we need to do is:

 *   Identify the specific, measurable performance issue

 *   Benchmark this, so as to meaningfully compare it with alternatives, and also to derive a measure of what
is adequate (in performance, as elsewhere, the perfect is often the enemy of the good)

 *   Look for optimisations which can help provide adequate solutions in the given circumstances

We have a genuine issue when we can't do the third step.

Too often we fall into black and white thinking, which is anathema to engineering, the art of making stuff
work. In engineering being right isn't as important as solving the problem. Sure, rhetorical discussions may
be engaging, but they don't really solve much. 

When it comes to development, we have so much to learn. Glibness won't help us do that.