That synching feeling.

How many screens do you routinely use to access email, messages, web content? Two? Three? More?

On what devices do you store your music, photos, movies?

On what devices do you view movies or photos? Listen to music?

As users (and most likely as developers and designers too) we are used to thinking of movies, photos, and so
on as discrete things, located in a given place. 

This in no small part comes from the pre networked days of computing, where we associate a document, an image,
a song, and so on with an individual file on our computers hard disk.

But even that analogy is inaccurate. A file on a disk is not a single thing. It's not even a contiguous block
of memory on a hard drive. Rather it's a whole lot of little fragments, scattered all over a drive, kept track
of by the filesystem.

For us as humans, knowing this, let alone keeping track of the implementation details is a waste of time (even
for most developers, we can safely think of a file as a discrete object).

So, the notion of a file as a thing, located in a given place, distinct from the identical information located
elsewhere, even on the same drive is a useful metaphor. But a metaphor none the less.

And while metaphors are useful, they are also dangerous.

Because we are burdened by this metaphor, when it comes to managing our information across multiple devices,
we imagine that this information is on each of these devices. Which it may be. But that's purely an
implementation detail.

When I play a song on my laptop, does it really matter whether it's *really* stored on a server at Apple, or
Google, or Amazon? Or on a NAS on my local network? Or on my phone?

When I open a file to be edited, do I care where it is located? 

Those are implementation details, for developers to worry about.

Yet our mental models of what is happening when we play a song, or edit a document, or watch a youtube Video
on AppleTV are encumbered, burdened with the metaphor of a file as a discrete thing, located somewhere
specific. 

Hence our obsession with "cloud computing" (as if we ever cared about "magnetic computing"). And our obsession
with synching. Something which simply should be an implementation detail for developers to concern themselves
with not something we as users should have to worry about, or even know about.

Which is all a roundabout way of saying that our mental models of computing are still essentially rooted in
the 1940s and 1950s. 

The device I hold in my hand, or which sits on my laptop, or my desk is still a store of data, connected to a
whole lot of other such devices, some big, some small.

But that metaphor has outlived its usefulness. 

Devices are portals to information, and it really shouldn't matter where that information "really" is. Whether
it's cached locally to my device, or always refreshed from a server, shouldn't matter to our user, or to us as
a user.

When I start editing a document, then open that document in another device, I should be seeing the same
document. When I start watching a movie on AppleTV, then take my phone to bed to finish watching the movie,
it should be the same movie.

Gmail gets closest to this model, indeed does it quite well. But I think it is a metal model of computing that
we should strive for as we design and develop for any connected devices.  