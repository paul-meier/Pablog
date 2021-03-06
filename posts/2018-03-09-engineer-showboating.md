    Title: Engineer Showboating
    Date: 2018-03-09T16:49:09
    Tags: engineering, culture, management
    og_image: https://morepablo.com/img/2018/3/profunctor_optics_THUMB.jpg
    og_description: How to fake it (in 2010, anyways)

<small><em>The song for this post is <a href="https://www.youtube.com/watch?v=bM9SHDNAbPw">Psycho Killer</a>, by The Talking Heads.</em></small>

A phrase [in my post on meetings][1] that got some reaction was "every complex
system has parasites."

So when have I been a parasite? When have I gamed a system to extract value for
myself at the expense of a greater ecosystem?

One example I've never been private about (but haven't written about widely)
is how consciously I played the Engineer Showboating game while transitioning
from a theater identity to a STEM one in undergrad, around 2008-2010. I saw
and matched patterns of what "real engineers" do to gain clout with folks in the
CS department.

I'll share them here, mostly to inoculate you against such tricks.

### Fear, Insecurity, fooling yourself

I'd like to remind you that, like any system that involves adopting markers
to game an outcome, it was motivated by fear and insecurity. It's often the fear
that one really isn't good enough, the fear that one doesn't deserve it. In my
case, my "outcome" was to be a respected, capable technologist, so I optimized
on these fronts out of fears that I wasn't any good, or that I couldn't be in a
reasonable timeframe. I wanted to be treated like a pro, so I focused
my attention on these shallow indicators.

Having these fears, and this response to it (adopting markers of behavior and
identity to avoid fixing or confronting said fears) is generalizable,
and especially common in communities of men.  Consider men who have fears of
vulnerability but want to have sex, so they adopt Pick-Up Artist techniques
rather than learn to be a whole, communicating person.  Or men who fear they
might actually not be The Hero Of A Great Story like they feel like they
deserve, so they reject the ample evidence of structural inequality and become
reactionaries against the equality of others.

On top of being awful, the big risk with avoiding pain and denying the existence
of these fears is that you'll end up believing your lies. Getting high on
your own supply is a classic dealer mistake, and many lose sight of what victory
actually looks like. Turns out most people are content to merely _feel like_
they've acquired some status, rather than actually completing the achievements
that would confer it. It's a lot easier to convince yourself that you're a good
technologist than to actually be one under scrutiny, so a lot of folks stop the
scrutinizing themselves, point to hollow signifiers, and rest on their laurels.
Don't do this. You'll be a shitty technologist and just show your ass to anyone
who knows how to look (which is hopefully a few more people after this post).

Finally, a reminder: if _A_ → _B,_ it _does not follow_ that _B_ → _A._ If
someone is performing these behaviors, that doesn't mean they're necessarily
full of crap; just know that people who are full of crap might exhibit these
behaviors.

### Partial list of signals to watch out for

Here were some flexes I optimized for when I wanted to be Taken Seriously by
people in computing.

#### Terminal-based editor and tools

The reason I learned [vim][2] wasn't because I felt particularly inhibited by
my editing speed in graphical environments, it's because _it conferred
authority._ The Cool Kids in the back row of [the Sunlab][20] never touched
their mouse, there was just frantic tapping and their cursor would dance around
while the screen magically produced what they willed it to. I wanted to be a
cool kid too, so I learned vim.

To shallow observers, there's a bit of a heirarchy among editors:

<ul>
<li style="margin:0"><strong>S Tier:</strong> Emacs, Vim</li>
<li style="margin:0"><strong>A Tier:</strong> Sublime Text, VS Code</li>
<li style="margin:0"><strong>A minus Tier:</strong> Atom (snobbery against web developers and web tech is also a way
  to be Serious in computing, and Atom trends this way)</li>
<li style="margin:0"><strong>Opaque Tier:</strong> JetBrains IDEs, Visual Studio</li>
<li style="margin:0"><strong>B Tier:</strong> Eclipse, NetBeans</li>
<li style="margin:0"><strong>C Tier:</strong> Graphical text editors</li>
</ul>

It's all horseshit, of course; my best friend who could code circles around me
did everything in [Gedit][4] without indentation support or syntax highlighting.

Do whatever works. My limited experience with VS Code has been delightful, I'd
probably go with that if I were starting over. If someone gives you shit for
your editor, be grateful they showed you their ass, then keep going.

