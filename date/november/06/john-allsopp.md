

# Before and after Apps 

In some (very small, for the most part insignificant) circles, I’m known as the anti-native-apps
guy.

Which is in many ways fair. For years, I’ve argued that [the supposed commercial benefits to developers
are largely illusory](http://www.webdirections.org/blog/iphone-native-apps-the-great-leap-backwards/)
(something I continue to believe, and which the last several years largely demonstrates).

But, my principal concern with apps was actually best expressed last year by Scott Jensen, legendary HCI
expert at Apple, Symbian, Google and now Frog Design, in his provocatively titled “[Native Apps Must
Die](http://designmind.frogdesign.com/blog/mobile-apps-must-die.html)”.

> Native
> apps are a remnant of the Jurassic period of computer history, a local maximum that is holding us back. The
> combination of a discovery service and just-in-time interaction is a powerful interaction model that native
> apps can’t begin to offer.

Apps are a model of functionality that has shaped both what developers and designers do, and how users
conceive of what’s possible more or less for the entire history of computing. But I think they are a
dead end.

One interesting detour from the app-centric model of computing was the
[Lisa](http://en.wikipedia.org/wiki/Apple_Lisa) operating system, the not quite fore-runner to the Macintosh
from Apple. Lisa differed markedly from the Macintosh, and other graphical operating systems, in that it was
document centric. You didn’t open applications to edit documents, you opened documents to work on them.
Users focussed on the task at hand, not the tool.

Changing this conception of what a user experience might be is very difficult, so ingrained is the app-centric
model with users, and among ourselves as designers and developers. But what might a more user-centric model
look like?

Let’s take a very popular consumer application/service right now. Photo hosting. Well, it’s been
popular for quite some time, with services like Flickr now several years old, and then Instagram and numerous
similar services emerging particularly with the rise of smart phones.

But all of these services are monolithic—indeed are becoming more so. Most if not all of what a user can do
with them takes place inside one application (this is particularly true of services like Instagram). You
shoot, apply effects, crop, tag, annotate and upload all within the application. In the case of Instagram you
also sign up, search, follow people, in short, access the entire Instagram experience from inside the
Instagram app.

While we think of apps and services like these as photo-sharing services, they aren’t really. Instagram
is an Instagram app. Facebook is a Facebook app. Twitter increasingly is a Twitter app (as soon as they can
get rid of all those other pesky client apps). The application, the service, is an end in itself.

So, what might a user focussed, post-app photo sharing service (experience? thing?) (let’s call it
phUto) look like.

At its core, it would be a place to upload photos which people could view. Some users might want to apply
filters and effects to their photos. Now, if I were building phUto, I might build that functionality into it.
__Or__, I might make it possible for other developers to provide the user this functionality, ideally in a way
that felt seamlessly part of phUto.

Users might want to search the photos stored at phUto. I could build a search engine, and results experience.
Or, I could make it easy for developers to provide this functionality, and a way for my users to __easily
discover__ these search services, and use them in a way that feels like it’s a seamless experience.

You get the idea.

There have been complex attempts to enable this in the past. [OpenDoc](http://en.wikipedia.org/wiki/OpenDoc),
an enormous undertaking by Apple in the mid 1990s was among the most sophisticated of such attempts.
Microsoft’s ActiveX similarly was designed to enable unrelated pieces of functionality work together.
But recently, more lightweight approaches among them
[Android](http://www.vogella.com/articles/AndroidIntent/article.html) Intents and [Web](http://webintents.org)
Intents.

But as much as the technology for enabling this is important, the underlying concept is crucial.

The app model essentially creates silos of functionality, carefully created for the user. It gives rise to
feature creep, and rewards large teams with lots of engineering resources over smaller teams and individuals
who focus on one thing they can do really well.

Perhaps in a decade, or a century, we’ll still be working with monolithic apps. But I suspect (and
certainly hope) not.