---
layout: way
title: "Chapter Zero: A Quick And Dirty Explanation"
redirect_from:
  - /quick
  - /dirty
  - /explanation
  - /quick-and-dirty
author: Gigi
order: ch0-03
toc: true
---


> Explanations are clear but since no one to whom a thing is explained
> can connect the explanations with what is really clear, therefore clear
> explanations are not clear.
>
> [Gertrude Stein](https://en.wikiquote.org/wiki/Gertrude_Stein)

> Paradoxes explain everything. Since they do, they cannot be
> explained.
>
> [Gene Wolfe](https://en.wikiquote.org/wiki/Gene_Wolfe)

Above all, Bitcoin is paradoxical. It is simple yet complicated,
ever-changing yet unchangeable. A novel machine without any novel parts;
a technological innovation that isn\'t really about technology. You
can\'t touch it, yet it is hard money. You can\'t see it, yet it will
show you a vision of the future. You can\'t possess it, yet thousands of
people seem to be possessed by it.

All that makes Bitcoin notoriously difficult to understand - and even
harder to explain. As John Oliver so succinctly quipped, \"it\'s
everything you don\'t understand about money combined with everything
you don\'t understand about computers.\" While this is true, and while
one doesn\'t have to necessarily understand bitcoin to use it, it helps
to have a deep understanding of money and the technology that powers
Bitcoin to truly appreciate the gravity of the situation. Unfortunately,
even a basic understanding of Bitcoin requires some expertise in
networks, markets, cryptography, game theory, mathematics, physics,
computer science, and human behavior. If it were easy to understand and
convey, hyperbitcoinization \[Footnote: \<\<Hyperbitcoinization>\> is
the final phase of the transitionary period in which humanity upgrades
its monetary operating system from fiat money to bitcoin.\] would be in
the past, and we would be on a bitcoin standard \[Footnote: The *Bitcoin
Standard* is a book written by Saifedean Ammous, describing how bitcoin
could be the base of a global sound monetary standard, similarly to how
the world used to be on a gold standard in the past.\] already. As
Satoshi remarked almost one year after his initial publication:
\"Writing a description for this thing for general audiences is bloody
hard. There\'s nothing to relate it to.\"

While many people have tried to do exactly that - describe Bitcoin for
general audiences - I\'m not sure that such a thing is even possible.
There truly is nothing to relate it to, so all metaphors, historical
equivalencies, and explanatory shortcuts will miss the point in one way
or another. It seems to me that the proverbial sat \[Footnote: in
pre-bitcoin times, we would call this a penny.\] will drop for
everyone *individually*, and without talking to you personally, I can\'t
know what your hangups are. Maybe you think that Bitcoin has no
intrinsic value, or that it can be shut down by governments, or that it
will be hacked, or that it will be superseded by another technology, or
that using it is unethical because of its energy consumption or illicit
use. All these concerns are more or less valid at first, but, believe it
or not, they fade away as your understanding of money in general---and
Bitcoin in particular---increases. Alas, this understanding doesn\'t
come easy. It seems that very few people are curious enough to put in
the necessary work, which, in turn, means that most people will have to
learn the hard way: they will have to deal with bitcoin out of
necessity.

That being said, it is definitely possible to understand Bitcoin and the
implications that its continued existence will bring about. If this
weren\'t the case, there would be no bitcoiners, no bitcoin developers,
and no individuals investing in Bitcoin\'s future. Everyone who was once
bitten by the bitcoin bug has their own \"a-ha!\" moment to share, and
my hope is that exploring this phenomenon from a vast array of
perspectives will increase your chance of having such a moment.

Before we explore these different viewpoints in-depth, a quick and dirty
explanation is in order. I will try to explain how Bitcoin works, what
you can do with it, why it is important, who is behind it, what
\"bitcoin\" is, and what its fundamental building blocks are.

### How It Works

In essence, Bitcoin is a large spreadsheet that documents who owns how
much of Bitcoin\'s internal units: *sats, *short for *satoshis.* This
spreadsheet contains a record of all transactions that ever happened, in
the form of \"Alice sent 21 sats to Bob.\" To keep everyone honest,
everyone gets a copy of this spreadsheet. Everyone can add entries at
the bottom of it, as long as certain rules are followed. To do so,
people are taking part in a kind of game, not too different from a
lottery or sports competition. The odds are set up so that roughly every
ten minutes, someone will win this competition, allowing them to add a
batch of entries at the bottom. The spreadsheet has certain internal
rules that prevent the modification of past entries. If you change these
rules in a backward-incompatible way, other people will refuse to play
with you, effectively kicking you from the network. It is these rules
that make sure that all the accounting is done correctly, e.g., that the
person who wants to send money actually has the money and that the money
is sent to only one other person. In addition, these rules make sure
that no money is created out of thin air, which in turn ensures that no
more than 2.1 quadrillion sats (= 21 million bitcoin) will ever exist.

No single entity can change the rules because everyone on the network
has to opt-in to changes voluntarily. All participants play according to
their own rules. Thus, nobody is in charge of the rules. Everyone is
free to participate. All you need is a computational device and an
internet connection.

That\'s pretty much it.

{% include image.html name="quick-and-dirty.png" %}

If you know a thing or two about Bitcoin already, you will realize that
what I called the spreadsheet is Bitcoin\'s (distributed) ledger, what I
called batches of entries are Bitcoin\'s blocks, what I called a lottery
is better known as mining, and what I called rules are, well, Bitcoin\'s
consensus rules.

Granted, everything is a tiny bit more complicated than I make it out to
be - it is a quick and dirty explanation, after all. However, I think
that the mental framework of a large spreadsheet that everyone has a
copy of is helpful. While this explanation of Bitcoin is undoubtedly
imperfect, I strongly believe that the technical details of how Bitcoin
works will become less relevant over time, just like the intricate
details of how the internet works are irrelevant for most people today.
Yes, you will have to learn some technical details to truly understand
why Bitcoin is resistant to seizure and censorship, just like you have
to learn some technical details to understand why the internet can\'t be
easily shut down. However, you don\'t need to have a complete
understanding of all the parts that make your car or your smartphone
work to enjoy the benefits of using it. The same is true for Bitcoin. As
with most things, the basic idea of what you can do with it is more
important than how it works in detail.

### What You Can Do With It

Bitcoin is money, first and foremost. It behaves like cash, meaning that
you can use it *without asking anyone for permission*. This is true
whether you want to receive it, spend it, or save it. The only thing you
need to open a \"Bitcoin account\" is mathematics, and the only thing
you need to send or receive payments is a communications channel.

As of today, this means that all you need is a smartphone and an
internet connection. In principle, however, you can use any source of
random information to create a Bitcoin wallet, and any communications
channel to send and receive transactions. A pair of dice and a ham radio
will work just as well as a smartphone and the internet, as Bitcoin
enthusiasts have demonstrated in the past. \[Footnote: This is also
why [outlawing
Bitcoin](https://dergigi.com/2021/08/02/implications-of-outlawing-bitcoin/) is
a fool\'s errand.\]

Unfortunately, permissionless transactions and inflation-resistant
savings aren\'t very attractive to most people. Until one is forced to
understand the importance of these basic use cases, it is easy to
dismiss Bitcoin as a speculative asset or mania. However, once your bank
account gets frozen because you bought or sold the wrong thing, or your
account gets closed because you dealt with the wrong person, or your
savings get obliterated because of hyperinflation, or you are forced to
flee your country and want to have your wealth intact, the question of
\"what can I do with bitcoin\" becomes obsolete. 

As time progresses, more and more people will be forced to understand
the importance of Bitcoin simply due to the trajectory of the prevailing
systems. The natural end-state of fiat money is hyperinflation, and the
natural end-state of centralized control is authoritarian censorship.
Bitcoin is the antidote to both of these ills.

### Why It Is Important

Bitcoin radically changes our collective assumptions about what money is
and who should be in control of it. The world is going digital, and it
becomes more apparent every day that uncensorable and natively digital
money is essential for a free society. In addition to that, Bitcoin is
important because it offers an alternative to the debt-based money that
the world is so addicted to. Bitcoin is independent of governments and
corporations, and as its short history has shown, it is extremely
resistant to subversion. This independence, combined with the unchanging
nature of Bitcoin\'s monetary properties, makes bitcoin a valuable asset
to be held by companies, individuals, and countries alike. With each
passing day of Bitcoin\'s operation, trust in the system will increase,
which will make its adoption and value increase. The earlier you will be
able to understand this process, the better your position in a
bitcoinized world will be.

It is worth pointing out that Bitcoin\'s mere survival is enough to put
it on the world stage. Its incentive structure has put in motion a
series of events that is best described as the
ongoing *bitcoinization* of our world. Whether this process will be a
gradual, multi-decade one, or a violent, single-digit year one is yet to
be seen. I believe it will be the latter. I believe that Bitcoin\'s
incentives are strong enough and its operation antifragile enough for it
to absorb other monies and stores of value quicker than most expect.
While the hyperinflations of the 21st century will happen independently
of Bitcoin\'s existence, the economic reality that Bitcoin forces upon
the rest of the world must not be underestimated. It is serendipitous
that the ongoing digitization of our world coincides with the
beyond-irresponsible money printing of central banks. This serendipity,
combined with the exponentially increasing pace of change in our global
society, is the perfect setting for what is aptly
named *hyperbitcoinization:* a rapid, bitcoin-induced demonetization of
currencies and other stores of value such as gold and real estate.

### Who Is Behind It

The short answer is: we don\'t know, and it doesn\'t matter. It doesn\'t
matter because Bitcoin is open and mathematical in nature. Everyone can
inspect it and verify that it operates as expected. Just like we do not
need to know who Pythagoras was in order to understand and use the
Pythagorean theorem, we do not need to know who Satoshi Nakamoto was to
use and understand Bitcoin. Similarly, asking the same question in
regards to fire, the wheel, the internet, and electricity might not lead
to satisfying answers. All these phenomena had inventors/discoverers,
but these people don\'t have any influence over their creation/discovery
anymore.

Bitcoin was released into the wild, and soon after, [Satoshi
disappeared](https://21lessons.com/5/). His gift to the world was
leaving behind free and open-source software that spawns a global,
public, permissionless peer-to-peer network, which in turn spawns
uncensorable and natively digital money.

Bitcoin\'s history, where it came from, and what came before it will be
the focal point of the first chapter. Bitcoin is an idea, and this idea
didn\'t come out of nowhere. The quest for digital money is almost as
old as the internet itself. It was just a matter of time until someone
had the right idea and built a system that would actually work.

### What It Is

*What is Bitcoin?* That\'s the 2.1 quadrillion sats question. It is what
humanity is trying to figure out - and what this book is all about. I
believe that the answer to this question depends on your point of view
and how you are willing to perceive it. To paraphrase Morpheus
\[Footnote: The son of Hypnos and the god of dreams.\]: \"Unfortunately,
no one can be told what Bitcoin is. You have to see it for yourself.\"

It is not readily apparent what people mean when they speak of Bitcoin.
Some are talking about the network, some are talking about the asset,
some are talking about the industry or community around it.

I had an epiphany a couple of years ago when trying to make sense of the
elusive and circular nature of Bitcoin. At least one other person had a
similar insight \[TODO Footnote/cite: \@deepvoid1981\]: Bitcoin is not
only different things to different people, but it is many things at
once, and we lack precise words to talk about it meaningfully. To make
matters worse, all the things that we call Bitcoin are interconnected in
a circular loop. Every part influences the whole.

In short, here is what \"Bitcoin\" is:

1.  Bitcoin is an idea. 
2.  Bitcoin is software implementing this idea.
3.  Bitcoin is a protocol birthed by the software it represents.
4.  Bitcoin is a computer network comprised of nodes running the
    software.
5.  Bitcoin is an absolutely scarce asset emerging from the operation of
    the network.
6.  Bitcoin is a social movement comprised of individuals that are
    holding the asset and participating in the operation of the network.
7.  Bitcoin is a toxic, freedom-loving cult of unwavering believers; an
    intolerant minority from all backgrounds that will do everything in
    their power to defend the idea.

TODO: Give attribution to \@deepvoid1981 as he sees fit.

\[TODO: insert circularity.png\]

What follows is my attempt to break this loop apart, hoping that it
helps to shine some light on this strange phenomenon. To do that, an
explanation of some key concepts is in order.