#### Programming Book culture and how to game it

It feels a bit less prevalent now than it did in 2010, but there's a bit of a
culture around programming books. _This_ book is a must-read, _that_ book is
overrated, Real Developers have a copy of _that_ on their desk. You get bonus
points if you have some kind of exasperated reaction (sighing, groaning, or
cheering) anytime one of these books gets brought up.

I bought and read a ton of them. Here are a few, plus what you need to
know about them:

##### Mythical Man-Month

You don't have to read this: just internalize the notion that adding people to a
project won't make it go faster ("you can't make 9 people have a baby in 1
month"). It spends a lot of time on 1950's minutiae ("[microdot technology][5] will
change documentation culture, since the current printouts of paper stack so
high!") or even advice we now consider bad (Brooks was about complete
transparency of implementations, we now believe hiding that detail behind an
interface to be way better). Turns out stories from 1950's OS development are
largely historical in their value!

The other major takeaway is in the title of the supplemental essay "There Is No
Silver Bullet." Software is hard and always will be. There, you got most of what
you needed.

##### Code Complete

I feel like this mostly got popular since it was Jeff Atwood's favorite book,
and where he got the Coding Horror branding behind his blog. It's pretty massive
and contains a lot of common-sense information, and is brave enough to even
sometimes take a stance on issues largely relegated to taste (e.g. the ideal
length of a method), trying its hardest to back it up with science and observation.

Overall, I didn't feel like it was critical to my development as an engineer
because of the underlying assumptions of what and how you're programming: it was
largely about C++ Object-Oriented programming like they did at Microsoft on desktop
software for about a decade. It won't hurt to read this!  But I found it's
applicability less general than how it was sold.

##### The Pragmatic Programmer

When I was managing, I was recommended a silly book on management and leadership
written by Ben Horowitz, and [I said][7]

> More than trusting or believing his accounts of how it all went down, watching
> how he frames those events and the characters involved does a lot to
> illuminate how the VC class thinks of themselves, the industry, and its
> history. You can think a church is worshipping clearly false idols but still
> find value in reading their holy texts, especially if you don't have much of a
> choice but to have to deal with them.

And I feel _The Pragmatic Programmer_ is a good text for understanding the
mentality of Serious Programmer Culture in a similar way. It's got some concrete
advice that I follow, but the major takeaway is that it implores programmers to
treat programming like a craft. If there's any book that's going to show you the
kind of signals you can boost and communication style you can imitate to Look
Cool, it's probably this one.

##### The C Programming Language

This is A Classic because it's got a lot of things that provoke reactions in
people:

* Due to manual memory management, lack of a module system, inclusion of
  pointers, and spare standard library, C is considered Cool and Hardcore. If
  you write software in C you're probably Cool.
* Not for nothing! C _is_ pretty brilliantly designed in how spartan its
  feature set is while still powerful enough to facilitate the computing revolutions
  it did.
* Folks like to reminded of the above, and since it's not a huge language, you
  can explain it pretty well in a small handful of pages.
* C is probably the closest most folks come to "thinking like a machine," so I
  think it evokes nostalgia for the fun of that, too.

##### Structure and Interpretation of Computer Programs

