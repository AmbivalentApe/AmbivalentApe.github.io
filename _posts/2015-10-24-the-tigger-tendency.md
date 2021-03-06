---
layout: post
title: the tigger tendency
---


<div class="message">
    overzealous isn't necessarily better
</div>

Where there are no answers, only musings.

The other day I was pinged by an old friend who was after some advice, and as it's always nice to be considered competent I dug in. They are in the process of starting a web cart startup with a mate and were undergoing a bit of a technical wobble: the techy one had decided that they weren't that arsed and so was off. That of course left the other one in a bind, given the beta version of the app was hosted on the errant party's VPS.

The questions started entirely sensibly - what hosting/email providers would you reccomend, and then what was the thin end of the wedge - if you were paying a dev to build this site for you how would you manage their access?

And then of course, I got a bit overzealous<sup>1</sup> and my mind wandered off.

* Pick a PaaS provider or rig something with N*VPS
* Why haven't I played more with AWS? Let's do that now for a bit.
* How would I manage CDN?
* For that matter, how would I manage SSL?
* Could you rig some kind of turnkey approach for prod access to a VPS? Is there a free version of something like powerbroker to be had? How would I enable someone non technical to manage it?
* What would my disaster recovery strategy be. Would **I** pay someone to do prod management? Could I faff around with something like NFLX's Chaos Monkey?

And then I had an intake of breath and a cup of tea, because all of the above is getting carried away with the fun process of doing something interesting, rather than actually understanding what the customer needs and having that shape the response. 

My missus is generally on the verge of throttling me for half finished fluff I tend to play with in the home media space. As someone with a technical mind, but not the inclination to try and do things because they're there and interesting, she's altogether more bearish on fannying on with a RPi running XBMC (which I guess is Kodi now), when you can now buy a $40 Android dongle that rams straight in the back of the telly.

And perhaps more relevantly, it's probably (nearly always?) more expensive to indulge this kind of need to flex your muscles. The cost of running a couple of sensibly sized VPS would run you maybe $40 a month (double that if you want something where someone might go do something if there's an outage), and then of course you have the cost of ensuring your backups are sensibly managed, your load balancing, the money you'd pay someone to triage an outage, the medical bills for the stress ulcer you'd get fretting about a lot of this kind of thing. Compare that to something like AWS which comes with a higher (although they appear to be giving it away atm) sticker price but means so much of the brittleness gets wafted out the door. 

And of course for that matter, if you're building a web cart, why not just take someone like shopify (or one of the dozens of other merchants), pay the even higher fixed cost ($80-$100/mo+) and have *all* the technical risk be someone else's problem? 

I find it (mildly) interesting that from a technical perspective we're often so keen to either get our hands dirty with playing with shiny new toys or that we're so lost in the implementation details that we lose sight of what we're trying to get done. 






--------
<sup>1</sup> And hence the title of this scribble, which is a half remembered fragment from **<a href="http://www.amazon.com/The-Te-Piglet-Benjamin-Hoff/dp/0140230165">The Te of Piglet</a>** which I'd read in a pseudish phase at university and where the 'Tigger Tendency' is defined as the impulsive 'I can do anything' attitude.
