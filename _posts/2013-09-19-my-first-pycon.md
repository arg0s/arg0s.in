---
Title: My first Pycon
Date: 2013-09-19
layout: post
comments: true
---

Late last month, [Vinu](//twitter.com/vinuthomas), Aditya, Jay and I attended [Pycon India](//twitter.com/pyconindia) for the first time. I made a presentation about the technology stack we use at [Levitum](http://www.levitum.com) for the backend some of our apps. We use a heady cocktail of `Flask`, `Redis`, `CouchDB`, `Postgres`, `Heroku`, `Gunicorn`, and `Gevent` and have several hundred thousand users using the apps we've built.

Ok there, I just tossed out a bunch of buzz words to make this post sound cool. But read on anyway.

<blockquote class="twitter-tweet"><p>Thanks <a href="https://twitter.com/kennethreitz">@kennethreitz</a> for the appreciation of my talk at <a href="https://twitter.com/pyconindia">@pyconindia</a> <a href="https://twitter.com/search?q=%23pyconindia&amp;src=hash">#pyconindia</a> <a href="https://twitter.com/search?q=%23pyconindia2013&amp;src=hash">#pyconindia2013</a> <a href="http://t.co/IHhAdSgaND">pic.twitter.com/IHhAdSgaND</a></p>&mdash; Aravind Krishnaswamy (@twitortat) <a href="https://twitter.com/twitortat/statuses/374078828915613696">September 1, 2013</a></blockquote>

Turns out, [Kenneth Reitz](http://www.twitter.com/kennethreitz), the python honcho at [Heroku](http://www.heroku.com) was impressed enough to give me a $300 gift card. Kenneth told me normally gives out $10-$25 cards, and I'm only the *second* person to receive one. So clearly, I must be good PR for Heroku.

Here's my slides from the talk, powered by the nifty [Slid.es](http://www.slid.es). I picked up a Pro account with them so I could use my slides offline and not deal with Murphys law kicking in with conference Wi-Fi.

<iframe src="http://slid.es/arg0s/chugging-flask/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

If you like the slides, check out the [full video](//www.youtube.com/embed/swRtWJLUmLI) on Youtube. And if you like the video as well, give me a shout in the comments. I ended up packing in way too much gyaan, and ran out of time. Next time, it'd probably make sense to break these into individual talks.

Fortunately, a bunch of people enjoyed it. I touched upon a number of resources which I hope provide direction for others to dig into further and inspire them explore things on their own.

So far, over 400 views of the slide deck. And plenty of kudos on Twitter.

<blockquote class="twitter-tweet"><p>Always wanted to know about FLASK and HHEROKU. Thanks to <a href="https://twitter.com/twitortat">@twitortat</a> for giving a good insight. Credits to <a href="https://twitter.com/search?q=%23pyconindia2013&amp;src=hash">#pyconindia2013</a> and <a href="https://twitter.com/twitortat">@twitortat</a>.</p>&mdash; Ritesh Bhat (@Ritesh_Bhat) <a href="https://twitter.com/Ritesh_Bhat/statuses/373685329930117120">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p>Awesome talk from <a href="https://twitter.com/twitortat">@twitortat</a> <a href="https://twitter.com/search?q=%23PyConIndia2013&amp;src=hash">#PyConIndia2013</a></p>&mdash; Suplab Debnath (@beingsuplab) <a href="https://twitter.com/beingsuplab/statuses/373685406044131328">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p><a href="https://twitter.com/twitortat">@twitortat</a> some great random gyaan there. <a href="https://twitter.com/search?q=%23pyconindia&amp;src=hash">#pyconindia</a></p>&mdash; Chitra Singh (@chit_raa) <a href="https://twitter.com/chit_raa/statuses/373684946772045824">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p>Great bit of gyaan by <a href="https://twitter.com/twitortat">@twitortat</a> ! <a href="https://twitter.com/search?q=%23pyconindia2013&amp;src=hash">#pyconindia2013</a></p>&mdash; Yes! The Seeker (@90sManiac) <a href="https://twitter.com/90sManiac/statuses/373719997941436417">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p><a href="https://twitter.com/twitortat">@twitortat</a> btw awsome research done and nice presentation... :D</p>&mdash; Pankaj Anand (@Pankajanand26) <a href="https://twitter.com/Pankajanand26/statuses/373730486440300544">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p>Good insights on how powerful can a micro framework like flask be. Thanks to <a href="https://twitter.com/twitortat">@twitortat</a> <a href="https://twitter.com/search?q=%23pyconindia2013&amp;src=hash">#pyconindia2013</a></p>&mdash; Suganthi (@enthudrives) <a href="https://twitter.com/enthudrives/statuses/373689802815569920">August 31, 2013</a></blockquote>

<blockquote class="twitter-tweet"><p>Best talks of <a href="https://twitter.com/search?q=%23PyConIndia2013&amp;src=hash">#PyConIndia2013</a> Day 2 : chugging flask by <a href="https://twitter.com/twitortat">@twitortat</a> and ZeroMQ by <a href="https://twitter.com/cnu">@cnu</a>. Most other talks were advertisement by sponsors</p>&mdash; Salil Panikkaveettil (@salilpa) <a href="https://twitter.com/salilpa/statuses/373835754373263360">August 31, 2013</a></blockquote>

<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Thanks everyone for all the love. *You* made all the hard work that went into the prep *totally* worth it.

Also, thanks to [Vinu](//twitter.com/vinuthomas), Jay, [Kiran](//twitter.com/jackerhack) & [Noufal](//twitter.com/noufalibrahim) for their feedback on the slides.

Lots of great things about the conference

- There were over a 1000 people. That's huge for an event that's totally community volunteer driven. Blows my mind.
- After my talk, a number of interesting people came by and engaged in insightful conversations. Made a bunch of new friends.
- Lots of terrific speakers who came well prepared, and delivered engaging, structured presentations.
- Amazed to see how python is now being used in so many different ways. Even [MPI](http://mpi4py.scipy.org/docs/usrman/intro.html#what-is-mpi) has a python layer now.
- Kiran & Kenneth delivered outstanding keynotes.
- I'd love to know who catered the lunch. I dont think I met anyone who didnt like it.
- Conference wi-fi actually held out throughout, which seems to be a rarity at other events.
- For a change, a lot of the sponsored booths were quite interesting and it was nice to go around and talk to them.

IMO, The only downside of python becoming as big as it is now, is that there were [certain topics](http://in.pycon.org/funnel/2013/88-predicting-black-swan-events) where I probably followed less than 1/3rd of what the knowledgable speaker was presenting due to the nature of the problem domain.

While it's arguably good to be exposed to new topics, I wonder whether it may have been beneficial to have the schedule grouped into topics such as

- python for newbies
- python & web
- python language and its intricacies
- python & scientific community
- python 3.x
- python & devops

This would arguably provide more focus and depth to each of these areas. And in between these, you'd have larger blocks of free time to socialize & just chill.

But then, maybe it's just me that feels this way.

Invariably, there's always tradeoffs between single-track vs multiple-track vs mish-mash. You cant make everyone happy, and shouldnt try.

Great job by the organizers. Congrats for making Pycon 2013 a great success.