This is something of the holy text for a way of thinking about computing that
[even the authors recognize isn't how we program computers anymore][8]:
attempt to fully reason about composable pieces, and recognize design tradeoffs.
This stuck with me more than most, but per the theme of this post, you really
don't _need_ it.

Just like The C Programming Language gets cred for being C, this gets elevated
in part because it uses Scheme, another language loaded with romantic
narratives.

Part of incorporating this into my identity (rather than merely being a fan) is
demonstrated in [my Twitch handle,][9] `sicp`.

##### The Following Books are largely overrated and I doubt most people have read them, but are still Status-conferring

* [Design Patterns][22] (WOW boring and less applicable than you'd think).
* [The Dragon Book][21] (WHO LOVES PARSING BEFORE [ANTLR][16] AND [LLVM][17] WERE THINGS)
* [CLRS][18] (also super dry; though it is comprehensive)
* [CTM][19] (okay, this is probably fine, I just never got around to it, Oz looks
  pretty cool)

Feel free to list any books I forgot to mention in the comments.

#### Functional Programming

<div class="caption-img-block" style="margin: 25px auto">
<a href="https://twitter.com/aisamanra/status/804553283578646528/photo/1" target="blank">
<img src="/img/2018/3/profunctor_optics_THUMB.jpg" alt="PROFUNCTOR OPTICS. Click for source." style="margin: 15px auto;" /></a>
<p style="font-style: italic; text-align: center; font-size: small"><a href="https://twitter.com/aisamanra/status/804553283578646528/photo/1">via</a></p>
</div>

Many toxic people find a home in some Functional Programming
communities. Certain FP communities [amplify slavery-glorifying fascists][13] in
the name of inclusion, and [torturously re-invent social science with glaring bugs][14]
to justify it. They'll also create [silly ladders about how real a programmer
you are.][15]

A lot of that is metastasis of the cultural forces that give you that
Credibility Boost this post is about: functional programming is a non-default
way of programming for most, and makes certain operations require contortions other
languages don't. A lot of practitioners make a performance of reminding
non-practitioners, repeatedly, that they're not as good or smart for
not programming like them.

It reminds me of a classic tweet, whose original author I think deleted their
account:

> Atheists are like gamers in the sense they take the least interesting aspect of
themselves and make it their whole personality for no reason

I happen to love Functional Programming, but as with many communities around
activities I enjoy, the fans make it awful. But! If you want cheap status, learn
it, and frequently brag about it. 

#### News Aggregators, The New Hot thing

You can pattern match against [Hacker News][10] and [Reddit Programming][11] and
[Lobste.rs][12] and always know the Hot New Thing people are talking about. You
can fake a lot by checking them every day and skimming comments. You get bonus
points for hyperbole (e.g.  saying a tech that isn't on the rise is "dead").

### Unlearning

I gamed the above and some fools took me more seriously. I looked in the mirror
and _felt_ like I knew things about being a Good Engineer. I almost certainly made
people along the way feel lesser for flouting the above. I feel terrible
about it, and wish I hadn't.

To be clear, the above wasn't completely valueless! I did read all those books,
and it's easy to take the things you already have for granted; I may very well be
devaluing the knowledge I acquired in doing all the above. If you choose to
investigate any of those paths, use me as a resource and/or let's chat 😄

I'll also state that my behavior was both a cause and a symptom. I hit these notes hardest
because I gleaned, from my peers and the online presence at the time, that these
things mattered. I wish I hand't _performed_ that process so much, though.

**Don't let anyone tell you there's a specific way to be an amazing engineer.**
If you came from Scheme and FP, great! If you wrote games, great! If you're
coming from browser programming, awesome! iOS? Did you start with C or assembly? All
fine! 

I'll write a follow-up on what I think _does_ make a strong engineer, and what
I've substituted the above with in the process of unlearning. But if someone
flexes a lot of the above, note that they're probably just afraid or insecure.

---
(if you found this interesting, you'd probably also enjoy [Jenn Schiffer's
Deconstruct talk][23] from 2017).


   [1]: /2018/02/meetings-baby.html#parasites
   [2]: https://www.vim.org/
   [3]: https://superuser.com/questions/246487/how-to-use-vimtutor
   [4]: https://wiki.gnome.org/Apps/Gedit
   [5]: https://en.wikipedia.org/wiki/Microdot
   [7]: /2016/08/six-months-of-managing.html#resources-i-consumed
   [8]: http://www.posteriorscience.net/?p=206
   [9]: https://www.twitch.tv/sicp
   [10]: https://news.ycombinator.com/
   [11]: https://www.reddit.com/r/programming/
   [12]: https://lobste.rs/
   [13]: https://medium.com/@codepaintsleep/lambdaconf-2016-controversy-2d4b13c338cf
   [14]: http://degoes.net/articles/lambdaconf-conclusion
   [15]: https://pbs.twimg.com/media/CydL5EYUsAAI-61.jpg:large
   [16]: http://www.antlr.org/
   [17]: https://llvm.org/
   [18]: https://en.wikipedia.org/wiki/Introduction_to_Algorithms
   [19]: https://mitpress.mit.edu/books/concepts-techniques-and-models-computer-programming
   [20]: https://cs.brown.edu/about/rooms/sunlab/
   [21]: https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools
   [22]: https://en.wikipedia.org/wiki/Design_Patterns
   [23]: https://www.deconstructconf.com/2017/jenn-schiffer-how-to-be-a-real-developer
