---
layout: post
comments: True
title: thoughts-on-learning
---

Been a while. Wanted to freestyle draft some thoughts on learning.

I vaguely want to learn something mathematical or functional. Something like studying number theory, or doing a side project in Haskell or Scala. Not hacking, but crafting. Deliberate, intentional craftsmanship of something. Can be something small (probably *should* be something small, otherwise it won't get built),  but most importantly, should be something I want to work on. Something more compelling than games. That's the tricky part.

Right now i'm toying with the idea of a poker system following the actor model. I know the actor model just enough for this to be interesting, but not enough for it to be trivial. Main question is what language/system to build it with. Tools must be enjoyable, and the right barrier to use. I think it's probably best to stick with python for this, but maybe stick to functional paradigms.


I think erlang might be the best language to work with. Useful for multiple reasons, career and personal, used widely in distributed systems, and functional! Even has built-in actors and FSM's as first-class constructs. Yep, let's go erlang. Although now I'm revisiting the poker idea...

Maybe poker in erlang doesn't make that much sense. It's well suited to modeling with FSMs but not distributed enough to be interesting from a concurrency perspective, at least on the surface. Maybe it is. Ionno.
